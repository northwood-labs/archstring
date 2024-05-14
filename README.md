# Architecture String

Provides a friendly _U.S. English_ description of the current OS and CPU architecture.

```go
import (
    "fmt"
    "runtime"

    "github.com/northwood-labs/archstring"
)

func main() {
    fmt.Println(
        archstring.GetFriendlyName(runtime.GOOS, runtime.GOARCH),
    )
}
```
