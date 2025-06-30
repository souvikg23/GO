1) Define a struct for it
2) initiate a struct object of that struct
3) use unmarshal function from encoding/json package

```
num:=  json.Unmarshal([]byte(jsonstreing),&object)
```

