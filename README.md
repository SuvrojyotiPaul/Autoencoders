# Autoencoders


## Project Overview

This project delves into the fascinating world of autoencoders, particularly focusing on their application in understanding the internal workings of Convolutional Neural Networks (CNNs). It is divided into three parts, each building upon the previous to deepen the exploration into the capabilities and variations of autoencoders.

### Key Features

#### Part 1: Simple Autoencoder

- **Objective**: To create a basic autoencoder with one hidden layer in both the encoder and decoder.
- **Implementation**: The autoencoder is designed with specified dimensions, but there is room for experimentation to observe how different configurations affect the model's performance.
- **Application**: This part serves as an introduction to the concept of autoencoders and their fundamental mechanics.

#### Part 2: Variational Autoencoder (VAE)

- **Extension to VAE**: Transforming the simple autoencoder into a Variational Autoencoder.
- **Normal Distribution Mapping**: The encoder is modified to map its output to a Normal distribution.
- **KL Divergence as Auxiliary Loss**: Incorporating Kullback–Leibler divergence as an auxiliary loss function to enhance the model's learning process.
- **Insights**: This part explores the more complex VAE, which is crucial for generating new data that's similar to the input data.

#### Part 3: Convolutional VAE

- **Convolutional Encoder**: Replacing the initial layers of the encoder with convolutional layers.
- **Even-Shaped Kernels**: Ensuring the use of even-shaped kernels in the convolutional layers for consistency and effectiveness

in feature extraction.
- **Advanced Model Architecture**: This part combines the principles of VAEs with the power of CNNs, leading to a more sophisticated model capable of handling complex image data.
