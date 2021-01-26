Exercise 1 - Theory questions
---------------------------------

What is the difference between concurrency and parallelism?
-------------------------------------------------------------
Parallellism is when different processes run at the exact same time, often on different processors. Concurrency is the possibillity of processes happening at the same time, but does not need to use the same amount of time or same duration.

Why have machines become increasingly multicore in the past decade?
---------------------------------------------------------------------
Because we need more computer power to run parallell or concurring processes.

Why do we divide software (programs) into concurrently executing parts (like threads or processes)?
-----------------------------------------------------------------------------------------------------
(Or phrased differently: What problems do concurrency help in solving?)

because we don't want one lagre process to block i.e the CPU from doing other critical tasks.

Does creating concurrent programs make the programmer's life easier? Harder? Maybe both?
-------------------------------------------------------------------------------------------------
(Come back to this after you have worked on part 4 of this exercise)

I would say it makes the program and application itself better and more robust, and in that term the programmers life easier. on the other hand it makes the maintance and programming more complex, and in that way harder. 

What is the conceptual difference between threads and processes?
----------------------------------------------------------------------
processes are independent from each other running on independent memory space, while threads are part of processes running on a shared memory space.

Some languages support "fibers" (sometimes called "green threads") or "coroutines"? What are they?
---------------------------------------------------------------------------------------------------
Green threads scheduled by a virtual machine or a runtime library. Coroutines uses generalized sub-routines to implement tools for handeling concurrency

What is the Go-language's "goroutine"? A C/POSIX "pthread"?
-------------------------------------------------------------
A goroutine is a basic thread of execution, and are functions working in the same address space. A pthread is a strandarized programming interface for making threads in C.

In Go, what does func GOMAXPROCS(n int) int change?
----------------------------------------------------------
It lets the programmer set themaximum number of CPUs that can be executing simultaneously.
 
 
 
 
