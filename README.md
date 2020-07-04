# Predicting the Outcomes of COVID-19 Patients using ML Models
Group members: Duc Le, Matthew Nwerem &amp; Riley Kendall.

# Abstract
The following model uses various types of Machine Learning algorithms to predict the outcome of patients diagnosed with COVID-19. The algorithms tested on this data set include Logistic Regression, Random Forest Classifier, AdaBoost Classifier and Naive Bayes. The end goal is to accurately predict the outcome of any given patient given certain features such as age, gender, chronic disease history (Y/N) and country of the case indentified. The patient can be classified as recovered or non-recovered (deceased or in critical condition). The modell will also provide each patient with the probability of their recovery.

# Data
The data set is acquired from nCov2019. The pre-processed data set consists of over 470,000 samples and over 20 columns. Our processed & filtered data set is reduced to roughly 700 samples due to the incompleteness of the original data set.

Source: https://raw.githubusercontent.com/beoutbreakprepared/nCoV2019/master/latest_data/latestdata.csv

# Description
Main assumptions:

Intended: the outcome associated with an age range regresses towards the mean of that age range.
Implicit: the dataset is correctly and reliably reported by credible sources.  Also, critical condition suggests not recovering


The model first begins with the pre-processing steps. Further details are attached in the Jupyter notebook. After cleaning, we are interested in gathering insights by visualizing our data set with all features, as well as plotting each individual feature against one another. 

Post-visualization is the testings of different ML models. The models attempted are Logistic Regression, RF Classifier, AdaBoost and Naive Bayes. ROC curves, AUC, accuracy & Confusion Matrices are the decided metrics on our results. After juxtaposing the results and their metrics, we decided to move forward with Random Forest and Logistic Regression as our final algorithms for this particular classification problem. 

For further commentary and explanation, please read the attached report (PDF).
