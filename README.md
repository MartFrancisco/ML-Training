## Machine Learning - Training

#### There are two short projects I used to train. 
---
### Glass Classification

The first one is a classical problem of classification of unbalanced classes.
Here, I used the glass dataset [Available at the UCI repository](https://archive.ics.uci.edu/dataset/42/glass+identification).

In this problem, I started with some techniques of exploratory data analysis. The purpose was to check the data distribution and statistics. Check duplicates or null values.
I also plotted some graphs for better visualization (pair plot, violin graph, correlation) [you can see here the EDA](https://github.com/MartFrancisco/ML-Training/blob/main/exploratory%20data%20analysis.ipynb)

Five models were generated and then evaluated and tuned. Four performance indicators were computed for each model, before and after tunning (F1, recall, accuracy, and precision).
[Check here](https://github.com/MartFrancisco/ML-Training/blob/main/Models.ipynb).



### QSAR androgen receptor

It is a project to build classification machine learning models to predict if molecules are active or not in a receptor.
Check the dataset at [UCI - QSAR androgen receptor](https://archive.ics.uci.edu/dataset/509/qsar+androgen+receptor). It contains 1024 attributes (molecular fingerprints) and 1687 instances (molecules).

I used this project to study the effect of unbalanced data on the models. Support Vector Classifier and Random Forest were employed for the original dataset and then evaluated. In the second step, the classes were balanced using SMOTE (Synthetic Minority Oversampling Technique), and both machine learning algorithms were again employed to check the possible implications.

It is possible to observe that by treating the unbalanced characteristic of the data set, the models have a significant increase in the performance measurements. You can check the project [here](https://github.com/MartFrancisco/ML-Training/blob/main/QSAR%20agonist.ipynb)
