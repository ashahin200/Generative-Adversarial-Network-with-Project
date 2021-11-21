Here is the following Steps I have followed in order to train the DCGAN. At the end of the output the model will be able to generate synthatic image of different fashionable shoe, shirt, trousars, Belt etc.

Import Libraries
Load and Preprocess the Data
Create Batches of Training Data
Build the Generator Network for DCGAN
Build the Discriminator Network for DCGAN
Compile the Deep Convolutional Generative Adversarial Network (DCGAN)
Define Training Procedure
Train DCGAN
Generate Synthetic Images with DCGAN

-->This project does requires to import following libraries------

import tensorflow as tf
from tensorflow import keras
import numpy as np
import plot_utils
import matplotlib.pyplot as plt
from tqdm import tqdm

-->Here I have used Fashion MNIST dataset from dataset.loader of keras




