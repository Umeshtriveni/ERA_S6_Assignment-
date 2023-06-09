# PART-1 ERA_S6_Assignment- Calculation for back-propogation

# Neural Network Architecture`

![image](https://github.com/Umeshtriveni/ERA_S6_Assignment-/assets/42119280/68f8b261-7ed4-42c8-b793-1f0e1dbbc1b1)

# Neural Network Architecture

This is a simple neural network architecture implemented for both forward propagation and backward propagation.

## Forward Propagation

The forward propagation process consists of the following steps:

1. Input Layer: The first layer of the network receives the input data.
2. Hidden Layers: One or more layers between the input and output layers. Each hidden layer contains multiple neurons that perform computations using weighted inputs and activation functions.
3. Output Layer: The final layer produces the output prediction.

In forward propagation, each neuron in a hidden layer computes a weighted sum of its inputs and passes it through an activation function to produce an output value. The output of each neuron in a hidden layer serves as the input for the neurons in the next layer. Finally, the output layer generates the final prediction based on the outputs from the last hidden layer.

## Backward Propagation (Backpropagation)

The backward propagation process involves the following steps:

1. Loss Function: A function that measures the difference between the predicted output and the true output.
2. Gradient Calculation: Calculate the gradient of the loss function with respect to the weights and biases of the neural network.
3. Weight and Bias Updates: Update the weights and biases of the network using an optimization algorithm, such as gradient descent.

During backpropagation, the loss function quantifies the error between the predicted output and the true output. The gradient is calculated by propagating the error backward through the network, using the chain rule to compute the derivative of the loss function with respect to each weight and bias. The weights and biases are updated using the gradient information and an optimization algorithm, such as gradient descent, to minimize the loss function.

It's important to note that the specific architecture and details of the neural network can vary depending on the problem at hand. The above description provides a general overview of the forward and backward propagation processes.

# Calculatation Sheet:
![image](https://github.com/Umeshtriveni/ERA_S6_Assignment-/assets/42119280/0179eada-8a57-4db7-8699-e9a58f3b8eba)

# Error graph for learning rate from [0.1, 0.2, 0.5, 0.8, 1.0, 2.0] 
## learning rate = 0.1
![image](https://github.com/Umeshtriveni/ERA_S6_Assignment-/assets/42119280/50da4be1-aeba-4c62-bc42-bb4532494d65)

## learning rate = 0.2
![image](https://github.com/Umeshtriveni/ERA_S6_Assignment-/assets/42119280/f19d1e2c-fed2-47d2-93b8-9722f66a7843)

## learning rate = 0.5
![image](https://github.com/Umeshtriveni/ERA_S6_Assignment-/assets/42119280/309d4bff-71ec-42f4-bcef-8e8a630e648c)

## learning rate = 0.8
![image](https://github.com/Umeshtriveni/ERA_S6_Assignment-/assets/42119280/8d3d9239-7aad-49b6-914c-6a8f149943b8)

## learning rate = 1.0
![image](https://github.com/Umeshtriveni/ERA_S6_Assignment-/assets/42119280/8f96cf5f-2bfa-43db-8e3d-ccb8321cf0b3)

## learning rate = 2.0
![image](https://github.com/Umeshtriveni/ERA_S6_Assignment-/assets/42119280/c663f817-0207-40c7-96fc-1c60335dce96)










