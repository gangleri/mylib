Very basic Go package I used to set-up and test publishing 
packages using [Canonical][1] import paths.

install:
```bash
go get gangleri.io/pkg/mylib
```

usage:
```go
import (
        "gangleri.io/pkg/mylib"
        ...
)
```


HTML used to publish the package:

```html
<html>
    <head>
        <meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
        <meta name="go-import" content="gangleri.io/pkg/mylib git https://github.com/gangleri/mylib">
    </head>
    <body>
    Nothing to see here; <a href="https://github.com/gangleri/mylib">move along</a>.
    </body>
</html>
```



[1]: https://golang.org/doc/go1.4#canonicalimports