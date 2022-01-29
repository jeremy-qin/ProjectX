# ProjectX
ProjectX Research Competition
Project Topic : Image Enhancement and Transfer Learning for Covid-19 Image Classification
# Datasets
We used two datasets for the project (COVID-CT and SARS-CoV-2). Both of them are available at the following links:
https://www.kaggle.com/plameneduardo/sarscov2-ctscan-dataset

https://github.com/UCSD-AI4H/COVID-CT
# Models and Code
This repository contains all the notebooks that were ran in Google Colab Pro for the project in the 'Models' folder. For each pretrained model, we have one notebook for each method (baseline, median blur and CLAHE) as well as one notebook per model that used K-fold Cross Validation for hypothesis testing. 
# Metrics and Results
Metrics and plots (confusion matrix, accuracy and loss plots, ...) for each baseline model are located in the 'Models Metrics' folder. The metrics and plots for the image enhancement techniques are stored in separate folders named 'Median blur' and 'CLAHE'. The folder 'K-folds' contain the classification reports of all methods and all models. A summary of all classification reports for each method and each model are also available in an Excel file in the 'Metrics summary' folder.
# Example of Notebooks
To see how we we did our project, we recommend to look at the 'VGG19_COV_Final.ipynb' notebook as it is the notebook with more comments. All other notebooks follow the same pattern, but with small changes which depends on the method used. 
