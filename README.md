# browser

Helpers to open URLs, readers, or files in the system default web browser.

## Usage

```go
import "github.com/ifrstr/browser"

err = browser.OpenURL(url)
err = browser.OpenFile(path)
err = browser.OpenReader(reader)
```
