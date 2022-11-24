---
title: "Parallel APIs and Frameworks."
weight:	7
---

Some languages support parallelism 'out of the box':​

*	Julia (shared-memory and distributed)​
*	Coarray Fortran (shared-memory  and distributed) ​
*	C# (shared-memory)​
Java (shared-memory)​

…​

There are also many parallel APIs/frameworks:​

*	OpenCL (shared-memory)​
*	CUDA (shared-memory)​
*	OpenMP (shared-memory)​
*	Message Passing Interface (MPI) (distributed)​

…

If you're not explicitly writing parallel code, you will likely use programs or software libraries built on one of the above APIs/frameworks to take advantage of Parallelism:

*	Numpy
*	Intel MKL
*	Tensorflow
*	...

What is best depends on the problem at hand and the hardware available.​ 

