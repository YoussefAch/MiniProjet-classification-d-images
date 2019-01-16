# Rock-Paper-Scissors (RPS) classification using PyTorch

## Authors : 
 - Youssef Achenchabe
 - Mehdi Ghouwati Badreddine
 
## Our work
In this notebook we will try to classify the RPS dataset using a fully connected neural network. This notebook is inspired from the MNIST example from PyTorch (https://github.com/pytorch/examples/tree/master/mnist).

## RPS dataset
We have created this 3 class dataset with other M2 students at ENSEEIHT, it contains 70 images (32 x 32) per class. We know that the number of images in this dataset is too slow to train a neural network. The main objective of this notebook is to prototype and start getting hands dirty with pytorch.
![screendataset](https://github.com/YoussefAch/RPS-classification-using-PyTorch/blob/master/RPS-dataset.jpg)



## The model
The model has 2 fully connected hidden layers: the first one with 20 neurons and the second one with 40 neurons.


## Convergence

![screendataset](https://github.com/YoussefAch/RPS-classification-using-PyTorch/blob/master/loss.png)


## Accuracy and loss results
 
![screendataset](https://github.com/YoussefAch/RPS-classification-using-PyTorch/blob/master/res.png)
