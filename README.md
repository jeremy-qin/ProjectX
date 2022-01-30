# ProjectX
ProjectX Research Competition
Project Topic : Image Enhancement and Transfer Learning for Covid-19 Image Classification
# Datasets
We used two datasets for the project (COVID-CT and SARS-CoV-2). Both of them are available at the following links:
https://www.kaggle.com/plameneduardo/sarscov2-ctscan-dataset

https://github.com/UCSD-AI4H/COVID-CT
# Dependencies
In the requirements.txt, we have a list of the dependencies used to run our experiments. However, note that our notebooks can simply be run in Google Colab (Pro). Many packages were already pre-installed in Colab such as Tensorflow, Numpy, Matplotlib and others.
# Models and Code
This repository contains all the notebooks that were ran in Google Colab Pro for the project in the 'Models' folder. For each pretrained model, we have one notebook for each method (baseline, median blur and CLAHE) as well as one notebook per model that used K-fold Cross Validation for hypothesis testing. 
# Pretrained Models
See links below for documentation on the pretrained models used:

VGG19 : https://keras.io/api/applications/vgg/#vgg19-function

ResNet50 : https://keras.io/api/applications/resnet/#resnet50-function

DenseNet121 : https://keras.io/api/applications/densenet/#densenet121-function
# Median Blur and CLAHE
Documentation and examples can be found at the following links:

Median Blur : https://docs.opencv.org/4.x/d4/d13/tutorial_py_filtering.html

CLAHE : https://docs.opencv.org/4.x/d5/daf/tutorial_py_histogram_equalization.html
# Metrics and Results
Metrics and plots (confusion matrix, accuracy and loss plots, ...) for each baseline model are located in the 'Models Metrics' folder. The metrics and plots for the image enhancement techniques are stored in separate folders named 'Median blur' and 'CLAHE'. The folder 'K-folds' contain the classification reports of all methods and all models. A summary of all classification reports for each method and each model are also available in an Excel file in the 'Metrics summary' folder.
# Example of Notebooks
To see how we we did our project, we recommend to look at the 'VGG19_COV_Final.ipynb' notebook as it is the notebook with more comments. All other notebooks follow the same pattern, but with small changes which depends on the method used. 
# References(Data)
Xingyi Yang et al. COVID-CT-Dataset: A CT Scan Dataset about COVID-19. 2020. arXiv: 2003.13865. URL: https://arxiv.org/abs/2003.13865

Soares, Eduardo, Angelov, Plamen, Biaso, Sarah, Higa Froes, Michele, and Kanda Abe, Daniel. "SARS-CoV-2 CT-scan dataset: A large dataset of real patients CT scans for SARS-CoV-2 identification." medRxiv (2020). doi: https://doi.org/10.1101/2020.04.24.20078584.
