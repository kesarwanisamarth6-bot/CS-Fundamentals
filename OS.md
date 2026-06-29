# Operating System (OS)

## Definition

An Operating System (OS) is system software that acts as an interface between the user and computer hardware.

---

## Goals of OS

- **Throughput:** Maximum tasks completed per unit time.
- **Convenience:** Makes the system easy to use.

---

## Functions of OS

### Resource Management
Manages and allocates:
- CPU
- Memory (RAM)
- Storage Devices
- I/O Devices

### Process Management
A process is a program in execution.

Responsibilities:
- Create and terminate processes
- Schedule CPU execution
- Manage multiple processes

### Memory Management
- Allocates and deallocates RAM
- Tracks memory usage
- Prevents memory conflicts between processes

### Storage Management
- File creation and deletion
- Directory management
- Storage allocation
- Data retrieval

### Security & Privacy
- Authentication and access control
- Process isolation
- Prevents unauthorized memory access

---

## System Calls

System calls allow applications to request services from the operating system.

Examples:
- File operations
- Process creation
- Memory allocation
- Device access

---

## User Interaction with OS

Users interact with the operating system through applications.

```text
User
  ↓
Application
  ↓
System Call
  ↓
Operating System
  ↓
Hardware
```

---

# Batch Operating System

## Type of Operating System

Batch Operating System is one of the earliest types of Operating Systems.

It executes multiple jobs by grouping them into batches and processing them automatically without user interaction.

---

## What is a Job?

A **Job** is a program along with the data required for its execution.

Examples:
- Printing a document
- Payroll processing
- Result generation

---

## Why Was It Introduced?

In early computer systems:

- Jobs were prepared using Punch Cards or Paper Tapes.
- Jobs were submitted to an operator.
- The operator grouped similar jobs into batches.

---

## Working

1. User prepares a job.
2. Job is submitted to the operator.
3. Operator creates batches.
4. OS executes jobs one by one.
5. Output is generated after execution.

```text
User → Operator → Batch → OS → CPU → Output
```

---

## Disk and I/O Operations

A **Disk** is a secondary storage device used for permanent storage.

Examples:
- HDD (Hard Disk Drive)
- SSD (Solid State Drive)

A job may require I/O operations such as reading or writing data from a disk.

```text
CPU → Requests Data
Disk → Fetches Data
CPU → Idle
```

This leads to:
- Poor CPU Utilization
- Lower Throughput

---

## Characteristics

- No user interaction during execution
- Jobs are executed sequentially
- Similar jobs are grouped together
- Output is generated after completion

---

## Advantages vs Disadvantages

| Advantages | Disadvantages |
|------------|---------------|
| Improved throughput | Long waiting time |
| Automatic job execution | No immediate response |
| Reduced manual effort | Difficult error handling |
| Better resource utilization | CPU may remain idle during I/O operations |