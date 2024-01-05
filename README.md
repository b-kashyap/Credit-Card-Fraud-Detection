# Credit-Card-Fraud-Detection
This project employs machine learning to spot credit card fraud in a dataset with valid and fraudulent transactions. It involves model exploration, data preprocessing, and feature engineering to build accurate classification models. Detailed documentation and insights aid understanding and further research in financial security.

![image](https://github.com/b-kashyap/Credit-Card-Fraud-Detection/assets/155677382/a11f62b9-e8cf-4f87-ae19-80dd2fbb1095)

## Dataset Overview:
The dataset is the Kaggle Credit Card Fraud Detection dataset found here-https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
It contains two-day transactions made on 09/2013 by European cardholders. The dataset contains 492 frauds out of 284,807 transactions. Thus, it is highly unbalanced. Data only contains numerical variables. Features V1, V2, … V28 are the principal components obtained with PCA transformation. The only features which have not been transformed are ‘Time’ and ‘Amount’. ‘Time’ is the seconds elapsed between each transaction and the first. ‘Amount’ is the transaction amount. ‘Class’ is the response variable with 1 as fraud and 0 otherwise.

## Technologies and Libraries used:
1.Pandas: For data manipulation and handling.<br>
2.Scikit-learn: For machine learning models, evaluation metrics, and data preprocessing.<br>
3.Matplotlib: For creating visualizations.<br>
4.Seaborn: Works with Matplotlib to provide high-level interface for drawing attractive and informative statistical graphics.<br>
5.NumPy: For mathematical operations and working with arrays.<br>
6.SciPy: Specifically, the stats module is used to compute the z-scores for outlier detection.<br>

## Model Evaluation
Given the class imbalance ratio, the accuracy is calculated using the Area Under the Precision-Recall Curve (AUPRC). (Confusion matrix accuracy is not meaningful for unbalanced classification)
### Precision Recall Curve for Logistic Regression
![image](https://github.com/b-kashyap/Credit-Card-Fraud-Detection/assets/155677382/393aa8a2-31ea-4500-bb56-15509bc6456b)

### Precision Recall Curve for Decision Tree
![image](https://github.com/b-kashyap/Credit-Card-Fraud-Detection/assets/155677382/13c940e3-6ee6-4d7e-97fd-05ea948b2e91)

### Precision Recall Curve for Random Forest
![image](https://github.com/b-kashyap/Credit-Card-Fraud-Detection/assets/155677382/218aa077-0c41-4bc0-8699-fbe30e362ffe)

### Precision Recall Curve for SVM
![image](https://github.com/b-kashyap/Credit-Card-Fraud-Detection/assets/155677382/3e019c5c-bfeb-4eeb-818e-7e98a6cb7d0a)

