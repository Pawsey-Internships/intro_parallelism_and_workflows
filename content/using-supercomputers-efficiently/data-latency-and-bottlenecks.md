---
title: "Data Latency and Bottleknecks"
weight: 1
---

Data Latency is the time taken to transfer data to a processor (a core in a CPU or GPU).

|        Data Location        | Average Latency | Normalised Human Time |
| --------------------------- | --------------- | --------------------- |
|    3 GHz CPU Clock Cycle    |     0.3. ns     |          1 s          |
|          CPU Cache          |    0.9-28 ns    |      2 s - 1 min      |
|             RAM             |    70-100 ns    |      3.5-5.5 min      |
|   Solid State Disk (NVME)   |   7-150 µs  	|    2 hrs to 2 days    |
|       Hard Disk Drive       |   1-10 µs	|  11 days to 4 months  |
| Another Supercomputing Node |   100-1000 ms   |       3-30 years      |

Depending on the type of work you are doing, the amount of data you are working and the type of system you are working on, your work will be:

**I/O Bound:** Progress depends on the speed of input/output operations (e.g. transferring data between the RAM and a disk drive). 

**Memory Bound:** Compute time depends on the amount of Memory (RAM or VRAM) available to hold working data. 

**Procesor Bound:** Progress is limited by the speed of processors in the CPU or GPU.
