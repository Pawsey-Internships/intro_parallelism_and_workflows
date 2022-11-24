---
title: "Concurrency vs Parallelism"
weight:	5
---

**Concurrency** is progressing on more than one task over a period of time by switching between tasks, e.g.:​

*	Checking your phone while studying. ​
*	Taking turns in a game of chess.​
*	One CPU core switching between instructions from different programs​

> No task occurs simultaneously.​

​If the switching occurs fast enough, each process will appear to be progressing simultaneously. As CPUs can process data at a much faster rate than human perception, we can multi-task on a PC with a single CPU core.

**Parallelism** splits tasks into smaller subtasks that progress independently:​

*	Write the introduction for your thesis while your numerical simulations are running.​
*	Heats in a chess tournament ​
*	Two CPUs searching through two halves of one data set to find a maximum value.

​
Unlike Concurrency:

*	Parallelism can reduce the time it tasks to complete a task.​
*	However, parallel processes often need to 'come together to share information.

	- 	Who will proceed to the next heat in the tournament?​
	-	Which CPU has found the actual maximum?
