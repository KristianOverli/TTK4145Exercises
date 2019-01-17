# Reasons for concurrency and parallelism


To complete this exercise you will have to use git. Create one or several commits that adds answers to the following questions and push it to your groups repository to complete the task.

When answering the questions, remember to use all the resources at your disposal. Asking the internet isn't a form of "cheating", it's a way of learning.

 ### What is concurrency? What is parallelism? What's the difference?
 > *Concurrency is the concept of having multiple tasks that will be taken care of at the time you specify. Ex: When moving the mouse your CPU "pause" other actions and prioritise this action first. We split up the tasks in threads, one
 per task.
 Parallelism is when you run multiple cores at the same time. Ex: Two lines at the supermarket, each going to two separate checkout counters. 
 The difference is that parallel is strictly two different CPU´s computing at the same time, while concurrency is managing multiple threads at the same time on a single CPU.*
 
 ### Why have machines become increasingly multicore in the past decade?
 > *This is because the rate that the clock speed increases, have slowed down. To continue to increase computing power, multi cores are used to compute actions in parallel with more cores.*
 
 ### What kinds of problems motivates the need for concurrent execution?
 (Or phrased differently: What problems do concurrency help in solving?)
 > *Your answer here*
 
 ### Does creating concurrent programs make the programmer's life easier? Harder? Maybe both?
 (Come back to this after you have worked on part 4 of this exercise)
 > *Your answer here*
 
 ### What are the differences between processes, threads, green threads, and coroutines?
 > *The process is an executing program that consists of one or more threads.
 A thread is a unit which the processor allocates time for.
 Green threads are threads that you can run on an OS that do not natively support this. Often scheduled by a runtime library or VM. Green threads emulate mulitithreaded environments.
 A coroutine is a subroutine that can have multiple  hold execution and return and continue*
 
 ### Which one of these do `pthread_create()` (C/POSIX), `threading.Thread()` (Python), `go` (Go) create?
 > *Your answer here*
 
 ### How does pythons Global Interpreter Lock (GIL) influence the way a python Thread behaves?
 > *Your answer here*
 
 ### With this in mind: What is the workaround for the GIL (Hint: it's another module)?
 > *Your answer here*
 
 ### What does `func GOMAXPROCS(n int) int` change? 
 > *Your answer here*
