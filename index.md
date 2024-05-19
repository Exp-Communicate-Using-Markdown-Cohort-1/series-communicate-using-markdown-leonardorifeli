# Creating a new markdown file

I'm a Brazilian Data Scientist & Mathematician! Remember that there is no code faster than no code. Gopher since 2017.

# Follow-me

My GitHub is @leonardorifeli.

# About Golang

![golangimg](https://dkrn4sk0rn31v.cloudfront.net/uploads/2022/10/o-que-e-e-como-comecar-com-golang.jpg "Golang")

### Checklist

- [x] Creating First Hello World
- [x] Example with goroutines

### Writing hello world

```golang
package main

import "fmt"

func main() {
  fmt.Println("Hello World!")
}
```

### Goroutines example

(needed vim editor)

```bash
$ mkdir golang_project
$ cd golang_project
$ vim main.go
```

in vim editor, paste this code:

```golang
package main

import "fmt"

func main() {
  go sayHello("Leonardo Rifeli")
  go sayHello("Best Brazilian Data Scientist & Mathematician")
}

func sayHello(name string) {
  fmt.Printf("Hello %s", name)
}
```
