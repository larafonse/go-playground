## File break down

```
package main

import (
  "fmt"
)


func main() {
  fmt.Println("hello world")
}
```

- `package main`: 
  - this tells the go compiler that the package should compile as an executable program instead of a shared library
  - we are decalring this file as the main package file executable?
- `import "fmt"`
  - imports the fmt package. this package is used so we can use print line
- `func main() { fmt.Println("hello, world") }`
  - our entry point function must be called main
## Run file
`go run main.go` or `go run .`

## Build exutable file and run executable file
`go build main.go` then `./main`
