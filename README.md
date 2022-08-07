# ML-Project-Campus-Recruitment
## About Dataset

This data set consists of Placement data of students in a XYZ campus. It includes secondary and higher secondary school percentage and specialization. It also includes degree specialization, type and Work experience and salary offers to the placed students

This dataset is available in kaggle at: https://www.kaggle.com/datasets/benroshan/factors-affecting-campus-placement

This dataset mainly aims to answer the following questions-
Which factor influenced a candidate in getting placed?
Does percentage matters for one to get placed?
Which degree specialization is much demanded by corporate?


## About Model

### Preprocessing-
To analyse the data first various plots have been made to get the understanding of the data. Then EDA has been done on the data including steps like outlier deleteion, skewness correction, MinMax scaling, label encoding and one-hot encoding.

### Feature Enginering-
Combined results of Chi-square, Anova and mutual information test if used to determine the best set of features.

### Model-
The data analysis mainly aims to estimate Salary and Placement status using other features to answer the questions described above. To do that we use two types of model, one to predict Salary which is an continous variable so we have used various Regression models and to determine Placement status, which is an classification problem we have used various classification model.

All the model are compared with best results being-
Salary prediction- 28.4% accuracy (Linear regression)
Placement status- 82.75% accuracy (Support Vector Machine)
