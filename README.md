# BP-Neural-Network-Matlab

## Description

BP neural network in Matlab. Edition 1.1.

## Tutorial

The program is used to generate and train a BP neural network with the primary application of Matlab. Both sigmoid and tanh can be chosen as the activation function of the hidden layer, and Linear function as the activation function of the output layer.

Before running the program, you should add all the files into Matlab path. You'd better run the program in BPtrain.m unless you want to improve my code.

You can change the training set, activation function of the hidden layer, number of neurons in hidden layer, learning rate, repeat times and check interval in BPtrain.m simply by changing the default values.

If your input size and output size are both 1, you can run film.m to generate a film showing the training process. An example can be seen in and gif180906.gif. Also, you can pause BPtrain.m at any time you want and use the code below to check your training result.

```matlab
plot(x, y)
```

NOTE: if the code above does not work, continue BP.train for a while and pause again. It is probably beacuse the script stops at an other workspace.

Enjoy your time with BPNN and Matlab! Suggestions and adjustments(as well as STARs) are welcomed.

Created 10/9/2018 by Bill in Beijing
