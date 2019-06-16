# BasicStuff
Basic Questions in Computers.

1. Process vs Thread

	A process is a piece of code or program in execution.
	A thread is smallest unit of execution within a process which can be executed independently of other code, a process can have one or more threads(or a light weight process).
	
	i) code, data and files are common to all threads, but they have different set of registers and stack.
	
	ii) Processes are independent of each other. Threads, since they share the same address space are interdependent, so caution must be taken so that different threads don't step on each other.
	
	iii) creation of process is system call/os call whereas creation of thread is at api level, different languages have different way of thread creations.
	
	
2. Scheduling algorithms
	[CPU Scheduling](https://www.studytonight.com/operating-system/cpu-scheduling)
	
3. Page Replacement
	[Page Replacement Algorithms](https://www.geeksforgeeks.org/page-replacement-algorithms-in-operating-systems/)
	
4. Thrashing
	[Techniques to handle Thrashing](https://www.geeksforgeeks.org/operating-system-techniques-handle-thrashing/)
