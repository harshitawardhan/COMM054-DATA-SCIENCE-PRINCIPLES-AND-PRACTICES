# E. coli Protein Localisation Classification

**Overview**
This project involves building and evaluating machine learning models to predict the location of proteins within the bacterium Escherichia coli. The task is to classify proteins into one of two classes based on five features using Naïve Bayes and Logistic Regression models. The data for this project is sourced from the UCI Machine Learning Repository.

**Dataset**
The dataset contains 5 features (X1 to X5) that describe the properties of proteins in E. coli. The target variable (C) indicates the location of the proteins within the cell:
0: Inner membrane
1: Perisplasm

**Dataset File**
Filename: ecoli.csv
Source: UCI Machine Learning Repository
Each row corresponds to a single protein with its features and class label.

**Models Used**
Naïve Bayes Classifier
A probabilistic classifier based on applying Bayes’ theorem with strong (naïve) independence assumptions between the features.
Logistic Regression
A linear model used for binary classification that estimates the probability of a class label based on input features using the logistic function.

**Project Structure**
ecoli.csv: The dataset used for classification.
notebook.ipynb: Jupyter notebook containing the implementation of both Naïve Bayes and Logistic Regression models.

**Project Tasks**
Model Training: Train both Naïve Bayes and Logistic Regression models on the E. coli dataset.
Model Explanation: Provide a clear explanation of each model, including equations, inputs, and outputs.
Performance Comparison: Evaluate and compare the performance of both models using appropriate classification metrics.
Metrics Used:
Accuracy
Precision
Recall
F1-Score
Confusion Matrix

**Visualizations:** Produce plots to visualize model performance and comparisons.

**Results and Discussion**
Both models are trained and evaluated, and their performance is compared using metrics such as accuracy, precision, recall, and F1-score. The notebook includes a detailed discussion on the results obtained from each model and the interpretation of the metrics.
