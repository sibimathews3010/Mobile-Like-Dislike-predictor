﻿# Mobile-Like-Dislike-predictor
This repository contains the code for predicting whether a mobile is liked or disliked by customer based on mobile specifications given in dataset.
If the rating is 4 or above then It is liked by customer
else its is dislked by user.


There 2 models for its prediction
  1) MP Neuron
  2) Perceptron
  
The model has been made after cleaninig of dataset by removing some extra features, using one hot encoding, removing irrelevant words from dataset etc.
The values in RAM attribute has been converted in terms of GBs as there were some values in MB.


## MP Neuron

This model requies input in terms of binary values.

Values of some features such as Resolution, Pixel Density, Internal Memory, Screen to Body Ratio,
RAM, Processor frequency, Screen Size, Height, Capacity were binarized based on their mean values.


The accuracy achieved was 85.7 percent.

## Perceptron

This model requies input in continous values.

The accuracy achieved was 77.1 percent.
