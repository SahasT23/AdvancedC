Module 12: Operating System Basics
• Topics:
– OS Architecture:
∗ Monolithic vs. microkernel vs. hybrid kernel designs.
∗ Kernel vs. user space: privilege levels and system calls.
7
∗ OS components: process manager, memory manager, I/O subsystem, file
system.
∗ Interrupt handling: software vs. hardware interrupts, interrupt descriptor
tables (IDT).
– Process Management:
∗ Process creation (fork, clone) and termination (exit).
∗ Process control blocks (PCB): state, PID, registers, and memory context.
∗ Context switching: saving/restoring CPU state (e.g., x86 registers).
∗ Process states: running, ready, blocked, suspended.
∗ Thread models: kernel-level vs. user-level threads, POSIX threads imple-
mentation.
– Memory Management:
∗ Virtual memory: address spaces, page tables, and TLB.
∗ Paging: page allocation, replacement algorithms (LRU, FIFO).
∗ Segmentation: segment descriptors and protection.
∗ Memory allocation in kernel: slab allocators, buddy system.
∗ Demand paging and swapping for memory efficiency.
∗ Memory protection: read-only pages, no-execute (NX) bits.
– Scheduling:
∗ Scheduling algorithms: FCFS, SJF, round-robin, multilevel feedback queues.
∗ Real-time scheduling: RMS, EDF, deadline monotonic.
∗ Priority-based scheduling and preemption mechanisms.
∗ CPU affinity and load balancing in multiprocessor systems.
∗ Scheduling in Linux: Completely Fair Scheduler (CFS), O(1) scheduler.
– File Systems:
∗ File system structures: inodes, superblocks, directory entries.
∗ File system types: FAT, ext4, NTFS, and their C implementations.
∗ File descriptors and I/O operations (read, write, fsync).
8
∗ Virtual file system (VFS) layer for abstraction.
∗ File system caching and buffer management.
– Inter-Process Communication:
∗ Pipes: named and unnamed pipes for data streaming.
∗ Message queues for structured data exchange.
∗ Shared memory for high-speed IPC.
∗ Semaphores for synchronization and mutual exclusion.
∗ Signals for event notification and handling.
– Device Management:
∗ Character vs. block devices: differences and C interfaces.
∗ Device drivers: structure, initialization, and I/O handling.
∗ Interrupt handling for device events.
∗ DMA for efficient data transfer.
– System Calls:
∗ System call interface: int 0x80, syscall instruction.
∗ Implementing system calls in C for process and memory management.
∗ Error handling: errno and error codes.
∗ System call tracing with strace.
– OS Security:
∗ Privilege separation and user permissions.
∗ Address space layout randomization (ASLR).
∗ System call filtering (e.g., seccomp).
∗ Kernel module security and loading mechanisms.
– OS Case Studies:
∗ Linux kernel: process scheduling, memory management, and VFS.
∗ xv6: a teaching OS for understanding Unix-like systems in C.
∗ RTOS concepts: task scheduling and interrupt handling.
