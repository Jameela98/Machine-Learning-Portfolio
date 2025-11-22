# Support Vector Machines Project: Iris Flower Classification

This repository contains a machine learning project using Support Vector Machines (SVM) to classify Iris flower species, I completed it as part of my machine learning learning journey. The project explain various data science techniques to build and evaluate classification models on a classic dataset.

##  Project Overview
This project explain the implementation and application of Support Vector Machines (SVM) for classification using the famous Iris flower dataset. The notebook explores how SVMs can effectively classify different species of Iris flowers based on their sepal and petal measurements.

The goal is to practice and demonstrate:

- Data exploration and visualization of features

- Data preprocessing

- Support Vector Machine application 

- Model evaluation and performance metrics

- Gridsearch Practice (GridSearchCV)

## Dataset Information
The project uses the Iris flower dataset, a classic multivariate dataset introduced by Sir Ronald Fisher in 1936. The dataset contains:

- 150 total samples (50 from each of 3 Iris species)

- 3 species: Iris setosa, Iris virginica, and Iris versicolor
- 4 features measured for each sample:
  Sepal length (cm)
  Sepal width (cm)
  Petal length (cm)
  Petal width (cm)

## Project Structure
The notebook covers the following key areas:

1) Data Loading & Exploration

  - Loading the Iris dataset
  - Basic data exploration and visualization
  - Understanding the distribution of features across different species

2) Data Preprocessing
   - Data cleaning and preparation
   - Train-test split for model validation

3) Support Vector Machine Implementation
   - Building SVM classifiers
   - Model training and evaluation

4) Model Evaluation
   - Performance metrics analysis :Accuracy, Precision, Recall, F1-score
   - Confusion matrix visualization
5) Gridsearch Practice
 GridSearchCV Implementation: Systematically searched for optimal hyperparameters

 Parameter Grid: Tested combinations of:
 
 - C values: [0.1, 1, 10, 100] - Regularization parameter

 - gamma values: [1, 0.1, 0.01, 0.001] - Kernel coefficient

 - Comprehensive Search: Evaluated 16 parameter combinations with 5-fold cross-validation (80 total model fits)

 - Optimal Parameters: Identified best performing C and gamma values for the SVM model  


## 🛠 Tools Used

- **Python 3.x** 
- **Jupyter Notebook** Interactive development environment
- **scikit-learn** Machine learning library
- **pandas & numpy** Data manipulation and analysis
- **matplotlib & seaborn** Data visualization
- **Iris Dataset** Classic multivariate dataset
  
##  Files in This Repository

- `J02-Support Vector Machines Project.ipynb` - Main Jupyter notebook containing complete analysis
- `iris` - Dataset
- `README.md` - Project documentation
