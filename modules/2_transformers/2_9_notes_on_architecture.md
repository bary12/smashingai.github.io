---
title: 2.9 Notes on Architecture
nav_order: 9
parent: 2. Transformers
---

# Notes on Architecture

When getting into Deep Learning, a lot of people focus on the model architecture, and how to improve it.

While there are many ways in which modifying the architecture can improve performance, these improvements are relatively rare and hard to find.

The reason for this is that the architecture itself "doesn't do much". Since we train the models as one big network, different parts of the models learn to interact with one another. It's easy to say "If I make this change, the model will understand X better". But in reality it usually already found a way to do this or to work around the need to do it.

The things that **do** matter about architecture are:

1. The expressiveness of the architecture. Can the model actually represent the function we are trying to approximate?
2. The expressiveness / parameters ratio. Can we decrease the number of parameters with minimal loss in expressiveness?

Everything else, the model will figure out by itself.
