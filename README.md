# Contents List

## Module 1: Review of C Fundamentals
### • Topics:
– Data types (int, char, float) and their memory representations.
– Advanced pointer usage: pointer arithmetic, const, and volatile qualifiers.
– Bit manipulation for system flags and registers.
– Structures, unions, and enums for data organisation.
– Memory layout: stack, heap, and static storage.
– Endianness and its impact on cross-platform code.

## Module 2: Memory Management
### • Topics:
– Dynamic memory allocation (malloc, calloc, realloc, free).
– Memory leaks, dangling pointers, and mitigation strategies.
– Custom memory allocators for system software.
– Memory alignment for performance optimisation.
– Stack vs. heap trade-offs in system programming.
– Memory pools for predictable allocation in constrained environments.
– Heap and Stack algorithms and management.

## Module 3: Pointers and Function Pointers
### • Topics:
– Pointer arithmetic for array and buffer manipulation.
– Function pointers for callback mechanisms and dynamic dispatch.
– Void pointers for generic programming.
– Pointer-to-pointer for multi-level data structures.
– const and volatile for safe memory access.
– Function pointer tables for system event handling.

## Module 4: Advanced Data Structures
### • Topics:
– Linked lists and trees for system resource management.
– Circular buffers for data streaming.
– Hash tables with collision resolution (chaining, open addressing).
– Tries for efficient string processing.
– Bit arrays for compact state tracking.
– Memory-efficient data structures for system utilities.

## Module 5: Concurrency in System Programming
### • Topics:
– POSIX threads: thread creation (pthread_create), joining, and detachment.
– Synchronisation primitives: mutexes, semaphores, condition variables.
– Priority inversion and priority inheritance mechanisms.
– Atomic operations using __atomic builtins for lock-free programming.
– Memory barriers for ensuring operation ordering.
– Spinlocks for low-latency synchronisation in high-performance systems.
– Real-time scheduling: rate-monotonic scheduling (RMS), earliest deadline first (EDF).
– Deadlock detection and prevention strategies.
– Thread pools for efficient task management.
– Interrupt-driven concurrency for system events.

## Module 6: System Programming
### • Topics:
– File I/O operations (open, read, write, close).
– Process management: fork, exec, wait.
– Signal handling for asynchronous events (signal, sigaction).
– Inter-process communication: pipes, message queues, shared memory.
– Memory-mapped I/O for device interaction.
– System calls for resource management.

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
– Compiler diagnostics and static analysis for error detection.
– Makefiles and more flags.

## Module 8: Performance optimisation
### • Topics:
– Code profiling with gprof and hardware counters.
– Loop optimisation: unrolling, vectorisation, and loop fusion.
– Cache optimisation: data locality and alignment.
– Function inlining and dead code elimination.
– Compiler-assisted optimisations: -ffast-math, -funroll-loops.
– Power-aware programming for battery-powered systems.
– Trade-offs between code size, speed, and resource usage.

## Module 9: Secure Coding
### • Topics:
– Buffer overflow prevention using bounds checking.
– Input validation for robust system interfaces.
– Stack-smashing protection with canary values.
– Secure memory handling to avoid leaks and overwrites.
– Mitigating side-channel attacks (e.g., timing, cache attacks).
– Cryptographic primitives for secure data handling.

## Module 10: Debugging and Profiling
### • Topics:
– GDB for breakpoint-based debugging and backtracing.
– Valgrind for memory leak detection and profiling.
– Memory sanitizers for detecting undefined behavior.
– Hardware trace tools for runtime analysis.
– Profiling system calls and interrupt handlers.
– Debugging concurrent programs with thread-aware tools.

## Module 11: Advanced System Programming
### • Topics:
– Advanced file I/O: asynchronous I/O, memory-mapped files.
– Process synchronisation with semaphores and monitors.
– Signal handling for robust system utilities.
– Shared memory for high-performance IPC.
– Device driver basics for peripheral interaction.
– System call optimisation for performance-critical applications.

## Module 12: Operating System Basics
### • Topics:
– OS Architecture:
∗ Monolithic vs. microkernel vs. hybrid kernel designs.
∗ Kernel vs. user space: privilege levels and system calls.
∗ OS components: process manager, memory manager, I/O subsystem, file system.
∗ Interrupt handling: software vs. hardware interrupts, interrupt descriptor tables (IDT).
– Process Management:
∗ Process creation (fork, clone) and termination (exit).
∗ Process control blocks (PCB): state, PID, registers, and memory context.
∗ Context switching: saving/restoring CPU state (e.g., x86 registers).
∗ Process states: running, ready, blocked, suspended.
∗ Thread models: kernel-level vs. user-level threads, POSIX threads implementation.
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
∗ Virtual file system (VFS) layer for abstraction.
∗ File system caching and buffer management.
– Inter-Process Communication:
∗ Pipes: named and unnamed pipes for data streaming.
∗ Message queues for structured data exchange.
∗ Shared memory for high-speed IPC.
∗ Semaphores for synchronisation and mutual exclusion.
∗ Signals for event notification and handling.
– Device Management:
∗ Character vs. block devices: differences and C interfaces.
∗ Device drivers: structure, initialisation, and I/O handling.
∗ Interrupt handling for device events.
∗ DMA for efficient data transfer.
– System Calls:
∗ System call interface: int 0x80, syscall instruction.
∗ Implementing system calls in C for process and memory management.
∗ Error handling: errno and error codes.
∗ System call tracing with strace.
– OS Security:
∗ Privilege separation and user permissions.
∗ Address space layout randomisation (ASLR).
∗ System call filtering (e.g., seccomp).
∗ Kernel module security and loading mechanisms.
– OS Case Studies:
∗ Linux kernel: process scheduling, memory management, and VFS.
∗ xv6: a teaching OS for understanding Unix-like systems in C.
∗ RTOS concepts: task scheduling and interrupt handling.


-- Might need to remove Linux kernel and security stuff. Keep to OS levels. 
-- Will not spend too much time on this, as I will be mostly working in C++