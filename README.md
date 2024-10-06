# nodejs-memory-management

Garbage collector in node js is going to mark and remove any nodes that are not being used from anywhere with a algorithm called `mark and sweeps`. Nodes are managed in a heap in a tree structure if any nodes are detached from the main node.



# Process and Thread.

To understand process and thread you first we have to understand what a `program` is. A program is a executable file that contains all you codes and instruction which when executed, the computer loads all these codes and inctruction in memory and when this is processed by the processor it becomes a process. A active process usage the resources (CPU, RAM) of the computer which is managed by the operating system.

Each process has it's own memory and space therefore one process cannot curropt the memory and space of another process. For eg: chrome runs each of it's tab in it's own process therefore if one tab misbehaves another tab is unaffected.

Now these process have atleast one thread which is called main thread. A process can have multiple threads. Thread is a unit of execution within a process. Imagine this as a thing that travels through the instruction and codes to execute them. Thread consist of `Stack`, `Registers`, `Program Counters`. Thread within a process share memory and space. It is also possible to communicate between threads using their shared memory and space.


<img width="952" alt="image" src="https://github.com/user-attachments/assets/cd36fd22-4233-4690-b99c-dca8922568d1">

