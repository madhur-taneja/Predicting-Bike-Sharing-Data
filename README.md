# Predicting Bike Sharing Data
#### First Neural Network

A neural network built from scratch to carry out a prediction problem on a real dataset to predict how many bikes a business would need according to the historical data so that it doesn't lose out money from potential riders by having too few bikes and also doesn't waste money on bikes that are just sitting around by having too many.

Open and view the Project using the `.zip` file provided or at my [Github Repository](https://github.com/madhur-taneja/Predicting-Bike-Sharing-Data).

The project is also hosted on [Github](https://madhur-taneja.github.io/Predicting-Bike-Sharing-Data/Your_first_neural_network).

## Table of Contents
- [Getting Started](#getting-started)
	- [Tools Required](#tools-required)
	- [Installation](#installation)
- [Development](#development)
- [Extras](#extras)
- [Running the App](#running-the-app)
- [References](#references)

## Getting Started

The starter project can be downloaded from [here](https://github.com/udacity/deep-learning/tree/master/first-neural-network)

The project will be evaluated by a Udacity code reviewer according to the Landing Page project [rubric](https://review.udacity.com/#!/rubrics/700/view)

This is how the neural network will look:

![first-neural-network](./assets/neural_network.png)

The network has two layers, a hidden layer and an output layer. The hidden layer will use the sigmoid function for activations. The output layer has only one node and is used for the regression, the output of the node is the same as the input of the node.

### Tools Required

You would require the following tools to develop and run the project:

* [Python](https://www.python.org/downloads/)
* [Anaconda](https://www.anaconda.com/products/individual)

### Installation

* Start by installing python and anaconda
* Create a new conda environment
	```
	conda create --name dlnd python=3
	```
* Enter your new environment:
	* Mac/Linux: `>> source activate dlnd`
	* Windows: `>> activate dlnd`
* Install `numpy`, `matplotlib`, `pandas`, and `jupyter notebook` using the following command:
	```
	conda install numpy matplotlib pandas jupyter notebook
	```

## Development

* Run the following to open up the notebook server:
	```
	jupyter notebook
	```
* In your browser, open `Your_first_neural_network.ipynb`
* Follow the instructions in the notebook; they will lead you through the project. You'll ultimately be editing the `my_answers.py` python file, whose components are imported into the notebook at various places.

## Extras

* Before submitting your solution to a reviewer, you are required to submit your project to `Udacity's Project Assistant`, which will provide some initial feedback.
* The setup for the project assistant is simple. If you have not installed the client tool from a different Nanodegree program already, then you may do so with the command: `pip install udacity-pa`
* To submit your code to the project assistant, run `udacity submit` from within the top-level directory of the project. You will be prompted for a username and password.
* This process will create a zipfile in your top-level directory named `first_neural_network-result-.zip`, where there will be a number between `result-` and 	`.zip`. This is the file that you should submit to the Udacity reviews system.

## Running the App

To run the project, open it in Jupyter Notebook and press the `play`  :arrow_forward:  icon to start the execution.

## References

* [Gradient](https://www.khanacademy.org/math/multivariable-calculus/multivariable-derivatives/gradient-and-directional-derivatives/v/gradient) by Khan Academy
* [Multivariable calculus lessons](https://www.khanacademy.org/math/multivariable-calculus) by Khan Academy
* [Backpropogation Lecture](https://www.youtube.com/watch?v=59Hbtz7XgjM) from Andrej Karpathy
