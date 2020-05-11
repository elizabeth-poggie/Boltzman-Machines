# Boltzmann Machines

## Objective

Boltzmann machines are a specific type of parallel distributed processing model designed for unsupervised learning. The machine is split up into hidden and visible units where the goal of the hidden units is to capture higher-order weak constraints of the visible units that the world provides. The machine has successfully learnt once the output is indistinguishable from it’s input in its absence.

The purpose of this exercise is three-fold:
1) To get familiar with a canonical, yet slightly esoteric, neural network model, so that I don’t fall prey to the idea that neural networks are all deep convolutional networks.
2) To think about the actual learning algorithm for a neural network and how to implement that in code in an elegant manner.
3) To engage in some more in depth thought about unsupervised learning and the relationship between unsupervised learning and brains.

## Issues

The model does not effectively reduce loss and so it does not “learn” efficiently. If I were to redo the model, I would put further effort into understanding how vamp up the equations, so the model learns correctly. 
