# AI Models: MNIST and CIFAR-10

This repository contains two computer vision models implemented using deep learning techniques. One model is trained on the MNIST dataset for handwritten digit recognition, while the other is trained on the CIFAR-10 dataset for object classification.

## Table of Contents

- [Overview](#overview)
- [Models](#models)
  - [MNIST Model](#mnist-model)
  - [CIFAR-10 Model](#cifar-10-model)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview

This project demonstrates the implementation of convolutional neural networks (CNNs) for image classification tasks using two popular datasets: MNIST and CIFAR-10.

## Models

### MNIST Model

The MNIST model is designed for recognizing handwritten digits (0-9). It uses a CNN architecture to achieve high accuracy on this grayscale image dataset.

Key features:
- Input: 28x28 grayscale images
- Output: 10 classes (digits 0-9)
- Architecture: Convolutional layers followed by dense layers

### CIFAR-10 Model

The CIFAR-10 model is built for classifying color images into 10 different categories. It employs a deeper CNN architecture to handle the increased complexity of this dataset.

Key features:
- Input: 32x32 RGB images
- Output: 10 classes (airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck)
- Architecture: Deep CNN with multiple convolutional and pooling layers

## Installation

To set up the project environment:

1. Clone this repository:

 ``` bash
git clone https://github.com/KanishkThamman/cifar-10.git
 ```


2. Navigate to the project directory:
 ``` bash
cd cifar10
 ```


## Usage

To train and evaluate the models:

python smthThatDefWorks.ipynb

## Results

- MNIST Model: Achieved 98% accuracy on the test set
- CIFAR-10 Model: Achieved 66.5% accuracy on the test set


## Contributing

Contributions to improve the models or extend the project are welcome. Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/improvement`)
3. Make your changes and commit them (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Create a new Pull Request

## License

This project is licensed under the MIT License