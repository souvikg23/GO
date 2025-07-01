#parrallel_processing 
-  routines that forces to operate on the shared var one thread at a time
- the sync/atomic go package provide  low level atomic  memory primitives'
`var mutex = &sync.Mutex()`
`func credit() {`
	`for i:=0; i<5; i++ {`
		`atomic.AddInt64(&balance,100)`
		`time.Sleep(time.Duration(ranD.iNTN(100)) * TIME.millisecond)`
		`fmt.Println("After crediting, balanc is",balance)`
	`}`
`}`

- 
