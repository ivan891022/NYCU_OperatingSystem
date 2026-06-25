# NYCU Operating System

This repository contains course materials, exam scopes, and past exam resources for the **Operating System** course at NYCU.

> Course: Operating System  
> Semester: 114 Academic Year, Second Semester  
> Instructor: Shyan-Ming Yuan  
> Purpose: Course review, exam preparation, and personal study organization.

---

## Course Overview

This course introduces the fundamental concepts and design principles of operating systems, including process management, memory management, file systems, multiprocessor systems, multicomputer systems, distributed systems, inter-process communication, distributed file systems, and distributed synchronization.

The course emphasizes both traditional operating system principles and distributed operating system concepts.

---

## Grading Policy

The course contains three regular written exams.

| Item | Weight |
|---|---:|
| Highest exam score | 50% |
| Middle exam score | 35% |
| Lowest exam score | 15% |

---

## Repository Structure

```text
.
├── slides/
│   ├── 01_OS_Part1.pdf
│   ├── 02_OS_Part2.pdf
│   ├── 03_OS_Part3.pdf
│   ├── 04_MultiProcessors.pdf
│   ├── 05_MultiComputers.pdf
│   ├── 06_DistributedSystems.pdf
│   ├── 07_MessagePassing.pdf
│   ├── 08_DistributedFileSystems.pdf
│   └── 09_Synchronization.pdf
├── exams/
│   └── 2026/
│       ├── 2026_first_exam.pdf
│       ├── 2026_second_exam.pdf
│       └── 2026_third_exam.pdf
└── past-exams/
    ├── 2023考古題/
    ├── 2024考古題/
    └── 2025考古題/

```

---

## Exam Scope

### First Regular Written Exam

**Date:** 2026-03-25  
**My Score:** 100 / 101  
**Class Average:** 78.5 / 101  

**Suggested scope:**

- OS introduction
- OS history
- Mechanism vs. policy
- Booting an operating system
- Kernel mode and user mode
- Mode switch and system calls
- Timer interrupt and context switch
- I/O devices
- Process and thread concepts
- CPU scheduling
  - FCFS
  - SJF
  - SRTF
  - Round Robin
  - Priority scheduling
  - Multilevel queue
  - Multilevel feedback queue
- Memory management
- Logical and physical address space
- Swapping
- Virtual memory
- Demand paging
- Page replacement
  - FIFO
  - Optimal
  - LRU
  - Clock algorithm
- File system basics

**Related materials:**

```text
slides/01_OS_Part1.pdf
slides/02_OS_Part2.pdf
slides/03_OS_Part3.pdf
exams/2026/2026_first_exam.pdf
```

---

### Second Regular Written Exam

**Date:** 2026-05-06  
**My Score:** 88.6 / 104  
**Class Average:** 77.1 / 104  

**Suggested scope:**

- Multiprocessor systems
  - UMA
  - NUMA
  - Cache coherence
  - Crossbar switch
  - Omega network
  - SMP
  - Master-slave multiprocessors
- Multicomputer systems
  - Interconnection networks
  - Direct and indirect networks
  - Mesh
  - Torus
  - Hypercube
  - Multistage interconnection networks
  - Blocking and non-blocking networks
- Distributed systems
  - Transparency
  - Scalability
  - Fault tolerance
  - Replication
  - Middleware
  - Network operating systems
  - Distributed operating systems
- Inter-process communication
  - Message passing
  - Direct and indirect communication
  - Blocking and non-blocking primitives
  - Persistent and transient messaging
  - Message buffering
  - Client-server model
  - RPC
  - Socket concepts

**Related materials:**

```text
slides/04_MultiProcessors.pdf
slides/05_MultiComputers.pdf
slides/06_DistributedSystems.pdf
slides/07_MessagePassing.pdf
exams/2026/2026_second_exam.pdf
```

---

### Third Regular Written Exam

**Date:** 2026-06-10  
**My Score:** 95 / 119  
**Class Average:** 82.9 / 119 

**Suggested scope:**

- Distributed file systems
  - File system concepts
  - DFS requirements
  - Access transparency
  - Location transparency
  - Naming schemes
  - Remote service model
  - Data caching model
  - Cache location policies
  - Cache update policies
  - Cache validation policies
  - File replication
  - Replication transparency
  - Multicopy update policies
- Distributed synchronization
  - Clock synchronization
  - Cristian's algorithm
  - Berkeley algorithm
  - NTP
  - Event ordering
  - Happened-before relation
  - Lamport logical clock
  - Global logical clock
  - Vector clock
  - Distributed mutual exclusion
  - Leader election
  - Distributed deadlock detection

**Related materials:**

```text
slides/08_DistributedFileSystems.pdf
slides/09_Synchronization.pdf
exams/2026/2026_third_exam.pdf
```




