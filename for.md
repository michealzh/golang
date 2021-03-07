### for without condition

```go
package main

import "fmt"

func main() {
	i := 1
	for {
		i++
		if i > 10 {
			break
		}
		fmt.Println("i is : ", i)
	}
	fmt.Println("finished")
}

```

### for with condition

```go
package main

import "fmt"

func main() {
	i := 1
	for i < 10 {
		i++
		fmt.Println("i is : ", i)
	}
	fmt.Println("finished")
}

```

### 
```go
package main

import "fmt"

func main() {
	a := 1
	for i := 1; i < 3; i++ {
		a++
		fmt.Println(a)
	}
}

```
