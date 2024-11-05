# Iris Flower Species Prediction App

The **Iris Flower Species Prediction App** is a Streamlit-based web application that classifies iris flowers into three species — *Iris-setosa*, *Iris-virginica*, and *Iris-versicolor* — based on their sepal and petal dimensions. This application uses a Support Vector Machine (SVM) classifier to make predictions and provides an interactive interface for users to input data and get real-time predictions.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Model Information](#model-information)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)

## Installation

To run this application locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/AnkitDogra-07/iris-flower-classifier.git
2. **Navigate to the project directory:**:
   ```bash
   cd iris-flower-classifier
3. **Install the required packages: Use the following command to install the necessary libraries.**:
   ```bash
   pip install numpy pandas matplotlib seaborn streamlit scikit-learn
4. **Run the application:**:
   ```bash
   streamlit run app.py
This will open the application in your default web browser.
## Usage

Once the application is running, you can use the sliders to input values for the sepal and petal dimensions. After setting the values, click on the Predict button to classify the iris flower species. The predicted species and model accuracy score will be displayed on the screen.
Input Features

    Sepal Length
    Sepal Width
    Petal Length
    Petal Width

## Output

    The predicted species (Iris-setosa, Iris-virginica, Iris-versicolor)
    Model accuracy score on the training set

## Features

    Interactive sliders for inputting sepal and petal dimensions
    Predicts the species of an iris flower in real-time
    Displays model accuracy score for transparency

## Model Information

This application uses a Support Vector Machine (SVM) classifier with a linear kernel to classify iris flowers based on their sepal and petal measurements. The SVM model was trained on the Iris dataset from UCI Machine Learning Repository.

    Training Data: 67% of the dataset
    Testing Data: 33% of the dataset

## Technologies Used

    Python: Programming language
    Streamlit: Framework for creating the web app interface
    Scikit-learn: Machine learning library for model training and evaluation
    Numpy and Pandas: Data manipulation and analysis
    Matplotlib and Seaborn: Data visualization libraries
