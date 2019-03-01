# JX-Docs-Material Theme

JX Docs Material is a clean material design theme for [Hugo](http://gohugo.io/) used by the Jenkins X docs site.

![](https://github.com/SharePointOscar/jx-docs-theme/blob/master/static/images/jx-docs-material.png)

# Demo
There will be a running demo soon.

## Features

- Simple Material Design by [Material](http://daemonite.github.io/material)
- Google Analytics (to be implemented)
- Pagination
- Tags
- Categories
- Highlighting source code (to be implemented)

## Installation

```shell
$ mkdir themes
$ cd themes
$ git clone https://github.com/SharePointOscar/jx-docs-theme.git
```

## Usage

```shell
$ hugo server -t jx-docs-material -w -D
```

## Configuration

config.toml

```toml
theme="jx-docs-material"
baseurl = "Your Site URL"
languageCode = "en-us"
title = "Your Site Title"
MetaDataFormat = "toml"
copyright = "© 2019 Copyright Text"

```

## Contributing Guideline

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request