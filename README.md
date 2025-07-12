# Capstone Project – HR Analytics
This project focuses on analyzing and modeling an HR dataset to understand employee retention and performance patterns. The goal is to apply machine learning techniques to identify key factors influencing employee attrition and predict future trends.

### Dataset
The dataset used is HR_capstone_dataset.csv, which includes features related to:

1. Employee satisfaction
2. Evaluation scores
3. Project count
4. Average monthly hours
5. Work accidents
6. Time spent at the company
7. Promotion history
8. Department and salary

### Project Steps

1. Data Loading & Preprocessing
2. Handled missing values and basic cleanup
3. One-hot encoded categorical features
4. Exploratory Data Analysis (EDA)
5. Visualized correlations, feature distributions, and attrition patterns
6. Modeling
7. Built and evaluated multiple classifiers:
   Logistic Regression, 
   Decision Tree, 
   Random Forest, 
   XGBoost, 
8. Evaluation Metrics
   Accuracy, 
   F1-Score, 
   Precision, 
   Recall, 
   Confusion Matrix visualization
9. Model Tuning

10. GridSearchCV and PredefinedSplit used for hyperparameter optimization
11. Final Outputs
12. Best model selection
13. Feature importance analysis
14. Model saved using pickle

### Requirements
1. Python 3.x
2. Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost

### File Structure
Capstone.ipynb: Main notebook with all analysis
HR_capstone_dataset.csv: Input dataset 
