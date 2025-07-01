#parrallel_processing 
- to implement go has Mutex type (a struct) in the sync package
``` 
var mutex = &sync.Mutex()
func credit() {
	for i:=0; i<5; i++ {
		mutex.Lock()
		balance+=100
		time.Sleep(time.Duration(ranD.iNTN(100)) * TIME.millisecond)
		fmt.Println("After crediting, balanc is",balance)
	}
}


```

