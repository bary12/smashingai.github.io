---
title: 2.4 Why transformers?
nav_order: 4
parent: 2. Transformers
---

# Why transformers?

Here I will try to explain my take on why autoregressive transformers eventually won out over other architectures, for language modeling.

The key reasons are: efficient parallel computation, and the ability to handle long-range dependencies, which is enabled by the O(n^2) complexity.

There are more reasons related to data rather than architecture, we will cover those later.
