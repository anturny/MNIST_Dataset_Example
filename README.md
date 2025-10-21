# MNIST_Dataset_Example
This project demonstrates how to use the MNIST dataset, a popular collection of handwritten digit images, to train and evaluate a neural network for image classification. By leveraging TensorFlow and Keras, the goal is to develop a model capable of accurately recognizing and classifying handwritten digits, serving as a fundamental example for understanding image recognition techniques in machine learning.

# Table Of Contents
- [Implementation](#implementation)
- [Requirements](#requirements)
- [How to Use](#how-to-use)
- [References](#references)

# Implementation
The MNIST dataset is a widely used collection of handwritten digit images, consisting of 70,000 grayscale images of digits from 0 to 9. Its primary purpose is to serve as a benchmark for training and evaluating machine learning models in image recognition tasks. By using this dataset, algorithms learn to identify and classify handwritten digits, which helps in developing systems for optical character recognition and other pattern recognition applications. The MNIST dataset is fundamental for understanding and experimenting with image classification techniques in machine learning.

# Requirements 
- Visual Studio Code (Software)
- Python Language on Computer (3.12.0)
- GitBash (Optional)

- This project is designed to run in a VSCode terminal using a Python environment.

Use 'pip install -r requirements.txt' to install the following dependencies:
```
tensorflow==2.20.0
keras==3.11.3
scikit-learn==1.7.1
```

# How to Use
- To run this code, you will need to have a Python environment installed on your computer. It is recommended to use Visual Studio Code as this Python script was written and ran in VSCode. GitBash is also recommended in order to synchronize your VSCode with GitHub.
- In GitHub, click on the green icon labeled "<> CODE" on the top of this page and copy the HTTPS link.
- In VSCode, click on "Clone Git Repository" and paste the copied link from GitHub.
- In the search bar, type in "Python: Create Environment" and then select a preferred environment. This code used .venv as the virtual environment.
- When the virtual environment is open (appears as .venv in the list of items in the left menu), you may navigate to the [MNIST.py](/src/MNIST.py) file and select it. At this point, you may open your terminal and install the pip requirements for the necessary libraries in order to execute the code. Then, you may hit "Run" on the top right hand corner to execute the code.

- Note: Upon copying the GitHub repository, the dataset should have already been included in order to run the code. If not, please refer to the [mnist_test.csv](/src/mnist_test.csv) file and gather this file into your source folder prior to running the code.

# References 
- [1]GeeksforGeeks, “MNIST Dataset : Practical Applications Using Keras and PyTorch,” GeeksforGeeks, May 2024. https://www.geeksforgeeks.org/machine-learning/mnist-dataset/
‌
