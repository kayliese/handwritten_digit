# Handwritten Digit Recognition

This project is focused on building a deep learning model that can recognize handwritten digits. The model is built using the popular deep learning framework, Keras.

## About

This project aims to build a deep learning model that can accurately recognize handwritten digits. The model is trained using the MNIST dataset, which consists of a large number of images of handwritten digits. The model is then tested on a separate set of images to evaluate its accuracy.

## Dependencies

Make sure the following dependencies are installed:

- Tensorflow
- Keras
- NumPy
- Matplotlib

You can install them using the following command:

```
pip install tensorflow keras numpy matplotlib
```

## Dataset

The dataset used for training the model is the MNIST dataset, which can be downloaded from [here](http://yann.lecun.com/exdb/mnist/). After downloading, extract the files and place them in the data directory.

## Usage

To train the model, run the following command:

```
python train.py
```


This will create a model file named `model.h5` in the model directory.

To test the model, run the following command:

```
python test.py
```


This will prompt you to enter the path to an image of a handwritten digit. After entering the path, the model will predict the digit and display it along with the confidence score.

## Credits

- Keras - the deep learning framework used for building the model.
- MNIST - the dataset used for training the model.



