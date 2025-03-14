# Predict-the-quality-of-wine
This repository contains an in-depth analysis of red wine quality prediction using Machine Learning (ML) techniques, including Linear Regression, Decision Trees, and Random Forest. The project explores the relationship between the chemical composition of wine and its quality rating, based on a dataset from Kaggle.
📄 Report (Predict-the-quality-of-wine report.pdf) – Detailed research on the dataset, ML models, and findings.
📊 Presentation (Predict the quality of wine presentation.pptx) – Slides summarizing the project and results.
📜 R Markdown (Predict_the_quality_of_red_wine.Rmd) – Code and implementation details using R for data preprocessing and model building.
🎯 Project Objective
The goal of this project is to:

Analyze the chemical properties of red wine and their impact on wine quality.
Apply Machine Learning models to predict wine quality based on physicochemical tests.
Compare the performance of Regression and Classification models.
🔬 Data & Features
The dataset consists of 1,599 samples of red wine with 11 chemical attributes, such as:

Fixed Acidity
Volatile Acidity
Citric Acid
Residual Sugar
Chlorides
Free & Total Sulfur Dioxide
Density
pH
Sulphates
Alcohol
Quality (Target Variable: 0-10 scale)
📊 Key Observations:

Alcohol, Citric Acid, and Sulphates positively influence wine quality.
Volatile Acidity, pH, and Density have a negative correlation with quality.
The dataset is imbalanced, with most wines rated 5 or 6.
🏆 Models Used & Performance
The following models were implemented and evaluated:

✅ Linear Regression

R² Score: 44.59%
Identifies key chemical factors affecting quality but lacks predictive power.
✅ Decision Tree

Accuracy: 75.00%
Easy to interpret but prone to overfitting.
✅ Random Forest (Best Model)

Classification Accuracy: 83.12%
Regression R² Score: 47.49%
Best performer due to its ensemble nature and ability to capture complex patterns.
📈 Key Takeaways:

Random Forest outperforms all models, achieving the highest accuracy.
Alcohol & Sulphates are the strongest predictors of wine quality.
Data imbalance affects model performance, indicating potential for improvement.
🚀 Future Improvements
📌 Balance dataset (resampling techniques to handle class imbalance).
📌 Feature Engineering (create new meaningful predictors).
📌 Hyperparameter tuning (optimize model performance further).
📌 Deep Learning (explore neural networks for enhanced accuracy).

