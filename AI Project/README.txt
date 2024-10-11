Predicting water level fluctuations for Urban Water systems


ReadMe Overview

This Jupyter notebook demonstrates the process of predicting water level fluctuations using deep learning models, specifically Multi-Layer Perceptron (MLP) and Graph Convolutional Network (GCN). The models are implemented using PyTorch and PyTorch Geometric.

Follow these steps to set up and run the Water Level Fluctuations Prediction project:

Ensure you have one of the following environments set up for executing Python code:

Google Colab
Visual Studio Code with Jupyter extension
Jupyter Notebook

Step 1: Accessing the Code
Open the project code in your chosen development environment. If you are using Google Colab, you can directly open the notebook using the link provided in the project repository.

Step 2: Data Files Preparation
The necessary data file, WW01_v3.xls, is required for running the project. Obtain this file from the shared Google Drive folder:
https://drive.google.com/drive/folders/1OKlj1qXB7vcmWLTmiBjYDVZ5PBfocxGP
Please ensure that the WW01_v3.xls file is present within the WW01_v3 folder before proceeding.

Step 3: Running the Code
In your development environment, locate the Runtime button or equivalent command to execute the code.

Step 4: Execute the Code
Click on the Run all option from the dropdown menu or execute the cells manually in sequence to start the execution process of the entire notebook.

Step 5: Viewing the Output
Upon successful execution, the output, including the prediction results and any visualizations, will be displayed within the notebook interface.

Prerequisites
* Python 3.x
* PyTorch
* PyTorch Geometric
* Pandas
* NumPy
* Matplotlib
* scikit-learn




Dataset
The dataset used in this project should be in Excel format containing time series data of water levels. Ensure that the target variable is specified correctly in the script.
Features
* Data loading and preprocessing to incorporate time-lagged features for time series analysis.
* Splitting the dataset into training and test sets.
* Normalization of features to standardize the data input to the models.
* Implementation and training of MLP and GCN models.
* Evaluation of models using MAE and RMSE metrics.


Usage
* Update the data_path and target_column variables in the script to point to your data file and specify the correct target variable.
* Run the notebook cells sequentially to preprocess the data, train the models, and evaluate their performance.


Model Descriptions
* MLP (Multi-Layer Perceptron): A basic neural network model with fully connected layers, suitable for regression tasks.
* GCN (Graph Convolutional Network): An advanced model that leverages the structure of graph data for making predictions.


Results
Running the notebook will output the training loss graph and the prediction accuracy in terms of MAE and RMSE on the test set.