# Assignment for Message Q

**Task**

* [ ] Understand the difference between pipe And Message Q

* [ ] Write a C program following both system-V and POSIX standerd message Q API's
	Details : A ticket generation system containing one server handling ticket delivery and 3 clients requesting tickets.
	each client request server a ticket by passing client no and ticket returning Q id through a Q created by server. Server will calculate A serial no
	other info and pass that structure through the Q id passed by client back to client also server record deliverd ticket info in a file stored in Filesystem

* [ ] Block diagram for above define software architecture.
	
* [ ] An example program using mq_notify()
 


 
## Attached codes

``query_app.c`` : User application.

``query_ioctl.c`` ; Linux driver for string operations.
