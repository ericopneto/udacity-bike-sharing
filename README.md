# Udacity Deep Laerning Foundations Nanodegree

## Project 1: Your first neural network - Bike sharing

In this project, i'll make a neural network to solve a prediction problem in a real dataset! By building a neural network from scratch, you will understand much better how gradient descent, backpropagation, and other important concepts of neural networks work. You also get a chance to see your network solving a real problem!

The data comes from the [UCI Machine Learning Database link](https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset)

## Problem

**Statement:** Neural Network for predicting Bike Sharing Rides. Here NN will predict how many bikes a company needs because if they have too few they are losing money from potential riders and if they have too many they are wasting money on bikes that are just sitting around. So NN will predict from the hisitorical data how many bikes they will need in the near future.

**Network Description:** The network has two layers, a hidden layer and an output layer. The hidden layer uses the sigmoid function for activations. The output layer has only one node and is used for the regression, the output of the node is the same as the input of the node. That is, the activation function is f(x)=xf(x)=x . A function that takes the input signal and generates an output signal, but takes into account the threshold, is called an activation function. We work through each layer of our network calculating the outputs for each neuron. All of the outputs from one layer become inputs to the neurons on the next layer. This process is called forward propagation. We use the weights to propagate signals forward from the input to the output layers in a neural network. We use the weights to also propagate error backwards from the output back into the network to update our weights. This is called backpropagation.

## Running using conda!

Run this in command line

**Step 1:** Create a new environment

```terminal
conda create --name dlnd python=3
```

**Step 2:** Use the new env

```terminal
source activate dlnd
```

**Step 3:** Install dependencies

```terminal
conda install numpy matplotlib pandas jupyter notebook
```

**Step 4:** Open the notebook to run it

```terminal
jupyter notebook dlnd-your-first-neural-network.ipynb
```

## Project structure

This folder contains files for Udacity Deep Laerning Foundations Nanodegree Project 1: Bike Share.

**dlnd-your-first-neural-network.ipynb** - Main project file.

**dlnd-your-first-neural-network.html** - Neural network prediction results file.

**Bike-Sharing-Dataset/day.csv** - Information about each trip taken using the bike share system by day.

**Bike-Sharing-Dataset/hour.csv** - Information about each trip taken using the bike share system by hour.

**Bike-Sharing-Dataset/Readme.txt** - General dataset description.
