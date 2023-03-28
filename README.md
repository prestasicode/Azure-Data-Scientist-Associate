# Azure-Data-Scientist-Associate

Materials:
1. Design a machine learning model training solution.
2. Explore developer tools for workspace interaction.
3. Make data available in Azure ML.
4. Work with compute target in Azure ML.
5. Find the best classification model with Automated ML.

Common ML Tasks:
1. Classification
2. Regression
3. Time Series Forecasting
4. Natural Language Processing (NLP)
5. Computer Vision

End-to-End Train Machine Learning Model:
1. Define the Problem
2. Get the Data
3. Prepare the Data
4. Train the Model
5. Integrate the Model
6. Monitor the Model

## Azure Machine Learning
Azure Service --> UI possible to manage ML Lifecycle full control train model and manage. Develop model using Python.

## Memory Optimized CPU/Single GPU
Azure Machine Learning Workspace --> Large tabular dataset to train and validate model ML in AZ ML Notebooks --> GPU 
CPU for smaller tabular datasets
2 Types VM Sizes:
1. General Purpose
2. Memory Optimized : High memory of CPU, fit to larger dataset and work with notebook

## Azure Cognitive Services
Train set of images and Integrate model as an API. Minimize effort.

## Azure Machine Learning Designer
One of Feature in Azure ML Notebook that facilitate user for drag and drop interface with pre-build custom components to create pipeline train and deploy model ML.

## Azure ML Python SDK v2
Authenticate to the workspace by using the Azure Machine Learning Python SDK v2 in Azure ML Notebooks setup lists:
"subscription_id": "<SUBSCRIPTION_ID>",
"resource_group": "<RESOURCE_GROUP>",
"workspace_name": "<AZUREML_WORKSPACE_NAME>"

## Create Compute Target using Azure CLI
This reference is part of the azure-cli-ml extension for the Azure CLI (version 2.0.28 or higher). 
The extension will automatically install the first time you run an 'az ml computetarget create' command. Learn more about extensions.

## Create Tabular assets for train model ML Notebook using Azure ML Python SDK v2
The path should be a folder that contains a valid MLTable file.
Configure a data asset that points to a local file to automatically upload to the default datastore.

## Create a datastore that has an existing Azure Storage account
Create an Azure Machine Learning datastore without cached credentials for the storage account. 
If a datastore has cached credentials, such as storage account key, those credentials are used instead of user identity.

## azureML
Protocol that can access the datastore from a notebook running in the workspace.


