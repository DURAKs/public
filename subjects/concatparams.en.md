## concatparams

### Instructions

Write a function that takes the arguments received in parameters and returns them as a `string`.

The arguments must be **separated** by a `\n`.

### Expected function

```go
func ConcatParams(args []string) string {

}
```

### Usage

Here is a possible program to test your function :

```go
package main

import (
	"fmt"
	piscine ".."
)

func main() {
	test := []string{"Hello", "how", "are", "you?"}
	fmt.Println(piscine.ConcatParams(test))
}
```

And its output :

```console
student@ubuntu:~/[[ROOT]]/test$ go build
student@ubuntu:~/[[ROOT]]/test$ ./test
Hello
how
are
you?
student@ubuntu:~/[[ROOT]]/test$
```
