<<<<<<< HEAD
# Contents List

## Module 1: Review of C Fundamentals
### • Topics:
=======
5.1 Module 1: Review of C Fundamentals
• Topics:

>>>>>>> ff7cf03c05044109730d321b883fc211c14de0cb
– Data types (int, char, float) and their memory representations.

– Advanced pointer usage: pointer arithmetic, const, and volatile qualifiers.

– Bit manipulation for system flags and registers.
<<<<<<< HEAD
– Structures, unions, and enums for data organisation.
=======

– Structures, unions, and enums for data organization.

>>>>>>> ff7cf03c05044109730d321b883fc211c14de0cb
– Memory layout: stack, heap, and static storage.

– Endianness and its impact on cross-platform code.

<<<<<<< HEAD
## Module 2: Memory Management
### • Topics:
=======
• Reading: The C Programming Language by Kernighan and Ritchie, Chapters 1–5;

C Programming: A Modern Approach by K.N. King, Chapters 1–6.

5.2 Module 2: Memory Management

• Topics:

>>>>>>> ff7cf03c05044109730d321b883fc211c14de0cb
– Dynamic memory allocation (malloc, calloc, realloc, free).

– Memory leaks, dangling pointers, and mitigation strategies.

– Custom memory allocators for system software.
<<<<<<< HEAD
– Memory alignment for performance optimisation.
=======

– Memory alignment for performance optimization.

>>>>>>> ff7cf03c05044109730d321b883fc211c14de0cb
– Stack vs. heap trade-offs in system programming.

– Memory pools for predictable allocation in constrained environments.

– Heap and Stack algorithms and management.

<<<<<<< HEAD
## Module 3: Pointers and Function Pointers
### • Topics:
=======
3

• Reading: C Programming: A Modern Approach by K.N. King, Chapter 17; Expert

C Programming by Peter van der Linden, Chapter 7.

5.3 Module 3: Pointers and Function Pointers

• Topics:

>>>>>>> ff7cf03c05044109730d321b883fc211c14de0cb
– Pointer arithmetic for array and buffer manipulation.

– Function pointers for callback mechanisms and dynamic dispatch.

– Void pointers for generic programming.

– Pointer-to-pointer for multi-level data structures.

– const and volatile for safe memory access.

– Function pointer tables for system event handling.

<<<<<<< HEAD
## Module 4: Advanced Data Structures
### • Topics:
=======
• Reading: Expert C Programming by Peter van der Linden, Chapter 4; C Program-
ming: A Modern Approach by K.N. King, Chapter 13.

5.4 Module 4: Advanced Data Structures

• Topics:

>>>>>>> ff7cf03c05044109730d321b883fc211c14de0cb
– Linked lists and trees for system resource management.

– Circular buffers for data streaming.

– Hash tables with collision resolution (chaining, open addressing).

– Tries for efficient string processing.


– Bit arrays for compact state tracking.

– Memory-efficient data structures for system utilities.

<<<<<<< HEAD
## Module 5: Concurrency in System Programming
### • Topics:
– POSIX threads: thread creation (pthread_create), joining, and detachment.
– Synchronisation primitives: mutexes, semaphores, condition variables.
=======
• Reading: Data Structures and Algorithm Analysis in C by Mark Allen Weiss,

Chapters 3–5; Algorithms in C by Robert Sedgewick, Part 1.

5.5 Module 5: Concurrency in System Programming

• Topics:

– POSIX threads: thread creation (pthread_create), joining, and detachment.

– Synchronization primitives: mutexes, semaphores, condition variables.

>>>>>>> ff7cf03c05044109730d321b883fc211c14de0cb
– Priority inversion and priority inheritance mechanisms.

– Atomic operations using __atomic builtins for lock-free programming.
<<<<<<< HEAD
– Memory barriers for ensuring operation ordering.
– Spinlocks for low-latency synchronisation in high-performance systems.
– Real-time scheduling: rate-monotonic scheduling (RMS), earliest deadline first (EDF).
=======

4

– Memory barriers for ensuring operation ordering.

– Spinlocks for low-latency synchronization in high-performance systems.

– Real-time scheduling: rate-monotonic scheduling (RMS), earliest deadline first
(EDF).

>>>>>>> ff7cf03c05044109730d321b883fc211c14de0cb
– Deadlock detection and prevention strategies.

– Thread pools for efficient task management.

– Interrupt-driven concurrency for system events.

<<<<<<< HEAD
## Module 6: System Programming
### • Topics:
=======
• Reading: Programming with POSIX Threads by David R. Butenhof, Chapters 2–4;
Real-Time Concepts for Embedded Systems by Qing Li, Chapters 5–8; The Art of

Multiprocessor Programming by Maurice Herlihy, Chapter 7.

5.6 Module 6: System Programming

• Topics:

>>>>>>> ff7cf03c05044109730d321b883fc211c14de0cb
– File I/O operations (open, read, write, close).

– Process management: fork, exec, wait.

– Signal handling for asynchronous events (signal, sigaction).

– Inter-process communication: pipes, message queues, shared memory.

– Memory-mapped I/O for device interaction.

– System calls for resource management.

<<<<<<< HEAD
## Module 7: Compilers and Cross-Compilation
### • Topics:
– Compiler pipeline: preprocessing, lexical analysis, parsing, AST generation,
code generation, optimisation, and linking.
– Cross-compilation for platforms like ARM, RISC-V, and x86.
– Linker scripts for custom memory layouts (e.g., separating code and data sections).
– Code generation: instruction selection, register allocation, and peephole optimisation.
– optimisation flags: -O2, -Os, -march for architecture-specific tuning.
– Inline assembly for low-level operations (e.g., CPU-specific instructions).
– Link-time optimisation (LTO) for whole-program optimisation.
– Toolchain customisation: building GCC/G++ for specific targets.
– Debugging symbols and map file analysis for code size optimisation.
=======
• Reading: Advanced Programming in the UNIX Environment by W. Richard Stevens,
Chapters 8–10; Linux System Programming by Robert Love, Chapter 3.

5.7 Module 7: Compilers and Cross-Compilation

• Topics:

– Compiler pipeline: preprocessing, lexical analysis, parsing, AST generation,
code generation, optimization, and linking.

– Cross-compilation for platforms like ARM, RISC-V, and x86.

– Linker scripts for custom memory layouts (e.g., separating code and data sections).

– Code generation: instruction selection, register allocation, and peephole optimization.

– Optimization flags: -O2, -Os, -march for architecture-specific tuning.

5

– Inline assembly for low-level operations (e.g., CPU-specific instructions).

– Link-time optimization (LTO) for whole-program optimization.

– Toolchain customization: building GCC for specific targets.

– Debugging symbols and map file analysis for code size optimization.

>>>>>>> ff7cf03c05044109730d321b883fc211c14de0cb
– Compiler diagnostics and static analysis for error detection.

– Makefiles and more flags.

<<<<<<< HEAD
## Module 8: Performance optimisation
### • Topics:
– Code profiling with gprof and hardware counters.
– Loop optimisation: unrolling, vectorisation, and loop fusion.
– Cache optimisation: data locality and alignment.
– Function inlining and dead code elimination.
– Compiler-assisted optimisations: -ffast-math, -funroll-loops.
=======
• Reading: Linkers and Loaders by John R. Levine, Chapters 1–4; Compilers: Prin-
ciples, Techniques, and Tools by Aho et al., Chapters 1–3; GCC documentation.

5.8 Module 8: Performance Optimization

• Topics:

– Code profiling with gprof and hardware counters.

– Loop optimization: unrolling, vectorization, and loop fusion.

– Cache optimization: data locality and alignment.

– Function inlining and dead code elimination.

– Compiler-assisted optimizations: -ffast-math, -funroll-loops.

>>>>>>> ff7cf03c05044109730d321b883fc211c14de0cb
– Power-aware programming for battery-powered systems.

– Trade-offs between code size, speed, and resource usage.

<<<<<<< HEAD
## Module 9: Secure Coding
### • Topics:
=======
• Reading: Computer Systems: A Programmer’s Perspective by Bryant and O’Hallaron,
Chapter 5; Optimizing Compilers for Modern Architectures by Randy Allen, Chapter 2.

5.9 Module 9: Secure Coding

• Topics:

>>>>>>> ff7cf03c05044109730d321b883fc211c14de0cb
– Buffer overflow prevention using bounds checking.


– Input validation for robust system interfaces.

– Stack-smashing protection with canary values.

– Secure memory handling to avoid leaks and overwrites.

– Mitigating side-channel attacks (e.g., timing, cache attacks).

– Cryptographic primitives for secure data handling.

<<<<<<< HEAD
## Module 10: Debugging and Profiling
### • Topics:
=======
6

• Reading: Secure Coding in C and C++ by Robert C. Seacord, Chapters 2–3; The
Art of Software Security Assessment by Dowd et al., Chapter 5.

5.10 Module 10: Debugging and Profiling

• Topics:

>>>>>>> ff7cf03c05044109730d321b883fc211c14de0cb
– GDB for breakpoint-based debugging and backtracing.

– Valgrind for memory leak detection and profiling.

– Memory sanitizers for detecting undefined behavior.

– Hardware trace tools for runtime analysis.

– Profiling system calls and interrupt handlers.

– Debugging concurrent programs with thread-aware tools.

<<<<<<< HEAD
## Module 11: Advanced System Programming
### • Topics:
– Advanced file I/O: asynchronous I/O, memory-mapped files.
– Process synchronisation with semaphores and monitors.
=======
• Reading: The Art of Debugging with GDB (online); Valgrind User Manual (on-
line).

5.11 Module 11: Advanced System Programming

• Topics:

– Advanced file I/O: asynchronous I/O, memory-mapped files.

– Process synchronization with semaphores and monitors.

>>>>>>> ff7cf03c05044109730d321b883fc211c14de0cb
– Signal handling for robust system utilities.

– Shared memory for high-performance IPC.

– Device driver basics for peripheral interaction.
<<<<<<< HEAD
– System call optimisation for performance-critical applications.

## Module 12: Operating System Basics
### • Topics:
=======

– System call optimization for performance-critical applications.

• Reading: Advanced Programming in the UNIX Environment by W. Richard Stevens,
Chapters 10–12; Linux Device Drivers by Jonathan Corbet, Chapter 4.

5.12 Module 12: Operating System Basics

• Topics:

>>>>>>> ff7cf03c05044109730d321b883fc211c14de0cb
– OS Architecture:

∗ Monolithic vs. microkernel vs. hybrid kernel designs.

∗ Kernel vs. user space: privilege levels and system calls.
<<<<<<< HEAD
∗ OS components: process manager, memory manager, I/O subsystem, file system.
∗ Interrupt handling: software vs. hardware interrupts, interrupt descriptor tables (IDT).
=======

7

∗ OS components: process manager, memory manager, I/O subsystem, file
system.

∗ Interrupt handling: software vs. hardware interrupts, interrupt descriptor
tables (IDT).

>>>>>>> ff7cf03c05044109730d321b883fc211c14de0cb
– Process Management:

∗ Process creation (fork, clone) and termination (exit).

∗ Process control blocks (PCB): state, PID, registers, and memory context.

∗ Context switching: saving/restoring CPU state (e.g., x86 registers).

∗ Process states: running, ready, blocked, suspended.
<<<<<<< HEAD
∗ Thread models: kernel-level vs. user-level threads, POSIX threads implementation.
=======

∗ Thread models: kernel-level vs. user-level threads, POSIX threads implementation.

>>>>>>> ff7cf03c05044109730d321b883fc211c14de0cb
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
<<<<<<< HEAD
=======
8

>>>>>>> ff7cf03c05044109730d321b883fc211c14de0cb
∗ Virtual file system (VFS) layer for abstraction.

∗ File system caching and buffer management.

– Inter-Process Communication:

∗ Pipes: named and unnamed pipes for data streaming.

∗ Message queues for structured data exchange.

∗ Shared memory for high-speed IPC.
<<<<<<< HEAD
∗ Semaphores for synchronisation and mutual exclusion.
=======

∗ Semaphores for synchronization and mutual exclusion.

>>>>>>> ff7cf03c05044109730d321b883fc211c14de0cb
∗ Signals for event notification and handling.

– Device Management:
∗ Character vs. block devices: differences and C interfaces.
<<<<<<< HEAD
∗ Device drivers: structure, initialisation, and I/O handling.
=======

∗ Device drivers: structure, initialization, and I/O handling.

>>>>>>> ff7cf03c05044109730d321b883fc211c14de0cb
∗ Interrupt handling for device events.

∗ DMA for efficient data transfer.

– System Calls:

∗ System call interface: int 0x80, syscall instruction.

∗ Implementing system calls in C for process and memory management.

∗ Error handling: errno and error codes.

∗ System call tracing with strace.

– OS Security:

∗ Privilege separation and user permissions.
<<<<<<< HEAD
∗ Address space layout randomisation (ASLR).
=======

∗ Address space layout randomization (ASLR).

>>>>>>> ff7cf03c05044109730d321b883fc211c14de0cb
∗ System call filtering (e.g., seccomp).

∗ Kernel module security and loading mechanisms.

– OS Case Studies:

∗ Linux kernel: process scheduling, memory management, and VFS.

∗ xv6: a teaching OS for understanding Unix-like systems in C.

∗ RTOS concepts: task scheduling and interrupt handling.

-- Might need to remove Linux kernel and security stuff. Keep to OS levels. 

-- Will not spend too much time on this, as I will be mostly working in C++
