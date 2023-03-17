# Process and Thread
(Quick Explanation)

## Quick Explanation
Processes and threads are two terms that we have heard many times, get an introductory idea and understanding of these terms. A program is written in some high-level languages like C++, Java, etc. But at the basic level, the computer can only understand the binary codes, which are 0's and 1's. Therefore, a compiler is used to convert the program into machine code, which is understandable by the machine.

After the program has been converted into binary executable code, it is ready for execution. However, having the binary code is not enough for a program to execute or for a program to tell the computer what it wants to do. It has to be loaded into the memory, and for a program to execute. It is the operating system, which we have been discussing so far. The operating system will help in loading the executable program into the memory, allocate its resources, and then the program will begin its execution. Program that is written and is ready for execution, but until that time, it is just a passive entity.

When a program starts execution, at that time, we call it a process. A process can be thought of as a program in execution. So, in earlier computers, it supported only one process or one program at a time. But in today's computer, it supports multiple processes or programs running at the same time. Even one single program can have many processes associated with it. So, when a program begins its execution, at that time, it is known as the process

When a thread is created, it means a new thread is added to the existing process. This usually involves allocating a new structure, initializing the thread stack, and setting up the necessary synchronization mechanisms.

Process termination involves releasing all resources allocated for the process, including memory and other resources. This is done by sending a signal to the process, informing it to clean up and exit.

Thread termination involves freeing the allocated structure and stack space for the thread. This can occur when the thread completes its execution or is explicitly terminated by another thread or the operating system. It is important to ensure that all shared resources are properly cleaned up to prevent synchronization issues.



## Ubuntu Process and Thread Exercise

1. Check Service Status of SSH
   
    <img src="https://cdn.discordapp.com/attachments/940456976234729542/1086143636976181319/image.png" width="500px">

2. Stop SSH Service
   
    <img src="https://cdn.discordapp.com/attachments/940456976234729542/1086144920726814730/image.png" width="500px">
  
3. Start the SSH Service
   
   <img src="https://cdn.discordapp.com/attachments/940456976234729542/1086145326014013520/image.png" width="500px">
  
4. Manage SSH
   
   <img src="https://cdn.discordapp.com/attachments/940456976234729542/1086145906828640256/image.png" width="500px">
  
5. Monitor System
   
   <img src="https://cdn.discordapp.com/attachments/940456976234729542/1086146305438527508/image.png" width="500px">
