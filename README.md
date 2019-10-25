# CNN-dog-breed-classifier

The purpose of this project is to develop a *Convolutional Neural Networks (CNN)* for dog breed recognition and is my *second project* of the [*Udacity Deep Learning Nanodegree program*](https://www.udacity.com/course/deep-learning-nanodegree--nd101).

## Quickstart

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
