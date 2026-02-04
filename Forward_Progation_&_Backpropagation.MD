## Forward Propagation
It is a process that passes data from an input layer to an output layer via hidden layers.

## Backpropagation
An algorithm that backpropagates errors from output nodes to input nodes

1. The algorithm steps backward to obtain the derivatives of the hidden layers
2. It calculates the derivative of the cost function with respect to the weights and biases of the previous layer
3. It repeats this process until each derivative is obtained

## Automatic differentiation

A process that allows computers to optimally perform all forward propagation and backpropagation operations

## Minibatches
 Small random selected samples of training data that change with each parameteer update.

 ** Stochastic gradient descent (SGD)**
   The minibatch style of optimization in which randomly selected subsamples converge in a fast but noisy fashion.