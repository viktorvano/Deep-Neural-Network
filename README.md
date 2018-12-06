# Deep-Neural-Network

This Neural Network has vector topology, so it can be a deep neural network or with a single hidden layer.
This project is just a preparation for my master's degree thesis.
The goal of my master's degree thesis is to make a robot with a beural network.
It is going to run on M3 ARM MCU.
The drivers for this MCU are in C language, so I had to write the file managing part of code in C.

This Neural Network can be easily confugred in "Topology.txt", "TrainingData.txt" and "Weights.txt".
If there are no weights, or if the topology does not match with a number of weights, the Neural Network retrains itself again.
