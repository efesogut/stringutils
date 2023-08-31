# stringutils

A basic golang package for demonstration purpose. Package currently contains 
only one function:

```go
func Reverse(s string) (string, error)
```

---

## Installation

Go to your project root, where `go.mod` file exists, than grab the library via:

```bash
go get github.com/efesogut/stringutils
```

---

## Usage

```go
package main

import (
	"fmt"

	"github.com/efesogut/stringutils"
)

func main(){
	reversed, err := stringutils.Reverse("efesogut")
	if err != nil {
		log.Fatal(err)
	}    
	fmt.Println(reversed)
}
```

---

## Contributor(s)

* [Efe Söğüt](https://github.com/efesogut) - Creator, maintainer

---

## Contribute

All PR’s are welcome!

1. `fork` (https://github.com/efesogut/stringutils/fork)
1. Create your `branch` (`git checkout -b my-feature`)
1. `commit` yours (`git commit -am 'add some functionality'`)
1. `push` your `branch` (`git push origin my-feature`)
1. Than create a new **Pull Request**!

---

## License

This project is licensed under MIT

---

This project is intended to be a safe, welcoming space for collaboration, and
contributors are expected to adhere to the [code of conduct][coc].

[coc]: https://github.com/efesogut/stringutils/blob/main/CODE_OF_CONDUCT.md