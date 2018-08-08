# Assignment for Synchronization Mechanisms

**Task**

*  Understand concept of Kernel Mode and User Mode.
*  Create sample code for the following...
	* [ ]  Dead-lock scenario and solution.
	* [ ]  Producer-consumer problem and solution.
 
## Attached codes

``deadlock.c``:Code for deadlock scenario.

``deadsolved.c``:Deadlock resolved.

``pcproblem``:Producer cosumer problem.

``pcsolved``:Solution for producer cosumer problem using semaphore.


### Kernel Mode and User Mode.

  A computer operates in two modes which are user mode and kernel mode. When the computer is running application software, it is in user mode. After the application software request for hardware, the
computer enters kernel mode. The kernel is the core part of operating system. Subsequently, the computer
frequently switches between user mode and kernel mode. Most critical tasks of the operating system are
executing in the kernel mode. The key difference between User Mode and Kernel Mode is that user mode is
the mode in which the applications are running and kernel mode is the privileged mode to which the
computer enters when accessing hardware resources.


**1.Kernel Mode**

  In Kernel mode, the executing code has complete and unrestricted access to the underlying hardware. It can execute any CPU instruction and reference any memory address. Kernel mode is generally reserved for the lowest-level, most trusted functions of the operating system. Crashes in kernel mode are catastrophic; they will halt the entire PC. 


**##2.User Mode**

  In User mode, the executing code has no ability to directly access hardware or reference memory. Code running in user mode must delegate to system APIs to access hardware or memory. Due to the protection afforded by this sort of isolation, crashes in user mode are always recoverable. Most of the code running on your computer will execute in user mode. 
