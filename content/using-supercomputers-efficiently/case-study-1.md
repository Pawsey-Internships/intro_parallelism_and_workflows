---
title: "Case Study - Alice"
weight: 2
---

*	Alice is working on an astrophysics project that explores how light (photons) are scattered in stellar atmospheres.
*	She is using Monte Carlo Simulation, which simulates the path of 10000s of individual photons based on randomised starting conditions and events.
*	As the path of each simulated independently from the other, this part of her work is **embarrassingly parallel**.
*	She uses MPI on Setonix to simulate one photon per CPU core.
*	As each of Alice's simulations completes quickly, saving the result of each simulation would result in her work being **Memory bound**.
* 	She solves this by saving her work in 'chunks' of multiple simulation results.

