---
title: "A few useful terms."
weight: 6
---

**Thread:**	A subtask in a parallel program or pipeline (different from a CPU thread).​

**Shared-Memory Parallelism:** A parallel process where threads share the same Memory, which includes variables or data in RAM for CPUs or VRAM for GPUs.

**Distributed Parallelism:** A parallel process where threads have their own Memory. They do not share the same variables or data. 

**Synchronisation:**	Threads come together to access objects or data that other threads have operated on​. In a program, often, these are shared variables. (e.g. a running total)​.

**Race condition​:**	Unexpected results or behaviour due to a fault in the 'parallel logic of a program. For example, a thread makes a decision based on a shared variable that all threads have not updated. Race conditions arise due to a lack of, or improper, synchronisation.​

**Parallel slowdown​:**	Not all parallelisation results in speedup.​ There is an overhead in both the initialisation of threads and, often, communication between them.​ As the number of threads increases, more time is generally spent on inter-thread communication.

Parallel computational tasks can be broady classed as either *fine-grained*, *coarse-grained* or *embarrassing*: ​

​**Fine-grained:** 	Threads frequently communicate (many times a second)​.

**Coarse-Grained:**	Threads infrequently communicate (a few times per second)​.

**Embarrassing:**	Threads communicate rarely or not at all.

​In an ideal world, all of our tasks would be embarrassing…but this is generally not the case.
