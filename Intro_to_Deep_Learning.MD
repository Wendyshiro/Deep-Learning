## Intro to Deep Learning

## Deep Learning
It is a complex and powerful subset of ML and foundational for modern AI models
# DL models
Good for handling big data and shines when fed big datasets

## Neural Networks
It is an ML algorithm that mimics the structure of the brain, linking many small functions together to model complex non linear relationships

Neural networks operate in layers:
 1. Input layer
 2. Hidden layer
 3. Output layer

 ![alt text](image.png)

Deep learning refers to particular to neural networks with multiple hidden layers

Neural nets mimic brain operations:
 1. A neuron "fires" (i.e activates) in response to how "excited" it gets
 2. "Neurons that fire together, wire together

## Activation Function
This are instructions for how a neuron fires in response to a combination of its input, weight and bias

The weight, w and the bias b are part of a linear regression within each neuron.

The linear regression equation, h=wx + b is inserted into the activation function f(h)

There are several activation functions:
 1. Softmax - is commonly used for multi class classification problems using probability to "soften" the output of a logistic regression
 2. Tanh - the tanh activation has historically performed better than the sigmoid activation on similar problem sets.
   ** e^x - e^-x/ e^x + e^-x**
 3. Sigmoid- the exact function used in logistic regression. Popular choice for activation but computationally expensive than ReLUs.

 Activation functions are passed the results of wx + b and generate non linerarity.


## Rectified Linear Unit (ReLU)
An activation function that outputs 0 when h < 0 and outputs h when h > 0