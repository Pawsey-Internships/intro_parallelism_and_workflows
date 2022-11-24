---
title: "Case Study - Bob"
weight: 3
---

*	Bob is working on a computer-vision project that is a machine learning project.
*	He is tasked with training a neural network on a large dataset.
*	Bob is working on Topaz as GPUs excel at performing the mathematical operations used in machine learning through **shared-memory** Parallelism.
*	Bob finds that his work is **Memory bound** as he can fit only a small number of images ('batch size') in the VRAM of one GPU on Topaz.
*	He solves this by modifying by using the Horovod Python package. It allows him to train his neural network over multiple GPUs, with each GPU learning on a partition of his dataset.
*	Bob's final workflow uses a combination of **shared-memory** (GPU) and **distributed-memory** (communication between GPU nodes) parallelism.
