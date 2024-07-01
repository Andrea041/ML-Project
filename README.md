# Image recognition for Machine Learning course

<p align="left">
  <img src="https://upload.wikimedia.org/wikipedia/commons/1/12/Convolutional_Layers_of_a_Convolutional_Neural_Network.svg" alt="logo" style="width: 200px;"/>
</p>

## Main goal
The goal of the project is to train and evaluate one or more classification models. The MNIST dataset is used (grayscale images, 28x28).

## Description of the project
Extended MNIST (EMNIST): an extended version of the MNIST dataset, containing alphabetic letters instead of digits. A CSV file emnist-letters.csv is available (not in this repository cause file size is too large) with approximately 80,000 images of uppercase or lowercase letters. In classification, it is not necessary to distinguish between uppercase and lowercase letters, so there are 26 classes to be recognized. Each row of the file contains the label of the corresponding class for the image (an integer between 1 and 26), followed by 784 integers ranging from 0 to 255 encoding the grayscale intensity of each pixel.
