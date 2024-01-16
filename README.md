# credit_card_synthetic_data
Credit Card Transactions Synthetic Data Generation




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


