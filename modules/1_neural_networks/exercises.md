---
title: Exercises
nav_order: 7
parent: 1. Neural Networks
---

# Exercise #1: Autoencoder on MNIST

Train an autoencoder on MNIST dataset, in pytorch.  

# Exercise #2: Adversarial attack on our autoencoder

your goal is to find an image that looks like a 7 but causes the autoencoder to output a 9.

<!-- Need to verify this is actually easy enough to do -->

the loss function will be a combination of the reconstruction loss from an image of a 9, and similarity of the input to an image of a 7.
