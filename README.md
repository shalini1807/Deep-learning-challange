1. # Overview of the Analysis

This analysis aims to develop a deep learning model to predict outcomes for Alphabet Soup, a charity organization, based on provided features. 
The model aims to classify whether funding applications will likely succeed or fail, enabling the organization to optimize its resource allocation.

2. # Results

# Data Preprocessing:

# Target Variable:

IS_SUCCESSFUL was selected as the target variable, as it indicates the success or failure of an application.

# Features:

Key features used in the model include:

APPLICATION_TYPE

AFFILIATION

CLASSIFICATION

USE_CASE

ORGANIZATION

INCOME_AMT

SPECIAL_CONSIDERATIONS

ASK_AMT

# Removed Variables:

The EIN and NAME variables were removed. These variables are unique identifiers and do not contribute meaningful information for the prediction task.

Compiling, Training, and Evaluating the Model

Neurons, Layers, and Activation Functions:

The model architecture consisted of the following:

Input Layer: The number of input neurons matches the number of features after one-hot encoding.

# Hidden Layers:

Layer 1: 80 neurons, ReLU activation function.

Layer 2: 30 neurons, ReLU activation function.

Output Layer: 1 neuron, Sigmoid activation function for binary classification.

# Model Performance:

The target model performance was to achieve an accuracy of 75%.

After initial training, the model achieved an accuracy of approximately 72%.

# Steps to Improve Performance:

# First Attempt:

Increased the number of neurons in the hidden layers to capture more complex relationships.

Experimented with additional hidden layers.

# Second Attempt:

Implemented feature engineering by scaling numeric data.

Removed less impactful features to reduce noise.

Despite these changes, the maximum accuracy achieved was 73%, suggesting potential limitations in the dataset or model architecture.

3. # Summary

The deep learning model achieved a maximum accuracy of 73%, which fell short of the 75% target. Although several adjustments were made to improve performance, including tuning the architecture and preprocessing features, the results highlight the potential for further improvement.



