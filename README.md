# Predicting Heart Health


## Background
The aim of my project is to uncover symptom patterns in heart disease. I'll examine the features that are most predictive of heart health and put people at most risk of heart disease.

In this project, I used Cryptocurrency data. After normalizing the data, I found the optimal k value by plotting them against inertia values in an elbow plot. I used the optimal k value to make a K-means model and predict clusters to group the Cryptocurrencies. Then I performed a Principal Component Analysis on the original data, and I found the optimal k value for the PCA data. With the PCA data's k value, I created another K-Means model. After comparing the results of each method, I concluded that having less features resulted in a clearer prediction. 

## Features 
* Preprocess the data to clean it up for Neural Network
* Create a Deep Learning Model with Tensor Flow
* Create a decision tree to find the most important features
* Create a Bar Chart with Decision Tree Feature Importance

## Installation
1. Clone repository
2. Install sklearn
3. Install Matplotlib and Pandas
4. Install Tensor Flow
5. Analyze and visualize data in Jupyter Notebook

## Built with
* Python
* Hvplot
* JupyterNotebook
* Sklearn
* TensorFlow
* MatPlotlib
* Pandas

## Sources
* https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease/
* https://www.cdc.gov/brfss/data_documentation/index.htm
