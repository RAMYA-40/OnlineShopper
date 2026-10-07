# 🛒 Online Shoppers Purchasing Intention

## 📌 Project Overview

This project uses Machine Learning to predict whether an online shopping session will result in a purchase or not.

The project is based on the **Online Shoppers Purchasing Intention Dataset** from the UCI Machine Learning Repository. The target variable is **Revenue**, which indicates whether a purchase was made during the session.

## 📊 Dataset

- **Source:** UCI Machine Learning Repository
- **Dataset:** Online Shoppers Purchasing Intention Dataset
- **Dataset ID:** 468
- **Total Sessions:** 12,330
- **Input Features:** 17
- **Target Variable:** Revenue

### Target Variable

- `True` → Purchase made
- `False` → No purchase

## 🔍 Data Preprocessing

The following preprocessing steps were performed:

- Checked the dataset and data types
- Checked for missing values
- Applied Label Encoding and One-Hot Encoding
- Used **SMOTE** to handle class imbalance
- Applied **SelectKBest (k=10)** for feature selection
- Applied **StandardScaler** for feature scaling
- Split the dataset into **80% training and 20% testing**

## 🤖 Machine Learning Algorithms

The following algorithms were trained and compared:

1. Logistic Regression
2. Decision Tree
3. Random Forest
4. AdaBoost
5. Gradient Boosting

## 📈 Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score

## 🏆 Best Model

**Random Forest** achieved the best overall performance.

| Metric | Score |
|---|---:|
| Accuracy | 0.87 |
| Precision | 0.88 |
| Recall | 0.86 |
| F1-Score | 0.87 |

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Imbalanced-learn
- Jupyter Notebook

## 🎯 Conclusion

The project successfully predicts online shopping purchase outcomes using Machine Learning. Among the five models tested, **Random Forest** provided the best overall performance with an accuracy of **87%**.

## 👩‍💻 Author

**Ramya Balachandran**  
III BCA – B  
Shri Krishnaswamy College for Women
