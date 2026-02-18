## Deep Learning Project: Handwritten Digit Recognition Using CNN (MNIST Dataset)

Handwritten digit recognition is one of the most fundamental deep learning problems that serves as an entry point for understanding image classification, convolutional neural networks (CNNs), and production-ready model deployment.
In this project, you will build a complete end-to-end solution using the MNIST dataset, visualize and preprocess data, train a CNN model, evaluate performance, and integrate cloud-based computer vision services.

## Project Overview

This project focuses on building a Convolutional Neural Network (CNN) using the MNIST dataset for classifying handwritten digits (0–9). The MNIST dataset contains grayscale, 28×28 pixel images and is one of the most widely used benchmark datasets in the deep learning community.

## The project demonstrates:

- Deep learning fundamentals
- CNN architecture design
- Data visualization
- Training & evaluating neural networks
- Building production-ready prediction code
- Using cloud AI services like Google Vision API, AWS Rekognition, and Azure Computer Vision
- Making predictions on individual images using Python’s PIL library



## Dataset Description

The MNIST dataset (“Modified National Institute of Standards and Technology”) was released in 1999 and remains a foundational benchmark for image classification.

- 60,000 training images
- 10,000 testing images
- Grayscale
- 28×28 pixels
- Digits from 0 to 9

Each image is labeled, making it ideal for supervised learning.

## Steps to Run

There are two ways to execute the end to end flow.

- Modular Code (engine.py)
- IPython

### Modular code

- Create virtualenv

### Code Implementation

The Python 3.8 version is supported for the execution of this project.
1. Running the codes locally: Python 3.8
    - Create a virtual environment: In the terminal or command prompt, use the following command to create a new virtual environment:

        - For Windows:
            `py -3.8 -m venv env`

        - For macOS and Linux:
            `python3 -m venv venv`
        This command creates a new virtual environment named "venv" in the current directory.

    - Activate the virtual environment:

        - For Windows (Command Prompt):
            `venv\Scripts\activate`


        - For macOS and Linux (Terminal) :
            `source venv/bin/activate`
    
    Once the virtual environment is activated, you should see the environment name (e.g., (venv)) in the terminal or command prompt.

    - Install project requirements: With the virtual environment active, you can now install the required packages for your project. Typically, the required packages are listed in a requirements.txt file. Make sure you have the requirements.txt file for your project.

2. Setup the pip and installing dependencies in Virtual environment

    - Upgrade pip
        `python -m pip install --upgrade pip`

    - To install the requirements, use the following command:
        `pip install -r requirements.txt`

### IPython Notebook

Follow the instructions in the notebook `Handwritten-Digit-Recognizer.ipynb`

- Install requirements `pip install -r requirements.txt`
- Run Modular Code `python Engine.py`

### IPython Notebook

Follow the instructions in the notebook `Handwritten-Digit-Recognizer.ipynb`

