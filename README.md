## Answers
Please write your answers here

q1)b
q2)c
q3)d
q4)b
q5)a
q6)c
q7)a
q8)a
q9)d
q10)b
q11)c

q12) The different states a process can be with in xv6 operating system is 
      Running: currently executing instruction , Runnable: Ready to run but waiting , sleeping  : waiting for an event to complete , zombie : process has terminated but information is still needed

q13)File System Structure in XV6:
    Superblock: Contains file system metadata.
    Inodes: Store information about files.
    Data blocks: Actual file content storage.

q14) The difference between system calls and library functions in the context of XV6 is ystem Calls vs. Library Functions in XV6:System Calls: Interface to the kernel for OS services (e.g., fork, exec).Library Functions: Higher-level  
     functions built on system calls ex:printf

q15) The memory paging work in XV6 as Fixed-size blocks of physical memory and the page tables withh virtual to physical addreses and the benefits of using paging in memory management are Efficient use of memory, protection,
     nd easy sharing.

q16)The three essential shell commands in the XV6 operating system are 
    ls: List directory contents. 
    cd: Change the current working directory. 
    rm: Remove files or directories.

q17)The concept of process synchronization in XV6 is  essential because it Ensures proper execution order and the mechanisms are used to achieve it are Locks, semaphores, and condition variables.

q18)In the XV6 operating system, interrupts play a crucial role in managing and responding to external events and hardware events.
    Interrupt Handling in XV6:
    Role: It Enables the CPU to respond to external events.
    Handling: Handled by interrupt service routines (ISRs)

q19)virtual memory is a memory management technique that provides an "idealized abstraction of the storage resources that are actually available on a given machine" which creates the illusion to users of a very large (main) memory.
    Implementation: Paging and demand paging.
    Advantages: Allows efficient use of memory resources, isolation, and flexibility.

q20)Boot Process in XV6:BIOS/UEFI: 
   Power-On Self-Test (POST): When the computer is powered on, the hardware undergoes a self-test (POST) to check the basic functionality of components like the CPU, memory, and peripherals.
    BIOS Initialization: The Basic Input/Output System (BIOS) is activated, initializing essential hardware and locating the boot device (typically a hard drive or SSD).
    Master Boot Record (MBR): The BIOS loads the Master Boot Record from the boot device into memory. The MBR contains the first-stage bootloader.
    Bootloader Execution: The bootloader, such as GRUB in the case of XV6, takes control. It loads the second-stage bootloader (like the XV6 bootloader) from the disk into memory.
    Kernel Loading: The second-stage bootloader loads the XV6 kernel into memory. The kernel is the core of the operating system.
    Kernel Initialization: Once loaded, the XV6 kernel initializes the essential components, sets up data structures, and prepares the system for execution.
    Transition to User Mode: Finally, the kernel transfers control to the user-mode code, allowing user applications to start executing.






