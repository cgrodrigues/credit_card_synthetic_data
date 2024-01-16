# Credit Card Transactions Synthetic Data Generation

# Credit Card Transaction Data Analysis

## Introduction

This project addresses the challenge of obtaining real credit card transaction data to train machine learning models for fraud detection and credit risk assessment. Acquiring such data can be complex due to privacy concerns and regulatory restrictions, notably under the General Data Protection Regulation (GDPR).

The General Data Protection Regulation (GDPR) imposes strict regulations on the processing and handling of personal data. This includes financial transactions, which are often considered sensitive and private. As a result, obtaining real credit card transaction data for analysis and modeling can be legally and ethically challenging.

## Jupyter Notebooks

This repository contains four Jupyter notebooks, each serving a specific purpose in the analysis and modeling of credit card transactions.

### 1. cc-demo-generate-data.ipynb

This notebook focuses on the generation of synthetic credit card transaction data. It explores techniques for creating realistic transaction data that can be used for model training and testing.

### 2. cc-demo-feature-generation.ipynb

In this notebook, feature engineering techniques for credit card transaction data are demonstrated. 

### 3. cc-demo-model-evaluation.ipynb

The third notebook is dedicated to model evaluation. It covers the training and assessment of machine learning models for credit card fraud detection or risk assessment. Evaluation metrics and model performance analysis are included (Soon).

### 4. cc-demo-dashboards.ipynb

This notebook showcases the creation of dashboards to visualize and explore credit card transaction data and model results. Dashboards provide a user-friendly way to gain insights from the data and models.

## Getting Started

To get started with this project, clone the repository and open the Jupyter notebooks in your preferred environment. Each notebook includes detailed explanations and code to guide you through the analysis and modeling process.

# Setting Up a Python Environment

## Introduction

This guide will walk you through the steps to create a Python environment to run the Jupyter Notebooks in this repo. This environment will help you manage your project's dependencies and isolate your Python packages for better organization.

## Steps to Create a Python Environment

1. **Create a Virtual Environment:**

   To create a virtual environment, open your terminal and navigate to the project's root directory. Run the following command to create a virtual environment named ".env":

   ```bash
   virtualenv .env
   ```
2. Activate the Virtual Environment:

   After creating the virtual environment, you need to activate it. Run the following command to activate the environment:
   ```bash
   source ./.env/bin/activate
   ```

3. Install Project Dependencies:
    To install the necessary Python packages and dependencies for your project, you can use the provided "requirements.txt" file. Make sure you are in the project directory and run the following command:
    ```bash
    pip install -r ./requirements.txt
    ```
    This command will install all the required packages listed in the "requirements.txt" file.

# List of Software Required

Make sure you have Python installed on your system. If it's not already installed, you can download it from the official Python website by [clicking here](https://www.python.org/downloads/).

If *virtualenv* is not installed on your system, you can install it using pip by running the following command:
```bash
pip install virtualenv
```

## Disclaimer

Please note that the credit card transaction data used in this project is synthetic and for demonstration purposes only. It does not contain real customer data or transaction information.