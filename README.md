# Predict-Employee-Attrition-using-Advanced-Algorithms


**Data:** The dataset contains 34 input features, and 1 Target variable called Attrition, which has 2 classes. Therefore, it's an Classificaion problem, and our ML mdoel would be expected give probability of attrition for eacch employee based on different attributes such as Age, Gender, Education, EnvironmentSatisfaction, WorkLifeBalance, etc.

![Employee Attrition](https://github.com/Praveen76/Predict-Employee-Attrition-using-Advanced-Algorithms/blob/main/Employee%20Attrition.png)

This is a Classification problem. You can import dataset from the [following link](https://www.kaggle.com/datasets/patelprashant/employee-attrition)  to replicate the same results and follow along the experiement. We'll use XgBoost to solve this problem.

**Important learnings:**
* Handle imbalanced Dataset using SMOTE sampling method.
* Encode Categorical features
* Build CatBoostClassifier, LightGBM Classifier(LGBMClassifier), and XgBoost Classifier.
* Hyperparameter tuning to find the best hyperparameters for our model training.
