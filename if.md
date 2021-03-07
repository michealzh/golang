```go
package main

import "fmt"

func main() {
	a := 10
  
	//支持一个初始化变量
	//初始化变量为block级别,同时隐藏外部同名变量
	if a := 1; a < 2 {
		fmt.Println("var in if statement:", a)
	}
	fmt.Println("var in outside statement: ", a)
}

```
