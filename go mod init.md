go mod init example/hello 
- example is the repository location and hello is the module (abir)


### `%v` — Default format

- It prints the **value** in a default format, depending on its type.
    
- It's useful when you don't care about formatting specifics, just want to print the value.


**The function also returns a `string`. In Go, a function whose name starts with a capital letter can be called by a function not in the same package. This is known in Go as an exported name.**


For local module import - 
use the [`go mod edit` command](https://go.dev/ref/mod#go-mod-edit) to edit the `example.com/hello` module to redirect Go tools from its module path (where the module isn't) to the local directory (where it is).