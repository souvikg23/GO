# Go Learning Roadmap (Concurrency Focused)

**Timeline:** 3 Days  
**Total Hours:** 12  
**Experience Level:** Intermediate (already familiar with at least one other programming language)

---

## Day 1: Core Language and Setup

### Hour 1: Installation and Basic Tour

- Install Go: [https://go.dev/doc/install](https://go.dev/doc/install)
    
- Setup project with `go mod init`
    
- Run a simple "Hello, World" program using `go run`
    
- Complete the "Basics" section of A Tour of Go: [https://go.dev/tour/basics/1](https://go.dev/tour/basics/1)
    

**Checkpoint**

- Able to write and execute a basic Go program
    
- Comfortable with variables, control flow, and basic syntax
    

---

### Hour 2: Types, Functions, Interfaces

- Continue with "Methods and Interfaces" and "More Types" in A Tour of Go
    
- Practice defining structs and implementing interfaces
    
- Write a simple CLI calculator or geometric shape processor using structs and interfaces
    

**Checkpoint**

- Can use structs, interfaces, and slices idiomatically
    
- Understand method receivers vs functions
    

---

### Hour 3: Packages, Errors, Tooling

- Learn Go’s package system (`main`, `fmt`, `errors`)
    
- Explore Go's error handling (`errors.New`, custom error types)
    
- Run `go fmt`, `go vet`, and `go test` on sample code
    
- Organize utility code into separate packages
    

**Checkpoint**

- Confident using Go's standard library and project structure
    
- Familiar with Go's tooling ecosystem
    

---

### Hour 4: Practice and Consolidation

- Build a simple modular text processing CLI tool
    
- Write basic unit tests using `testing` package
    
- Review: [https://go.dev/doc/code](https://go.dev/doc/code)
    

**Checkpoint**

- Able to create a tested and modular Go utility with proper formatting and project layout
    

---

## Day 2: Intermediate Concepts and Concurrency Foundations

### Hour 1: Pointers, Memory, Maps

- Learn how Go handles memory with pointers
    
- Understand slice vs array behavior
    
- Practice working with maps and nil checks
    
- Read from: [https://go.dev/doc/effective_go](https://go.dev/doc/effective_go)
    

**Checkpoint**

- Can confidently use pointers, slices, and maps
    
- Aware of Go’s memory safety and zero values
    

---

### Hour 2: Introduction to Goroutines

- Learn goroutine syntax using `go func()`
    
- Create programs with concurrent printing
    
- Observe scheduling and interleaved output
    

**Checkpoint**

- Can launch concurrent tasks using goroutines
    
- Understand goroutines are scheduled independently
    

---

### Hour 3: Channels and Synchronization

- Read: [https://go.dev/doc/effective_go#channels](https://go.dev/doc/effective_go#channels)
    
- Create and use buffered and unbuffered channels
    
- Build a simple worker pool
    
- Learn the `select` statement
    

**Checkpoint**

- Understand synchronization via channels
    
- Know how to use `select` to multiplex channel operations
    

---

### Hour 4: Patterns and Debugging

- Build a producer-consumer pattern
    
- Use `go run -race` to detect race conditions
    
- Add logs to trace goroutine execution
    

**Checkpoint**

- Recognize and resolve data races
    
- Built at least one idiomatic concurrent program using channels
    

---

## Day 3: Advanced Concurrency and Practical Application

### Hour 1: Mutexes and WaitGroups

- Use `sync.Mutex` for protecting shared resources
    
- Practice `sync.WaitGroup` for coordinating goroutines
    
- Explore `sync.Once` and `sync.Map`
    

**Checkpoint**

- Can apply mutexes to avoid race conditions
    
- Know when to use WaitGroups vs Channels
    

---

### Hour 2: Timeouts and Contexts

- Read: [https://go.dev/blog/context](https://go.dev/blog/context)
    
- Use `context.WithCancel`, `context.WithTimeout`
    
- Pass context to goroutines and HTTP handlers
    

**Checkpoint**

- Can manage goroutine lifecycle using context
    
- Understand cancellation propagation
    

---

### Hour 3: Final Mini Project

- Suggested project: Concurrent Web Crawler or File Downloader
    
- Use Goroutines + Channels + Mutex + Context
    
- Implement retries, timeouts, and shared state
    

**Checkpoint**

- Designed and implemented a concurrent program from scratch
    
- Demonstrated integration of concurrency primitives in one app
    

---

### Hour 4: Review and Patterns

- Read: [https://go.dev/blog/pipelines](https://go.dev/blog/pipelines)
    
- Study common concurrency idioms (fan-in, fan-out, pipelines)
    
- Refactor and document mini project
    
- Summarize learnings and note idioms
    

**Checkpoint**

- Recognize Go’s idiomatic concurrency patterns
    
- Confident applying concurrency tools in new projects
    

---
