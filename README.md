# Prediction-of-Odor-Using-Machine-Learning
# Introduction
In the chemical realm, machine learning and data analytics are rapidly being employed for quantitative structure property relation (QSPR) applications. One such application is the perception of odorant stimuli, as olfaction is the least worked among all other senses in the prediction domain. The usefulness of employing a data-driven strategy to predict the perceptual qualities of an odorant, specifically the odorant characters, is investigated in this work using machine learning-based algorithms and data analytics. We first analyze a Odor dataset. which is a repository of odor name, smiles, primary and secondary odor. We next utilize the data to train multiple machine learning algorithms for olfactory character prediction, including random forest, decision tree, XGBoost, and K-nearest-neighbors, and provide the structural elements that correlate well with the odor based on the best model. Furthermore, we investigate the influence of data quality on model performance by comparing the semantic descriptors often associated with a certain odorant to how the majority of the participants perceive it. The research gives a framework for constructing odor perception models, as well as insights into odor perception and the impact of inherent bias in perception data on model performance. The algorithms and techniques described here might be utilized to anticipate novel odorant odor characteristics. In this paper , we describe a model that combines data preprocessing and scaling approaches to clean the dataset, then different classifiers are applied to the dataset and we obtained the highest accuracy of 97.01% using a random forest classifier on the test data.
# Documentation
One can find out more about the machine learning algorithms used to Prediction-of-Odor-Using-Machine-Learning in the Odor_prediction_Project_Report.pdf and our web application can be found at Web Application.rar
# Dataset Description
We have worked on the Odor Dataset which we have obtained from the Olfaction base section of IIIT Allahabad. The dataset consists of 3686 unique molecule information, this dataset contains 5 attributes namely Primary Odor, Sub-Odor, CAS-id, chemical name and smiles. 
# Installation of Prediction Model
# Prerequisite
One needs Python 3.6 with standard libraries such as pandas, matplotlib, seaborn, numpy,sklearn and imblearn.
# Steps to run the code
1) Download the code using Odor_prediction_NormalClassifiers_on_full_dataset.ipynb
2) Downlaod the dataset 1800Finaldescriptors4.csv
3) You can run the code in your local machine having python 3.6 and libraries or you can use the Google Collab for running code without any difficulty.


