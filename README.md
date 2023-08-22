# AWS-Sagemaker
# SageMaker Canary Deployment and Model Training

This repository contains two Jupyter Notebook files demonstrating SageMaker deployment guardrails with canary traffic shifting and a machine learning model training example using XGBoost.

## Canary Deployment (Canary_shift.ipynb)

The `Canary_shift.ipynb` notebook demonstrates how to perform a canary deployment using Amazon SageMaker's deployment guardrails. The notebook covers the following steps:

1. Creating and deploying pre-trained models.
2. Invoking the SageMaker endpoint.
3. Setting up CloudWatch alarms to monitor endpoint performance.
4. Updating the endpoint with deployment configurations using canary traffic shifting.
5. Cleaning up resources.

The notebook provides a hands-on example of how to update an endpoint while minimizing the risk of errors and performance regressions using canary deployments.

## XGBoost Model Training (Main_model.ipynb)

The `Main_model.ipynb` notebook demonstrates how to train a machine learning model using the XGBoost algorithm in Amazon SageMaker. The notebook includes the following steps:

1. Importing necessary libraries and installing required packages.
2. Defining the Amazon S3 bucket and prefix for data storage.
3. Defining the IAM role for model training.
4. Loading and preparing training, validation, and test datasets.
5. Uploading the training and validation data to Amazon S3.
6. Setting up the XGBoost Estimator for model training.
7. Fitting the XGBoost model to the data.

The notebook showcases the process of training an XGBoost model and provides a starting point for building and training machine learning models with SageMaker.

## Usage

1. Clone this repository to your local machine.
2. Open and run the Jupyter Notebook files in your preferred environment (e.g., Jupyter Notebook or JupyterLab).
3. Follow the instructions provided within each notebook to execute the code step by step.

Note: Make sure to have the required AWS credentials and permissions set up before running the code.

## License

This repository is licensed under the [MIT License](LICENSE).
