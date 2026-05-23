# Basics of Machine Learning Algorithms

This repository contains a collection of beginner-to-intermediate machine learning notebooks covering core supervised and unsupervised learning algorithms using Python and scikit-learn.

The notebooks were developed as part of my early machine learning learning journey and practical exploration of foundational ML concepts. This repository is maintained as a structured archive of hands-on practice with common machine learning workflows.

## Repository Overview

This repository includes practical notebooks on:

- linear regression
- multivariate regression
- gradient descent
- model saving with Pickle and Joblib
- one-hot encoding and dummy variables
- train-test split
- logistic regression
- decision tree classifiers
- support vector machines
- random forests
- K-fold cross-validation
- K-means clustering
- Naive Bayes classifiers
- hyperparameter tuning with Grid Search and Randomized Search
- Lasso and Ridge regularization
- K-nearest neighbors
- principal component analysis
- bagging ensemble methods

## Learning Objectives

The main objectives of this repository are to:

- understand the basic workflow of machine learning model development
- practice data preprocessing and feature handling
- implement common supervised and unsupervised learning algorithms
- evaluate classification and regression models
- explore model selection and hyperparameter tuning
- understand dimensionality reduction and ensemble learning concepts

## Topics Covered

### Regression

The regression notebooks introduce simple and multivariate regression workflows using practical prediction examples.

Covered concepts include:

- simple linear regression
- multivariate linear regression
- gradient descent
- model fitting and prediction
- basic regression interpretation

### Data Preprocessing

The preprocessing notebooks cover important data preparation steps used in machine learning workflows.

Covered concepts include:

- one-hot encoding
- dummy variables
- handling categorical features
- train-test splitting
- preparing data for model training

### Classification

The classification notebooks introduce supervised learning algorithms for predicting categorical outcomes.

Covered algorithms include:

- logistic regression
- decision tree classifier
- support vector machine
- random forest
- Naive Bayes
- K-nearest neighbors

### Model Selection and Evaluation

The model selection notebooks introduce approaches for comparing and improving machine learning models.

Covered concepts include:

- K-fold cross-validation
- Grid Search
- Randomized Search
- model comparison
- hyperparameter tuning

### Unsupervised Learning

The unsupervised learning notebooks introduce methods for identifying structure in unlabeled data.

Covered concepts include:

- K-means clustering
- cluster assignment
- basic clustering interpretation

### Dimensionality Reduction and Ensembles

The later notebooks introduce additional machine learning concepts such as:

- principal component analysis
- Lasso regularization
- Ridge regularization
- bagging ensemble methods

## Repository Structure

```text
Basics_of_ML_Algorithms/
├── notebooks/
│   ├── 1_Canada's GDP Prediction Model.ipynb
│   ├── 2_Salary Prediction Model -- Multivariate Lin. Reg..ipynb
│   ├── 3_House Price Multivariate Model.ipynb
│   ├── 4_Salary Prediction Model -- Multivariate Lin. Reg..ipynb
│   ├── 5_Gradient Descent.ipynb
│   ├── 6_Pickle and Joblib_Saving Your Model.ipynb
│   ├── 7_One Hot Encoding_Dummy Variables.ipynb
│   ├── 8_Dummy Variables Exercise.ipynb
│   ├── 9_Intro To Train-Test Split Model.ipynb
│   ├── 10_Logistic Regression_Binary Classification.ipynb
│   ├── 11_HR Data Analysis.ipynb
│   ├── 12_Decision Tree Classifier.ipynb
│   ├── 13_Decision Tree Classifier-Sklearn Iris Data.ipynb
│   ├── 14_Support Vector Machine_Iris Data.ipynb
│   ├── 15_Support Vector Machine_Digits Data.ipynb
│   ├── 16_Random Forest_Digits Data.ipynb
│   ├── 17_Random Forest_Iris Data.ipynb
│   ├── 18_K Fold Cross Validation_Digits Data.ipynb
│   ├── 19_K Fold Cross Validation_Iris Data.ipynb
│   ├── 20_K Means Clustering Algorithm.ipynb
│   ├── 21_K Means Clustering II.ipynb
│   ├── 22_Naive Bayes I.ipynb
│   ├── 23_Naive Bayes II.ipynb
│   ├── 24_Naive Bayes III.ipynb
│   ├── 25_Use of Grid and Randomized Search I.ipynb
│   ├── 26_Grid Search II.ipynb
│   ├── 27_Lasso(L1) and Ridge(L2).ipynb
│   ├── 28_K Nearest Neighbor.ipynb
│   ├── 29_KNN Digit Exercise.ipynb
│   ├── 30_Principal Component Analysis.ipynb
│   ├── 31_PCA_Heart Model.ipynb
│   ├── 32_Bagging .ipynb
│   └── 33_Heart Model Using Bagging.ipynb
├── README.md
├── requirements.txt
├── .gitignore
└── LICENSE
```

## How to Use This Repository

Clone the repository:

```bash
git clone https://github.com/CodeeSam/Basics_of_ML_Algorithms.git
cd Basics_of_ML_Algorithms
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Open Jupyter Notebook:

```bash
jupyter notebook
```

Then open any notebook of interest.

## Requirements

The main Python packages used in these notebooks include:

```text
pandas
numpy
scikit-learn
matplotlib
seaborn
jupyter
```

## Suggested Learning Path

For beginners, the notebooks can be followed in this order:

1. Linear regression
2. Multivariate regression
3. Gradient descent
4. Model saving with Pickle and Joblib
5. One-hot encoding and dummy variables
6. Train-test split
7. Logistic regression
8. Decision trees
9. Support vector machines
10. Random forests
11. Cross-validation
12. K-means clustering
13. Naive Bayes
14. Grid Search and Randomized Search
15. Lasso and Ridge regularization
16. K-nearest neighbors
17. Principal component analysis
18. Bagging

## Project Note

This repository represents one of my earlier machine learning learning archives. It is not intended to be a production-level machine learning package. Instead, it documents my practical exploration of core ML algorithms and serves as evidence of my long-term development in applied machine learning.

## Limitations

Some limitations of this repository include:

- The notebooks are primarily educational and exploratory.
- The workflows are notebook-based rather than modular Python scripts.
- Some datasets are small demonstration datasets.
- The notebooks may not include advanced experiment tracking or production-level validation.
- The repository focuses mainly on classical machine learning algorithms.

## Future Improvements

Possible future improvements include:

- organizing notebooks into topic-based folders
- adding short explanations at the beginning of each notebook
- adding model evaluation summaries
- standardizing notebook naming conventions
- adding datasets into a dedicated `data/` folder where appropriate
- converting selected examples into reusable Python scripts

## Author
Credit @Codebasics; DavePatel
