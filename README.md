# Everlytics
ML Test

## Objective: 
Build a model that predicts/classifies whether a website is a Phishing website.
Input Data
https://drive.google.com/open?id=1INjk9MQ-CiPlFzp2UA2Gr8yX2F_kR2xy8UQhWWcyQsI

Variable count: 31
Record count: 2456

## Data Definition
https://docs.google.com/document/d/1rdp7mAQhZ4OjJV2yiMsmohPRAc-oTHWIOTBMMs_Ahzc/edit?usp=sharing

Column name of the target variable: Result
Output
Please document your results in the Readme file of a GitHub repo by keeping in mind the following guidelines:
Justifications of selected approach, tools and techniques
Visualizations if necessary (you can keep them as part of the Jupyter Notebook)

## Evaluation Criteria: 
By observing the given dataset we can clearly tell that it is a supervised machine learning task. If we observe the result, it shows there is 1/0 and it comes under the classification problem.

## Approach: 
Loading the Dataset, 
Data Visualization, Data Pre-Processing, 
Model implementation using various Supervised Machine Learning Techniques and Finding the accuracy for testing,training data.

## Tools and Techniques used: 
numPy, pandas, matplotlib.pyplot, seaborn used for data visualization and pre-processing. Scikit learn, XGBoost for implementing the different Supervised Machine learning Classifiers(Random fofrest, Support Vector Machine, Decision Tree, XGBoost)

## Accuracy of the model: 
After implementation and comparision of different models, it is observed that XGBoost Model performs better Accuracy than other Models.
