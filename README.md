# Machine Learning - Training Projects

This repository contains two short machine learning projects I completed as part of my training.

---

## Glass Classification

This project addresses a classical problem of classifying unbalanced classes using the [Glass Identification dataset](https://archive.ics.uci.edu/dataset/42/glass+identification) from the UCI repository.

- **Exploratory Data Analysis (EDA):** I began by performing EDA to examine the data distribution and key statistics, as well as to check for duplicates or missing values. I visualized the data using pair plots, violin plots, and correlation matrices for better insight. You can view the EDA [here](https://github.com/MartFrancisco/ML-Training/blob/main/EDA.ipynb).
  
- **Modeling:** I built and tuned five classification models, comparing their performance before and after tuning using four key metrics: F1-score, recall, accuracy, and precision. You can explore the models and their results [here](https://github.com/MartFrancisco/ML-Training/blob/main/Models_glass_classification.ipynb).

---

## QSAR Androgen Receptor

In this project, I built machine learning models to predict whether molecules are active in an androgen receptor using the [QSAR Androgen Receptor dataset](https://archive.ics.uci.edu/dataset/509/qsar+androgen+receptor) from the UCI repository. The dataset includes 1,024 molecular fingerprint attributes for 1,687 molecules.

- **Objective:** The project focuses on understanding the impact of unbalanced data on model performance. I applied Support Vector Classifier (SVC) and Random Forest models on the original dataset, followed by re-training on a balanced dataset using SMOTE (Synthetic Minority Oversampling Technique).
  
- **Findings:** Balancing the dataset resulted in significant performance improvements across both models. The details of the models and their evaluation can be found [here](https://github.com/MartFrancisco/ML-Training/blob/main/QSAR_agonist_models.ipynb).
