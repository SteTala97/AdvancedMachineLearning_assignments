# Directives for this assignment

The task of the assignment #3 is the design of a CNN architecture and its training.

Input dataset: MNIST digits (input size 28x28x1, number of classes: 10).
The dataset is not distributed since can be easily downloaded directly from Keras.

The CNN has to be designed with the aim of reaching the maximum possible accuracy on the test set, with the hard constraint of a maximum of 6K learnable parameters. Refer to the code developed in today's class as a skeleton on which to build your solution.

The report must contain:
- a description of the designed architecture
- the parameters count for each layer
- the hyper-parameters used for training (batch size, learning rate, optimizer, number of epochs, etc)
- a plot of the training and validation loss/accuracy 
- classification performance on training, validation (if used) and test set
