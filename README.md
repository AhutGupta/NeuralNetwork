# NeuralNetwork
A Neural Network to recognize handwritten digits(0-9). Works on a MNIST dataset(included).  
The data is divided into 3 sets: Training, Validation and Testing.  
It uses a single hidden layer, but the number of hidden nodes is configurable.
Number of output classes: 10 (1 for each digit)

### Output:
1. Training time
2. Accuracies on Training, Validation and Testing sets.

### Usage:
1. Number of Hidden Layers:  
   Set the number of hidden nodes in the variable `n_hidden`
2. Regularization:   
   Set the regularization parameter (0-1) in the variable `lambdaval`
