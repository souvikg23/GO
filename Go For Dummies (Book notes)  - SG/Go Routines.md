#parrallel_processing 
- used for concurrency
- Similar to threading in other lingos
- its a lightweight thread managed by Go runtime
- So to run a function in parallel threading you can add "go" keyword before it
```
package main

  

import (

    "fmt"

)

  

func say(s string, times int) {

    for i := 0; i < times; i++ {

        fmt.Println(i, s)

    }

}

  

func main() {

    go say("Hello", 4)

    go say("world", 2)

    fmt.Scanln()

}
```

- the scanln is needed for getting an output
	- becauseafter go routine is called, the control is immediately given back to the caller
	- so without scanln waiting for user input, the main function will terminate after both go routines are called and won't print
	- 