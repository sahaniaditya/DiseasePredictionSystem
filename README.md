# Disease Prediction Model Deployment

## Introduction
This project implements a disease prediction model using machine learning techniques. The trained model is deployed for prediction of diseases based on input features such as symptoms, age, gender, and other relevant factors.

## Dataset
The dataset used for training the disease prediction model is available in the file `Training.csv`.

## Data Exploration and Preprocessing
- The dataset is explored to understand its structure and characteristics.
- Preprocessing steps such as handling missing values, duplicate rows, and encoding categorical variables are performed.

## Exploratory Data Analysis (EDA)
- EDA is conducted to analyze the distribution and relationships among different features in the dataset.
- Visualizations are generated to understand patterns and trends in the data.

## Model Training
- Three different machine learning models are trained: Decision Tree, Random Forest, and Support Vector Machine (SVM).
- Hyperparameter tuning is performed using techniques such as Grid Search and Randomized Search to optimize model performance.
- The trained models are evaluated on a test set to measure their accuracy.

## Model Interpretability
- Model interpretability techniques are explored to understand the decision-making process of the trained models.

## Model Deployment
- The best-performing model (Decision Tree) is selected for deployment.
- The trained model is serialized using pickle and saved as `classifier.pkl` for deployment.
- This serialized model can be used to make predictions on new data in a production environment.

## Usage
1. Clone the repository:
   ```bash
   git clone <repository_url>
