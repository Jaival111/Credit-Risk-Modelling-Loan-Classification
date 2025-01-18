# Credit-Risk-Modelling-Loan-Classification

This repository contains a machine learning model that predicts if an individual will repay the loan or not based on various input features. The model was built using **RandomForest Classifier** and trained on a dataset of loan_detectin data. It has achieved **99% accuracy** on the training set and **96% accuracy** on the test set.

## Project Overview

The goal of this project is to develop a model that can predict if an individual will repay the loan or not based on input features and relevant attributes. The dataset used for training and testing the model was carefully preprocessed to ensure the highest possible accuracy.

### Key Features:
- **RandomForest Classifier**: The model uses RandomForest Classifier.
- **Accuracy**: Achieved **99% accuracy** on the training data and **96% accuracy** on the test data.

> Note: Ensure that the data is clean and free from any missing values before running the model.

## Installation

To run the house price prediction model, you need to have Python installed on your machine along with the necessary dependencies. You can set up the environment using the following steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/Jaival111/Credit-Risk-Modelling-Loan-Classification.git
    cd Credit-Risk-Modelling-Loan-Classification
    ```

2. Create a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

To use the model for house price prediction, you can refer to the jupyter file:

1. Download and prepare the dataset (if not already included).
2. Run the below script:
    ```bash
    jupyter notebook
    ```

## Model Evaluation

The model was evaluated based on the following metrics:
- **Training Accuracy**: 99%
- **Test Accuracy**: 96%

The model generalizes well to unseen data, indicating that the RandomForest Classification approach was effective for this particular dataset.

## Dependencies

The project requires the following Python libraries:
- `pandas`
- `scikit-learn`
- `imbalanced-learn`
- `matplotlib`
- `seaborn`

Install all dependencies by running:
```bash
pip install -r requirements.txt


