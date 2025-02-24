---
title: 3. Performance and Infrastructure
nav_order: 13
---

# Performance and Infrastructure

As models get larger, the performance and infrastructure requirements also increase.

This section will cover training infrastructure, as well as all kinds of optimization techniques to improve performance of both training and inference.

Most of the techniques are independent of each other, so you can pick and choose which ones you want to learn about.
Some are more software-y (e.g. CUDA kernels), some are more hardware-y (e.g. NVLink), and some are algorithmic (e.g. Mixture of Experts).
But good optimizations usually touch all three. Knowing all three intimately is a superpower when coming up with new optimizations.
ZeRO and FlashAttention are good examples of this.
