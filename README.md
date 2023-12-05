# Machine-Learning-for-Liver-Disease-diagnosis-and-Prediction
## Overview of the Project
Liver disease is one of the most fatal
diseases around the world and with this
project we are trying to build a prediction
system which uses machine learning to
analyze the dataset fed into it and come up
with the accuracy at which the ML model
will be able to predict if a person will get
liver disease or not. The goal of this project
is to compare such ML models so as to find
the best fit for predicting liver disease based
on some parameterslike accuracy. We will
be comparing five machine learning models
namely random forest, gradient boosting,
Adaboost classifier, random search CV and
grid search CV.
# Methodology 
## Data Acquisition - Phase-1
The liver Disease Dataset is collected from the UCI Machine Learning Repository The Link for the Dataset is Given Below. This dataset contains 11
attributes and 584 rows of data. The
attributes include patient’s age, gender, total
bilirubin, direct bilirubin, alkaline
phosphate, alamine aminotransferase,
aspartate aminotransferase, total proteins,
albumin and albumin globulin ratio.
https://archive.ics.uci.edu/dataset/225/ilpd+indian+liver+patient+dataset
## Data Preprocessing And EDA - Phase-2
In phase 2 of our Liver disease prediction project, we'll tackle data preprocessing and exploratory data analysis (EDA) to refine our model. We'll begin by addressing missing values using a suitable imputation technique. Next, we'll analyze feature correlations to identify redundant or irrelevant factors. To handle potential class imbalance in our training data, we'll employ SMOTE (Synthetic Minority Oversampling Technique) to create synthetic samples for the underrepresented class. For further dimensionality reduction and feature selection, we'll leverage PCA (Principal Component Analysis) to retain the most informative features. Finally, we'll standardize our data using sklearn's StandardScaler to ensure all features are on equal footing before feeding them to our machine learning models. This comprehensive data preparation process will ensure our model learns from the most relevant information, leading to more accurate and reliable predictions.
## Training and Evaluation of Models - Phase-3
Phase 3 of our project dives into model training and evaluation. We'll be putting five machine learning models to the test: Random Forest, Gradient Boosting, Adaboost Classifier, Randomized Search CV, and Grid Search CV. Our goal is to identify the champion model with the highest accuracy in predicting liver disease. Each model will be trained on our prepped data, and their performance will be rigorously evaluated using relevant metrics like accuracy, precision, recall, and F1 score. We'll carefully analyze the strengths and weaknesses of each model, comparing their ability to generalize and handle complex relationships within the data. Ultimately, this phase will reveal the best-suited model for our liver disease prediction task, paving the way for reliable and impactful diagnoses.
# System Architechture.


