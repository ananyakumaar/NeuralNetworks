
# MNIST Digit Classification with TensorFlow and Keras

This repository contains a simple implementation of a neural network to classify handwritten digits from the MNIST dataset using TensorFlow and Keras.


## Overview

The MNIST dataset consists of 60,000 training images and 10,000 testing images of handwritten digits (0-9). Each image is 28x28 pixels. The goal of this project is to build a neural network that can accurately classify these images into the correct digit categories.
## Requirements

1.Python 3.x

2.TensorFlow 2.x

3.Keras
## Installation

1.Clone this repository:

```bash
git clone https://github.com/ananyakumaar/NeuralNetworks.git
```

2.Navigate to the project directory:

```bash
cd NeuralNetworks

```

3.Install the required packages:

```bash
pip install tensorflow


```



## Usage

1.Run the script
```python
python NeuralNetworks.py

```
2.The script will load the MNIST dataset, normalize the data, build and train a neural network, and then evaluate its performance on the test dataset.


## Results
After training for 5 epochs, the model should achieve an accuracy of around 98% on the test dataset.
## Acknowledgements

 - The MNIST dataset is a classic dataset in the field of machine learning and is widely used for benchmarking image classification algorithms.


 - This project uses TensorFlow and Keras, powerful tools for building and training neural networks.



## License

This project is licensed under the [MIT](https://choosealicense.com/licenses/mit/) License - see the LICENSE file for details.


