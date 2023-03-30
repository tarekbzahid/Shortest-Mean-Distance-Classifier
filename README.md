# Shortest-Mean-Distance-Classifier
MNIST Classwise Average Visualization and Distance Calculation

This code demonstrates how to visualize the classwise average of MNIST dataset and how to calculate the distance between two classes.
Dependencies

    numpy
    matplotlib
    sklearn

Data

The MNIST dataset is loaded from the following files:

    MNISTcwtrain1000.npy: a 2D numpy array of 1000 training images, each image represented by a 1D vector of length 784 (28x28 pixels).
    MNISTcwtest100.npy: a 2D numpy array of 100 test images, each image represented by a 1D vector of length 784.

Code Overview

    The training and test datasets are loaded using numpy's load() function.
    The classwise average of the training dataset is calculated by taking the mean of each class (0-9) separately using numpy's sum() and astype() functions.
    A function unpackcw() is defined to convert the 1D vectorized image into a 2D array of size 28x28.
    The classwise averages are then visualized using matplotlib's imshow() function.
    A function calcdist() is defined to calculate the Euclidean distance between two classes.

How to Use

    Ensure that the dependencies are installed.
    Download the MNIST dataset files: MNISTcwtrain1000.npy and MNISTcwtest100.npy.
    Place the files in the same directory as the code file.
    Run the code using a Python IDE or the command line.
    The classwise averages will be displayed as images and the distances between two classes will be printed.

