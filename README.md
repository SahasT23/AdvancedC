5.1 Module 1: Review of C Fundamentals
• Topics:
– Data types (int, char, float) and their memory representations.
– Advanced pointer usage: pointer arithmetic, const, and volatile qualifiers.
– Bit manipulation for system flags and registers.
– Structures, unions, and enums for data organization.
– Memory layout: stack, heap, and static storage.
– Endianness and its impact on cross-platform code.
• Reading: The C Programming Language by Kernighan and Ritchie, Chapters 1–5;
C Programming: A Modern Approach by K.N. King, Chapters 1–6.
5.2 Module 2: Memory Management
• Topics:
– Dynamic memory allocation (malloc, calloc, realloc, free).
– Memory leaks, dangling pointers, and mitigation strategies.
– Custom memory allocators for system software.
– Memory alignment for performance optimization.
– Stack vs. heap trade-offs in system programming.
– Memory pools for predictable allocation in constrained environments.
– Heap and Stack algorithms and management.
3
• Reading: C Programming: A Modern Approach by K.N. King, Chapter 17; Expert
C Programming by Peter van der Linden, Chapter 7.
5.3 Module 3: Pointers and Function Pointers
• Topics:
– Pointer arithmetic for array and buffer manipulation.
– Function pointers for callback mechanisms and dynamic dispatch.
– Void pointers for generic programming.
– Pointer-to-pointer for multi-level data structures.
– const and volatile for safe memory access.
– Function pointer tables for system event handling.
• Reading: Expert C Programming by Peter van der Linden, Chapter 4; C Program-
ming: A Modern Approach by K.N. King, Chapter 13.
5.4 Module 4: Advanced Data Structures
• Topics:
– Linked lists and trees for system resource management.
– Circular buffers for data streaming.
– Hash tables with collision resolution (chaining, open addressing).
– Tries for efficient string processing.
– Bit arrays for compact state tracking.
– Memory-efficient data structures for system utilities.
• Reading: Data Structures and Algorithm Analysis in C by Mark Allen Weiss,
Chapters 3–5; Algorithms in C by Robert Sedgewick, Part 1.
5.5 Module 5: Concurrency in System Programming
• Topics:
– POSIX threads: thread creation (pthread_create), joining, and detachment.
– Synchronization primitives: mutexes, semaphores, condition variables.
– Priority inversion and priority inheritance mechanisms.
– Atomic operations using __atomic builtins for lock-free programming.
4
– Memory barriers for ensuring operation ordering.
– Spinlocks for low-latency synchronization in high-performance systems.
– Real-time scheduling: rate-monotonic scheduling (RMS), earliest deadline first
(EDF).
– Deadlock detection and prevention strategies.
– Thread pools for efficient task management.
– Interrupt-driven concurrency for system events.
• Reading: Programming with POSIX Threads by David R. Butenhof, Chapters 2–4;
Real-Time Concepts for Embedded Systems by Qing Li, Chapters 5–8; The Art of
Multiprocessor Programming by Maurice Herlihy, Chapter 7.
5.6 Module 6: System Programming
• Topics:
– File I/O operations (open, read, write, close).
– Process management: fork, exec, wait.
– Signal handling for asynchronous events (signal, sigaction).
– Inter-process communication: pipes, message queues, shared memory.
– Memory-mapped I/O for device interaction.
– System calls for resource management.
• Reading: Advanced Programming in the UNIX Environment by W. Richard Stevens,
Chapters 8–10; Linux System Programming by Robert Love, Chapter 3.
5.7 Module 7: Compilers and Cross-Compilation
• Topics:
– Compiler pipeline: preprocessing, lexical analysis, parsing, AST generation,
code generation, optimization, and linking.
– Cross-compilation for platforms like ARM, RISC-V, and x86.
– Linker scripts for custom memory layouts (e.g., separating code and data sec-
tions).
– Code generation: instruction selection, register allocation, and peephole opti-
mization.
– Optimization flags: -O2, -Os, -march for architecture-specific tuning.
5
– Inline assembly for low-level operations (e.g., CPU-specific instructions).
– Link-time optimization (LTO) for whole-program optimization.
– Toolchain customization: building GCC for specific targets.
– Debugging symbols and map file analysis for code size optimization.
– Compiler diagnostics and static analysis for error detection.
– Makefiles and more flags.
• Reading: Linkers and Loaders by John R. Levine, Chapters 1–4; Compilers: Prin-
ciples, Techniques, and Tools by Aho et al., Chapters 1–3; GCC documentation.
5.8 Module 8: Performance Optimization
• Topics:
– Code profiling with gprof and hardware counters.
– Loop optimization: unrolling, vectorization, and loop fusion.
– Cache optimization: data locality and alignment.
– Function inlining and dead code elimination.
– Compiler-assisted optimizations: -ffast-math, -funroll-loops.
– Power-aware programming for battery-powered systems.
– Trade-offs between code size, speed, and resource usage.
• Reading: Computer Systems: A Programmer’s Perspective by Bryant and O’Hallaron,
Chapter 5; Optimizing Compilers for Modern Architectures by Randy Allen, Chap-
ter 2.
5.9 Module 9: Secure Coding
• Topics:
– Buffer overflow prevention using bounds checking.
– Input validation for robust system interfaces.
– Stack-smashing protection with canary values.
– Secure memory handling to avoid leaks and overwrites.
– Mitigating side-channel attacks (e.g., timing, cache attacks).
– Cryptographic primitives for secure data handling.
6
• Reading: Secure Coding in C and C++ by Robert C. Seacord, Chapters 2–3; The
Art of Software Security Assessment by Dowd et al., Chapter 5.
5.10 Module 10: Debugging and Profiling
• Topics:
– GDB for breakpoint-based debugging and backtracing.
– Valgrind for memory leak detection and profiling.
– Memory sanitizers for detecting undefined behavior.
– Hardware trace tools for runtime analysis.
– Profiling system calls and interrupt handlers.
– Debugging concurrent programs with thread-aware tools.
• Reading: The Art of Debugging with GDB (online); Valgrind User Manual (on-
line).
5.11 Module 11: Advanced System Programming
• Topics:
– Advanced file I/O: asynchronous I/O, memory-mapped files.
– Process synchronization with semaphores and monitors.
– Signal handling for robust system utilities.
– Shared memory for high-performance IPC.
– Device driver basics for peripheral interaction.
– System call optimization for performance-critical applications.
• Reading: Advanced Programming in the UNIX Environment by W. Richard Stevens,
Chapters 10–12; Linux Device Drivers by Jonathan Corbet, Chapter 4.
5.12 Module 12: Operating System Basics
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


-- Might need to remove Linux kernel and security stuff. Keep to OS levels. 
-- Will not spend too much time on this, as I will be mostly working in C++