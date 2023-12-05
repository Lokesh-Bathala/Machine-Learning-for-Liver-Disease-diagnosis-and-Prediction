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
# Technologies Used 
-Python 
-Machine Learning
-Pandas
-Numpy
-Scikit-learn
-Flask
-HTML
-CSS
-Pickle
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
In phase 2 of our Liver disease prediction project, we'll tackle data preprocessing and exploratory data analysis (EDA) to refine our model. We'll begin by addressing missing values using a suitable imputation technique. Next, we'll analyze feature correlations to identify redundant or irrelevant factors. To handle potential class imbalance in our training data, we'll employ SMOTE (Synthetic Minority Oversampling Technique) to create synthetic samples for the underrepresented class. For further dimensionality reduction and feature selection, we'll leverage PCA (Principal Component Analysis) to retain the most informative features. Finally, we'll standardize our data using sklearn's StandardScaler to ensure all features are on equal footing before feeding them to our machine learning models. This comprehensive data preparation process will ensure our model learns from the most relevant information, leading to more accurate and reliable predictions. You can find this Phase-2 of the project in the [Liver.ipynb] file which was Uploaded Above.
## Training and Evaluation of Models - Phase-3
Phase 3 unleashes five machine learning gladiators (Random Forest, Gradient Boosting, Adaboost Classifier, Randomized Search CV, and Grid Search CV) to battle for liver disease prediction supremacy! We'll feed them our prepped training data (X samples, Y features) and watch them fight it out. Each model will be meticulously trained, their strengths and weaknesses dissected through rigorous evaluation with accuracy, precision, recall, and F1 score as weapons. We'll be on the lookout for the champion, the model that not only boasts high accuracy but also shines with a gleaming F1 score and that can be shown in the[liver.py] file. This ultimate victor will be immortalized in a PKL file [Liver.pkl], ready to serve as the foundation for reliable and impactful diagnoses in the future.
# System Architechture.
![WhatsApp Image 2023-12-04 at 21 18 03_38abe5e9](https://github.com/Lokesh-Bathala/Machine-Learning-for-Liver-Disease-diagnosis-and-Prediction/assets/152923362/480b8e87-ab7e-4e12-a7a9-56b4a16b12b7)
# Results and Conclusion
This project tackled the challenge of predicting liver disease in patients. We meticulously cleansed the data, imputing missing values, applying dummy encoding, and eliminating outliers to ensure optimal model performance.
We then unleashed a battery of classification algorithms: Random Forest Search, AdaBoost Classifier, Random Search CV, Grid Seach CV and Gradient Boosting. In this epic battle for accuracy, Random Forest emerged as the champion! Its impressive performance, surpassing all other contenders, solidified it as the ideal weapon for predicting liver disease.
And the best part? Our champion model boasts a staggering 85% accuracy! This not only surpasses other liver disease prediction projects but also signifies a significant leap forward in reliable diagnoses.
So, to conclude, this project successfully identified and employed the most potent weapon in the fight against liver disease: the mighty Random Forest algorithm. With its remarkable accuracy, we've opened a new chapter in reliable and potentially life-saving diagnoses. The Accuracy of the random Search algorithm is Given Below for the reference.

![WhatsApp Image 2023-12-04 at 21 51 11_54a3155b](https://github.com/Lokesh-Bathala/Machine-Learning-for-Liver-Disease-diagnosis-and-Prediction/assets/152923362/dec8dfb4-57ee-4b05-816d-910f81b7301a)
# Web application Associated with our Project
Patients now have the power to actively participate in their health journey! We've designed a user-friendly web application[Web App.py], crafted with HTML[index.html,result.html], that integrates seamlessly with our powerful AI model. Simply enter your blood test values, and our model, trained on vast medical data, springs into action. With a click, it unveils a personalized prediction of potential liver disease, empowering you to take control of your health. No more waiting for appointments or deciphering medical jargon - this interactive platform puts the power of prediction directly in your hands. It's a seamless blend of technology and patient empowerment, offering clear, actionable insights to guide your health decisions.
# Running Tests 
To run the Web application, use the following command

'Python app.py'

Our user-friendly web application seamlessly integrates with our powerful AI model, empowering you to take charge of your health. Simply launch the application by running the command python app.py in your terminal. Your web browser will guide you to the application's interface, where you'll effortlessly enter your blood test values. Once you've submitted the information, our AI model springs into action, analyzing your data with the expertise of vast medical knowledge. With a click, you'll receive a personalized prediction of potential liver disease, putting you back in control of your health decisions. No more navigating complex medical jargon or waiting for appointments – our interactive platform places the power of prediction directly in your hands. Embark on a journey of personalized health insights with our groundbreaking web application, where technology and patient empowerment converge.



# Demo 
<img src="https://raw.githubusercontent.com/SagarDhandare/Liver-Disease-Prediction-Project/main/Images/gif.gif">
<img src="https://raw.githubusercontent.com/SagarDhandare/Liver-Disease-Prediction-Project/main/Images/gif1.gif">


# Thank you...!




