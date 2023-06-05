**Fashion MNIST Classification using Deep Learning**
This repository contains the code for training and evaluating a deep learning model to classify Fashion MNIST dataset. The Fashion MNIST dataset consists of 60,000 grayscale images of 10 different fashion categories.
I used Google Colab for building this model and took the dataset from there itself.

Download the Fashion MNIST dataset by running the following code in a code cell:
--------------------------------------------------------------------------------------------------------------------------------------
**CODE:**
from tensorflow.keras.datasets import fashion_mnist

(x_train, y_train), (x_test, y_test) = fashion_mnist.load_data()
---------------------------------------------------------------------------------------------------------------------------------------
The goal of this project is to build a deep learning model that can accurately classify these images into their respective fashion categories. The model will be trained on a subset of the dataset and evaluated on a separate test set.

This model gave** 91% Accuracy** in classifying different labels of data which included :0) T-shirt/top", "1) Trouser", "2) Pullover", "3) Dress", "4) Coat", "5) Sandal", "6) Shirt", "7) Sneaker", "8) Bag", "9) Ankle Boot"]

LINK: https://colab.research.google.com/drive/1-3WYGq46XC4AenG7L2tLxQ988Uu8WB8s#scrollTo=93-3md0-GbK_
