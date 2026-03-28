\# MVC Project: Multilayer Perceptron



\## What is this project?

This project is about building a Multilayer Perceptron (MLP) from scratch 

using only Python and NumPy. We start by doing all the math by hand 

(Tasks 1 to 6), and then we write Python code to train the same network 

on the MNIST handwritten digits dataset (Task 7).



\## What is an MLP?

An MLP (Multilayer Perceptron) is a type of neural network. It takes some 

numbers as input, passes them through layers of neurons, and produces a 

prediction at the end. Each neuron multiplies its inputs by weights, adds 

a bias, and then applies an activation function (we use sigmoid). The 

network learns by adjusting the weights using a process called 

backpropagation and gradient descent.



\## How to Run the Notebook



1\. Make sure you have Python 3.8 or higher installed.

2\. Install the required libraries:

&#x20;  pip install numpy matplotlib jupyter

3\. Copy the MNIST dataset file and place it in the data/ folder.

4\. Open the notebook:

&#x20;  jupyter notebook src/B\_i252015.ipynb

5\. Run all cells from top to bottom using Kernel > Restart \& Run All.



\## Requirements

\- Python 3.8+

\- NumPy

\- Matplotlib

\- Jupyter Notebook



\## Folder Structure

mvc-mlp-25i2015/

├── src/          # Jupyter Notebook with all code

├── data/         # MNIST dataset (.npz file)

├── report/       # Compiled PDF report

└── README.md     # This file

