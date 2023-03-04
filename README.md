<a href="https://gohugo.io/"><img src="https://raw.githubusercontent.com/gohugoio/gohugoioTheme/master/static/images/hugo-logo-wide.svg?sanitize=true" alt="Hugo" width="565"></a>

A Fast and Flexible Static Site Generator built with love by [bep](https://github.com/bep), [spf13](https://spf13.com/) and [friends](https://github.com/gohugoio/hugo/graphs/contributors) in [Go](https://go.dev/).

### Install Hugo

#### Prerequisite Tools

* [Go](https://golang.org/dl/)

#### Fetch from GitHub

To fetch, build and install from the Github source:

```bash
go install github.com/gohugoio/hugo@latest
```

If you want to compile with Sass/SCSS support use `--tags extended` and make sure `CGO_ENABLED=1` is set in your go environment. If you don't want to have CGO enabled, you may use the following command to temporarily enable CGO only for hugo compilation:

```bash
CGO_ENABLED=1 go install --tags extended github.com/gohugoio/hugo@latest
```

## Install Theme
* [Hugo-Resume](https://themes.gohugo.io/themes/hugo-resume/)
```bash
git submodule update --init --recursive
```

## Start
```bash
hugo serve
```
