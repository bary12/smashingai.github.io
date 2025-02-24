---
title: 3.8 Multi-Token Prediction
nav_order: 8
parent: 3. Performance and Infrastructure
---

# Multi-Token Prediction

Used by DeepSeek to dramatically speed up training for DeepSeek V3 (The starting point for DeepSeek R1).

The way I see this, the key idea here is to **maximize the throughput of tokens flowing through the network**. This is also, I believe, the reason why autoregressive decoders train faster than masked language models.
