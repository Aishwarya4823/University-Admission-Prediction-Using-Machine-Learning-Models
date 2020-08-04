# University Admission Prediction Using Machine Learning Models

In this repository, I have implemented various machine learning models that predict whether the probability of a student getting accepted into a University offering a Masters degree. Upon noting the validation accuracies on each of the model, I have selected the best of all on them and shown how the key performance indicators(KPIs) vary in their values.
<br>

 
# Data

The dataset contains several parameters which are considered important during the application for Masters Programs.
The parameters included are :<br>

1) GRE Scores ( out of 340 )<br>
2) TOEFL Scores ( out of 120 )<br>
3) University Rating ( out of 5 )<br>
4) Statement of Purpose and Letter of Recommendation Strength ( out of 5 )<br>
5) Undergraduate GPA ( out of 10 )<br>
6) Research Experience ( either 0 or 1 )<br>
7) Chance of Admit ( ranging from 0 to 1 )<br>

# Citation

Mohan S Acharya, Asfia Armaan, Aneeta S Antony : A Comparison of Regression Models for Prediction of Graduate Admissions, IEEE International Conference on Computational Intelligence in Data Science 2019

# Model
<br>
For this dataset, we tried the following four models with their accuracies listed as below <br>

|   Model                |Validation Accuracy|
|------------------------|-------------------|
|Linear Regression     |   0.822831       |
|Artificial Neural Networks(5-layers)       |   0.805562       |
|Decision Tree    |   0.460020       |
|Random Forest           |   0.797299       |
<br>
As we can see, the best model is our Multiple Linear Regression model with a validation accuracy of 0.822831
<br>

# Insights
<br>

1) The mean for the GRE scores is 316<br>
2) Mean for TOEFL score is 107<br>
3) Standard deviation for the GRE score is 11, which suggests that about 68% of the students scored between 305 and 327<br>
4) Average University Ranking is 3<br>
5) There is a very high correlation between GRE and TOEFL scores. A student who scores higher on GRE tends to score higher on their TOEFL exam<br>
6) The chance of admission acceptance increases as GPA, SOP and University Ranking improve/increase<br>
7) Students who have research experience in the past, tend to have a higher chance of getting into a University with a ranking of 3<br>

# Key Performance Indicators(KPIs)
<br>
In the following text, I have explained what role each KPI plays and what the value that we have got suggests about our best model(Multi-Linear Regression)

## Mean Absolute Error(MSE)
<br>





