# AI Image Classifier by Bhuvanyu Geel

## Project Overview
This project is an AI-based image processing application designed to classify handwritten digits (0-9). It fulfills the assignment objective to build a small image classification application using Python.

We utilize a Convolutional Neural Network (CNN), which is the standard approach for modern image recognition, ensuring the solution is robust and accurate.

## Requirements
To run this project, you need the following tools and libraries installed:
* Python 3.x
* TensorFlow
* NumPy
* Matplotlib
* Jupyter Notebook (or JupyterLab)

## Installation
1.  Clone or download this project folder.
2.  Open your terminal or command prompt.
3.  Install the necessary dependencies by running:
    pip install tensorflow numpy matplotlib jupyterlab

## How to Run
1.  Launch Jupyter Notebook by typing the following command in your terminal:
    jupyter notebook
2.  Open the file named "AI Image_Classifier.ipynb".
3.  Click on "Cell" in the top menu and select "Run All".
4.  The notebook will download the data, train the model, and display a prediction result at the bottom.

## Features
* **Data Loading:** Automatically loads the MNIST dataset.
* **Preprocessing:** Resizes and normalizes image data for better performance.
* **Modeling:** Uses a CNN to learn patterns in the images.
* **Visualization:** Displays the test image and the predicted label.
