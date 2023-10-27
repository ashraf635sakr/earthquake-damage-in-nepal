# Earthquake Damage Prediction in Nepal

This project focuses on predicting earthquake damage in Nepal using machine learning models. It includes data extraction from a SQL database, data preprocessing, model building, and hyperparameter tuning. The goal is to create models for earthquake damage classification.

## Project Structure

The project consists of the following components:

- **data:** This folder contains the raw data used for the project, which is extracted from a SQL database.

- **Jupyter Notebooks:** The project includes five Jupyter notebooks that cover various aspects of the analysis and model building:

    In this project, we undertake a series of crucial data analysis and machine learning tasks. First, we begin by extracting data from a SQL database, which forms the foundation of our analysis. Once the data is acquired, we perform a randomized train-test split to create a reliable evaluation framework for our predictive models. With the data prepared, we proceed to build two classification models. The first is a logistic regression model, a widely used technique for classification tasks, which helps us make predictions based on the extracted features. Additionally, we construct a decision tree model for classification, providing us with a different perspective on predicting earthquake damage. Finally, we fine-tune the hyperparameters of our models to optimize their performance, ensuring that our predictive models are as accurate and efficient as possible. This sequence of steps forms the core of our project, enabling us to develop robust models for earthquake damage classification based on the provided data.



## Instructions

To run the project, follow these steps:

1. Clone the repository to your local machine.
2. Ensure you have the necessary libraries and dependencies installed.
3. Start by running `1- sqlite explore` to extract data from the SQL database.
4. Continue with the subsequent notebooks in order, as each one builds upon the previous steps.
5. Pay attention to the instructions and comments within each notebook for guidance.
6. The hyperparameter tuning in `06_hyperparameter_tuning.ipynb` is crucial for model optimization.

## Dependencies

The project relies on the following Python libraries and packages:

- `numpy`
- `pandas`
- `scikit-learn`
- `matplotlib`
- `seaborn`

Make sure to install these dependencies in your Python environment before running the notebooks.

## Data Source

The raw data for this project is extracted from a SQL database. The dataset contains information related to earthquake damage in Nepal.


