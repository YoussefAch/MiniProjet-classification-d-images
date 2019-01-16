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

## Accuracy and loss results
 
 Train Epoch: 87/100 [161/161 (23%)]	Loss: 0.697446	 Test Accuracy: 51.2195%
 Train Epoch: 88/100 [161/161 (23%)]	Loss: 0.639645	 Test Accuracy: 56.0976%
 Train Epoch: 89/100 [161/161 (23%)]	Loss: 0.622699	 Test Accuracy: 48.7805%
 Train Epoch: 90/100 [161/161 (23%)]	Loss: 0.833772	 Test Accuracy: 36.5854%
 Train Epoch: 91/100 [161/161 (23%)]	Loss: 0.818403	 Test Accuracy: 36.5854%
 Train Epoch: 92/100 [161/161 (23%)]	Loss: 0.395956	 Test Accuracy: 43.9024%
 Train Epoch: 93/100 [161/161 (23%)]	Loss: 0.814989	 Test Accuracy: 41.4634%
 Train Epoch: 94/100 [161/161 (23%)]	Loss: 0.524944	 Test Accuracy: 53.6585%
 Train Epoch: 95/100 [161/161 (23%)]	Loss: 0.581320	 Test Accuracy: 53.6585%
 Train Epoch: 96/100 [161/161 (23%)]	Loss: 1.231633	 Test Accuracy: 43.9024%
 Train Epoch: 97/100 [161/161 (23%)]	Loss: 0.768421	 Test Accuracy: 46.3415%
 Train Epoch: 98/100 [161/161 (23%)]	Loss: 0.381561	 Test Accuracy: 46.3415%
 Train Epoch: 99/100 [161/161 (23%)]	Loss: 0.388825	 Test Accuracy: 46.3415%
 Train Epoch: 100/100 [161/161 (23%)]	Loss: 1.217011	 Test Accuracy: 46.3415%
 
 