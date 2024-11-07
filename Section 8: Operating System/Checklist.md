# GATE Operating System Preparation Checklist

## 1. **System Calls**
- [ ] **Definition and Types of System Calls**
  - [ ] Process control (e.g., fork, exec, wait, exit)
  - [ ] File management (e.g., open, close, read, write, delete)
  - [ ] Device management (e.g., ioctl, device drivers)
  - [ ] Information maintenance (e.g., getpid, time)
  - [ ] Communication (e.g., pipe, message queues, signals)

## 2. **Processes and Threads**
- [ ] **Process Management**
  - [ ] Definition of a process
  - [ ] Process states: new, ready, running, waiting, terminated
  - [ ] Process control block (PCB)
  - [ ] Context switching and process scheduling
- [ ] **Threads**
  - [ ] Definition and difference from processes
  - [ ] Thread control block (TCB)
  - [ ] Types of threads: user-level threads vs kernel-level threads
  - [ ] Multithreading models (many-to-one, one-to-one, many-to-many)

## 3. **Inter-Process Communication (IPC)**
- [ ] **Methods of IPC**
  - [ ] Shared memory
  - [ ] Message passing (synchronous vs asynchronous)
  - [ ] Pipes (named and unnamed)
  - [ ] Message queues, semaphores, and condition variables
- [ ] **Synchronization Mechanisms**
  - [ ] Mutexes, semaphores, and monitors
  - [ ] Critical section problem and its solutions
  - [ ] Producer-consumer problem
  - [ ] Reader-writer problem

## 4. **Concurrency and Synchronization**
- [ ] **Concurrency Concepts**
  - [ ] Definition of concurrency vs parallelism
  - [ ] Race conditions and solutions
  - [ ] Synchronization primitives (mutexes, semaphores, barriers, etc.)
- [ ] **Concurrency Control**
  - [ ] Deadlock prevention, avoidance, and detection
  - [ ] Lock-based synchronization and deadlock-free protocols
  - [ ] Condition variables and their role in synchronization
  - [ ] Thread-safe programming

## 5. **Deadlock**
- [ ] **Definition and Necessary Conditions for Deadlock**
  - [ ] Mutual exclusion, hold and wait, no preemption, circular wait
- [ ] **Deadlock Prevention**
  - [ ] Breaking one of the necessary conditions
- [ ] **Deadlock Avoidance**
  - [ ] Banker's Algorithm
  - [ ] Resource allocation graph (RAG)
- [ ] **Deadlock Detection and Recovery**
  - [ ] Wait-for graph
  - [ ] Deadlock detection algorithms
  - [ ] Methods for recovery (process termination, resource preemption)

## 6. **CPU and I/O Scheduling**
- [ ] **CPU Scheduling Algorithms**
  - [ ] First Come First Serve (FCFS)
  - [ ] Shortest Job Next (SJN) / Shortest Job First (SJF)
  - [ ] Round Robin (RR)
  - [ ] Priority Scheduling (preemptive and non-preemptive)
  - [ ] Multilevel Queue Scheduling
- [ ] **I/O Scheduling Algorithms**
  - [ ] FCFS, SSTF, SCAN, C-SCAN, LOOK, C-LOOK
  - [ ] Disk scheduling policies
  - [ ] Efficiency and optimization of I/O scheduling

## 7. **Memory Management**
- [ ] **Memory Allocation Techniques**
  - [ ] Contiguous memory allocation (fixed partitioning, dynamic partitioning)
  - [ ] Paging and page tables
  - [ ] Segmentation and segmentation with paging
- [ ] **Virtual Memory**
  - [ ] Virtual memory concepts and benefits
  - [ ] Demand paging and page fault handling
  - [ ] Page replacement algorithms (FIFO, LRU, Optimal, Clock)
  - [ ] Thrashing and its prevention
- [ ] **Page Replacement Algorithms**
  - [ ] Optimal, Least Recently Used (LRU), First-In-First-Out (FIFO), Clock
  - [ ] Belady's anomaly and its implications

## 8. **File Systems**
- [ ] **File System Concepts**
  - [ ] File attributes, file operations, and file types
  - [ ] File access methods (sequential, random, indexed)
  - [ ] Directory structure: single-level, two-level, tree-structured
- [ ] **File Allocation Methods**
  - [ ] Contiguous allocation
  - [ ] Linked allocation (singly linked, doubly linked)
  - [ ] Indexed allocation
- [ ] **File System Implementation**
  - [ ] File allocation table (FAT), Inode structure
  - [ ] Block allocation strategies
  - [ ] Journaling file systems and recovery
- [ ] **Disk Management**
  - [ ] Disk scheduling algorithms (FCFS, SSTF, SCAN, C-SCAN)
  - [ ] Disk formatting, partitioning, and management
  - [ ] RAID levels (RAID 0, 1, 5, etc.)
- [ ] **File System Security and Protection**
  - [ ] Access control lists (ACLs) and file permissions
  - [ ] Cryptography in file systems
  - [ ] File system integrity and reliability

