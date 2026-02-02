📊 Estimation of Obesity Levels Using Classification Models (R)

📌 Project Overview

This project focuses on estimating obesity levels based on eating habits, lifestyle choices, and physical activity using classification techniques in R. The goal is to identify key factors influencing obesity and evaluate multiple machine learning models to determine the most effective approach.

The analysis was performed as part of the course Business Analytics with R (BUAN 6356) at The University of Texas at Dallas.

Problem Statement:

Obesity is a growing global health concern linked to chronic diseases such as diabetes and cardiovascular disorders. Using lifestyle and behavioral data, this project aims to classify individuals into:
	•	Overweight
	•	Non-Overweight
and determine which predictive model performs best.

📂 Dataset
	•	Source: UCI Machine Learning Repository
	•	Dataset Name: Estimation of Obesity Levels Based on Eating Habits and Physical Condition
	•	Link: https://archive.ics.uci.edu/dataset/544/estimation+of+obesity+levels+based+on+eating+habits+and+physical+condition
Due to licensing and academic guidelines, the dataset is not stored in this repository. Please download the dataset directly from the UCI repository using the link above.

🔧 Data Preprocessing
	•	Removed non-controllable attributes such as age, height, and weight to avoid bias
	•	Retained family history with overweight due to genetic relevance
	•	Converted 7 obesity categories into binary classification
	•	Performed scaling to handle class imbalance
	•	Conducted exploratory data analysis (EDA) and correlation analysis

📈 Models Implemented

The following classification models were developed and evaluated:
	•	Decision Tree (with post-pruning)
	•	Random Forest
	•	Boosted Tree (Adaboost)
	•	Logistic Regression (with backward elimination)
	•	Neural Network (two hidden layers)

🏆 Model Evaluation

Models were evaluated using:
	•	Accuracy
	•	Sensitivity & Specificity
	•	ROC Curve & AUC
Model                AUC
Boosted Tree        0.9313
Random Forest       0.9307
Decision Tree       0.8911
Neural Network      0.8678
Logistic Regression 0.8650

✅ Boosted Tree was identified as the best-performing model.

🔍 Key Insights
	•	Eating between meals and family history are strong predictors of obesity
	•	Lifestyle factors like physical activity, water intake, and screen time significantly influence outcomes
	•	Ensemble models outperform single classifiers for this dataset

🛠 Tools & Technologies
	•	R
	•	RStudio
	•	Libraries: rpart, randomForest, adabag, nnet, caret
	•	MS Word & PowerPoint (documentation)

Author:
Aparna Mishra MS Business Analytics and AI, UT Dallas
