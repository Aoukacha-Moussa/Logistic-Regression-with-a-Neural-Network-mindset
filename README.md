# Logistic Regression with a Neural Network Mindset

This project is an implementation of a logistic regression classifier to recognize cats. The implementation is done with a neural network mindset, which helps in understanding the intuitions about deep learning.

## Table of Contents

- [1 - Packages](#1)
- [2 - Overview of the Problem set](#2)
    - [Exercise 1](#ex-1)
    - [Exercise 2](#ex-2)
- [3 - General Architecture of the learning algorithm](#3)
- [4 - Building the parts of our algorithm](#4)
    - [4.1 - Helper functions](#4-1)
        - [Exercise 3 - sigmoid](#ex-3)
    - [4.2 - Initializing parameters](#4-2)
        - [Exercise 4 - initialize_with_zeros](#ex-4)
    - [4.3 - Forward and Backward propagation](#4-3)
        - [Exercise 5 - propagate](#ex-5)
    - [4.4 - Optimization](#4-4)
        - [Exercise 6 - optimize](#ex-6)
        - [Exercise 7 - predict](#ex-7)
- [5 - Merge all functions into a model](#5)
    - [Exercise 8 - model](#ex-8)
- [6 - Further analysis (optional/ungraded exercise)](#6)
- [7 - Test with your own image (optional/ungraded exercise)](#7)

## Installation

This project requires Python 3 and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [h5py](http://www.h5py.org)
- [matplotlib](http://matplotlib.org)
- [PIL](https://pillow.readthedocs.io/en/stable/)
- [scipy](https://www.scipy.org/)

To run the project, you also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html).

## Run

In a terminal or command window, navigate to the top-level project directory `Logistic_Regression_with_a_Neural_Network_mindset/` (that contains this README), and run one of the following commands:

```bash
ipython notebook Logistic_Regression_with_a_Neural_Network_mindset.ipynb
