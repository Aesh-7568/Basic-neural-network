# Basic-neural-network
Assignment 1

1.What is neural network neuron?

Neural network is a set of neurons organized in layers. Each neuron is a mathematical operation that takes it's input, multiplies it by it's weights and then passes the sum through the activation function to the other neurons.



2.What is the use of learning rate?

 The learning rate is a configurable hyperparameter used in the training of neural networks that has a small positive value, often in the range between 0.0 and 1.0. The learning rate controls how quickly the model is adapted to the problem.

3.How are weights initialised?

 Weight initialization involves using small random numbers, although over the last  decade, more specific heuristics have been developed that use information, such as the type of activation function that is being used and the number of inputs to the node.
These more tailored heuristics can result in more effective training of neural network models using the stochastic gradient descent optimization algorithm.

4.What is loss in a neural network?

The difference between the actual and predicted value is termed as loss.In the context of an optimization algorithm, the function used to evaluate a candidate solution (i.e. a set of weights) is referred to as the objective function.
We may seek to maximize or minimize the objective function, meaning that we are searching for a candidate solution that has the highest or lowest score respectively.
Typically, with neural networks, we seek to minimize the error. As such, the objective function is often referred to as a cost function or a loss function and the value calculated by the loss function is referred to as simply “loss.”
 
5.What is the chain rule in gradient flow?

Backpropagation is an algorithm to calculate gradients.The Chain Rule is a method for finding complex derivatives.
We are trying to find a partial derivative of E w.r.t Wih. So the strategy is to find the partial derivative of E w.r.t o multiplied by partial derivative of o w.r.t μ2 and so on moving from right to left. This process is called the chain rule.
 

Here X = Input
bih=bias
w= weights
E= error (calculated using mean squared error here)
 
 
 
 
 



