# Welcome to MkDocs

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

``` py
import tensorflow as tf
```

``` py title="bubble_sort.py"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```

```go
package main

import (
	"fmt"
)

/**
 * @Author: yirufeng
 * @Date: 2021/8/23 4:33 下午
 * @Desc:
 **/

func main() {

	flag := true

	var l, r byte

	if flag {
		l, r = 'r', '1'
	}

	fmt.Println(l == 'r')
	fmt.Println(r == 'r')


	num := -10
	a := -num
	fmt.Println(a)


	s := []int{3,2,4}

	copy(s[1:], s[0:])

	s[0] = 100
	fmt.Println(s)

	fmt.Println((-3)%2)
}
```