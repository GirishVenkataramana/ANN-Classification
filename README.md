# ANN Classification - Customer Churn Prediction

This project implements an Artificial Neural Network (ANN) for predicting customer churn using the Churn Modeling dataset. The application is built with TensorFlow and deployed using Streamlit to provide an interactive user interface for testing the model.

## Project Overview

Customer churn prediction is critical for businesses to retain valuable customers and minimize loss. In this project, we develop a neural network model to predict whether a customer will leave a service based on various input features.

## Key Features

- **ANN Model:** Implemented using TensorFlow's Sequential API.
- **Training Visualization:** Utilizes TensorBoard for visualizing training progress, loss, and accuracy.
- **Deployment:** The model is deployed as a Streamlit web app for easy accessibility.

## Model Implementation

1. **Sequential Model:** Built using TensorFlow's Sequential API.
2. **Dense Layers:** Used for creating hidden layers with activation functions.
3. **Activation Functions:** Applied ReLU and Sigmoid for non-linearity.
4. **Optimizer:** Adam optimizer is used for efficient gradient descent.
5. **Loss Function:** Binary Crossentropy for binary classification.
6. **Metrics:** Accuracy is used to evaluate model performance.
7. **Training Logs:** Stored in a TensorBoard folder for visualization.

## Setup and Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/ann-classification.git
   cd ann-classification
