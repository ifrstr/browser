# browser

Helpers to open URLs, readers, or files in the system default web browser.

## Install

```sh
go get gopkg.ilharper.com/x/browser
```

## Usage

```go
import "gopkg.ilharper.com/x/browser"

err = browser.OpenURL(url)
err = browser.OpenFile(path)
err = browser.OpenReader(reader)
```

[![Go Reference](https://pkg.go.dev/badge/gopkg.ilharper.com/x/browser.svg)](https://pkg.go.dev/gopkg.ilharper.com/x/browser)

## LICENSE

[BSD 2-Clause "Simplified" License](https://github.com/ifrstr/browser/blob/master/LICENSE)
