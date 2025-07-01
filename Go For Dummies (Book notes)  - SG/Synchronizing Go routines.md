#parrallel_processing 
- one way to do is by using Waiting to complete all the go routines
```
var wg sync.WaitGroup
```
-  `wg.Add(1)`     Adds 1 to counter
- `wg.Wait()`      waits till the WaitGroup object is 0
- `wg.Done()`      decrement 1 from waitgroup object
- 