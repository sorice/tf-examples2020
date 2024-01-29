# PyData Montreal 2020 TensorFlow Tutorial

*Instructor: [Abel Meneses-Abad](https://menesesabad.com)*

- email: <abelma1980@gmail.com>
- twitter: [@abelma1980](https://twitter.com/abelma1980)
- github: [sorice](https://github.com/sorice/)

This repository contained some notebooks and other info associated with 
my proposal for PyData Montreal 2019,  referred to TensorFlow 1.13. 
Unfortunatelly in March of 2019, Google release tf2.0 since then the
examples have been changing to much.

The only usefull thing in this repo is the initial order of contents.
[Current tutorial for 2020](https://github.com/wittylytics/tensor-rfl.git)

### Who is this project for:
This book is for data analysts, data scientists, and researchers who 
want to make the results of their machine learning activities faster 
and more efficient.

## Installation Notes
This tutorial was tested using the following packages

- Python version 3.6 or 3.7
- `numpy` version 1.17.2 http://www.numpy.org/
- `tensorflow` version 1.13.1
- `tensorflow-gpu` version 1.13.1
- `keras` version 2.3.1 http://keras.io
- `jupyter/notebook` version 6.0.1

After doing proper virtualenv commands (creation and activation)
install all the dependencies using _requirements.txt_

```bash
$ pip install -r requirements.txt
```

## About Scientific Data

Classical MNIST database is present in the majority of the books and
examples about Artifitial Neural Network and tensorflow. Because it is a
good way to start this dataset is used as dataset in all the examples. 
[Download MNISTCorpus](http://yann.lecun.com/exdb/mnist/)

## Downloading the Tutorial Materials

```
git clone git://github.com/sorice/tensorflow1.13.git
```

## Brief Table of Contents

1. Preamble:
    1. Preliminaries: details to have a successful experience with this tutorial,load Data
    2. Config: config GPU, Keras backend and others
  all libraries and GPU
2. Introduction to Deep Learning ANN
3. ANN Frameworks
    1. Introduction to Tensorflow
    2. Introduction to Keras
4. Neural Network Examples
    1. Convolutional network
    2. Autoencoders
    3. Recurrent NN
5. Hyper Paramenter Tuning
6. Tensorboard

The folder _examples_ contain different examples of neural networks 
implemented on python using tensorflow.

## Bibliography

## Future Work

This is an introductory tutorial to learn to work with tensorflow and 
tensorboard in a basic way (if learning ANN could be basic in certain 
way). In the current moment (2019) tensorflow2.0 is ready, so a huge 
number of changes has been introduced for better design of Neural 
Network, debuging and deployment.

### Copyright Note
This collection of notebooks is based on 
[Deep Learning Keras-Tensorflow tutorial](https://github.com/leriomaggio/deep-learning-keras-tensorflow) 
and [TensorFlow Examples](https://github.com/aymericdamien/TensorFlow-Examples)
