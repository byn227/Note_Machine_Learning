# Chapter 3: Neural Networks and Deep Learning

This chapter introduces neural networks, softmax activation, optimization algorithms, and convolutional neural networks (CNNs). Visual aids are included to help illustrate each concept.

## Neural Network
A neural network is a computational model inspired by the human brain, consisting of interconnected layers of nodes (neurons). Each neuron processes input data and passes the result to the next layer. Neural networks are used for tasks such as classification, regression, and pattern recognition.

![Neural Network Diagram](assets/image.png)
![Neural Network Layers](assets/image-1.png)
![Neural Network Example](assets/image-2.png)
![Neural Network Training](assets/image-3.png)
![Neural Network Activation](assets/image-4.png)
![Neural Network Output](assets/image-5.png)
![Neural Network Connections](assets/image-6.png)
![alt text](assets/image-33.png)
![Neural Network Visualization](assets/image-7.png)
![Neural Network Structure](assets/image-8.png)
![Neural Network Flow](assets/image-9.png)
![Neural Network Backpropagation](assets/image-10.png)
![Neural Network Weights](assets/image-11.png)
![Neural Network Bias](assets/image-12.png)

(./lab/Neuron and Layers.ipynb)

Mini Neuron network for two type library python:
(./lab/Coffee_TF.ipynb)
(./lab/Coffee_Numpy.ipynb)

## Lab
(./lab/Handwritten_Recognition.ipynb)

## Relu Activation
(./lab/Relu.ipynb)

## Softmax
The softmax function is used in the output layer of neural networks for multi-class classification. It converts raw scores (logits) into probabilities, ensuring that the sum of all probabilities is 1.

![Softmax Formula](assets/image-14.png)
![Softmax Output](assets/image-15.png)
![Softmax Example](assets/image-13.png)
![Softmax Visualization](assets/image-16.png)
![Softmax Probabilities](assets/image-17.png)
![Softmax Distribution](assets/image-18.png)
![Softmax Activation](assets/image-19.png)
![Softmax Classes](assets/image-20.png)

(./lab/Softmax.ipynb)
(./lab/Multiclass_TF.ipynb)


## Optimization
Optimization algorithms are used to adjust the weights and biases of a neural network to minimize the loss function. In this chapter, we use the Adam algorithm, which combines the advantages of two other extensions of stochastic gradient descent: AdaGrad and RMSProp.

![Adam Algorithm Diagram](assets/image-23.png)
![Adam Update Rule](assets/image-21.png)
![Adam Optimization Steps](assets/image-22.png)

## Convolution Neural Network (CNN)
Convolutional Neural Networks are specialized neural networks for processing grid-like data, such as images. CNNs use convolutional layers to automatically and adaptively learn spatial hierarchies of features from input images.

![CNN Architecture](assets/image-25.png)
## Lab
(./lab/Multiclass_Handwritten.ipynb)
