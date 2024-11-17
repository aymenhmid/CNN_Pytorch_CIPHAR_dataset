# CNN Model on CIFAR Dataset

This repository contains a CNN model designed to classify images from the CIFAR-10 dataset. The model is implemented using Python and the Keras library.

## Dataset

The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class. The dataset is divided into 50,000 training images and 10,000 test images.

## Model

The CNN model consists of the following layers:

- Conv2D layer with 128 filters, kernel size 5x5, and padding 2
- Conv2D layer with 128 filters, kernel size 5x5, and padding 2
- Conv2D layer with 256 filters, kernel size 3x3, and padding 1
- Conv2D layer with 256 filters, kernel size 3x3, and padding 1
- MaxPooling2D layer with pool size 2x2
- BatchNormalization2D layer for each convolutional layer
- Dropout2D layer with dropout rate 0.25
- Dropout layer with dropout rate 0.5
- Dense layer with 1024 units
- Dense layer with 512 units
- Dense layer with 10 units

## Dependencies

- Python 3.8
- Keras 2.4.3
- Pytorch 1.7.1
- NumPy 1.20.0
- Matplotlib 3.4.3

## Usage

1. Clone the repository using `git clone https://github.com/aymenhmid/CNN_Pytorch_CIPHAR_dataset.git`
3. Download the CIFAR-10 dataset from this link (https://www.cs.toronto.edu/~kriz/cifar-10-python.tar.gz)
4. preferably run the notebook on colab using GPU

## Results

The model achieves an accuracy of 90% on the test dataset.

## Acknowledgments

This project was inspired by the Kaggle Notebooks on the same subject.
