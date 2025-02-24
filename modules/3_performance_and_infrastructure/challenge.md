---
title: "Challenge: nanoGPT speedrunning world record"
nav_order: 15
parent: 3. Performance and Infrastructure
---

# Challenge: nanoGPT speedrunning world record

Twitter users have taken Karpathy's nanoGPT and optimized the hell out of it. This is called the nanoGPT speedrun.

Starting from a baseline training run of 45 minutes, they managed to get it down to **2.9 minutes** as of 2025-02-24. Today, your goal is to beat that.

The goal is to get 3.28 cross-entropy validation loss on the FineWeb dataset, running on a 8xH100 machine, in as little time as possible. Since 2.9 minutes is a very short time, there is also a new category for reaching 2.92 validation loss as fast as possible. latest record as of 2025-02-24 is [27.67 minutes](https://x.com/leloykun/status/1892793848163946799). We recommend starting with the original category as most optimizations seem to transfer well to the other category.

This competition is has helped multiple ideas be tested quickly. The biggest of which is probably the [Muon Optimizer](https://kellerjordan.github.io/posts/muon/)

The repo including the code of previous runs, as well as a leaderboard is located [here](https://github.com/KellerJordan/modded-nanogpt).
Note however that the leaderboard might not be up to date as there is a new record every few days. So keep updated on twitter. Some users to follow:

- [Keller Jordan](https://x.com/kellerjordan0) - Speedrunner and unofficial organizer of the speedrun

A 8xH100 machine costs about $20/hour, so a 3 minute run costs about $1. In the course, we will give you some compute budget. You can also run on colab with some different hyperparameters

