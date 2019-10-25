# CNN-dog-breed-classifier

The purpose of this project is to develop a *Convolutional Neural Networks (CNN)* for dog breed recognition and is my *second project* of the [*Udacity Deep Learning Nanodegree program*](https://www.udacity.com/course/deep-learning-nanodegree--nd101).

## Installation

This project is based on [Pytorch](https://pytorch.org/) and [Jupyter notebook](https://jupyter.org/). All the installation process are handled by [Anaconda](https://www.anaconda.com/), one of the the most popular ***Data Science platform***, so is quite straightforward.

Download and install the ***Anaconda platform*** for the OS and architecture in use:

    $ wget https://repo.anaconda.com/archive/Anaconda3-2019.03-Linux-x86_64.sh
    $ ./Anaconda3-2019.03-Linux-x86_64.sh

Create an ***Anaconda environment*** for the project based on Python 3.6:

    $ conda install python=3.6.8
    $ conda create -n dog-breed python=3.6
    $ conda activate dog-breed

Install all the ***required dependencies*** always using Anaconda (in this case without GPU support):

    $ conda install -c conda-forge matplotlib
    $ conda install numpy jupyter notebook
    $ conda install pytorch-cpu torchvision-cpu -c pytorch

## Dataset

The ***dog dataset*** is based on the [Stanford Dogs Dataset](http://vision.stanford.edu/aditya86/ImageNetDogs/) by Khosla, Jayadevaprakash and Yao and Li Fei-Fei of the Vision Lab Computer Science Department, Stanford University.

The ***human faces dataset*** is based on the [Labeled Faces in the Wild (LFW) dataset](http://vis-www.cs.umass.edu/lfw/) by Huang, Ramesh, Berg and Learned-Miller of the University of Massachusetts.

## Goal

The aim of the project is to design an application that accept a *user-supplied image* as input and if a ***dog is detected*** in the image, it will provide an estimate of the dog's breed; if a ***human face is detected***, it will provide an estimate of the dog breed that is most resembling.
