# Credit Card Fraud Detection using Decision Tree and Random Forest

## 📌 Project Overview
This project focuses on detecting fraudulent credit card transactions using Machine Learning techniques.  
The main objective of this project is to compare the performance of **Decision Tree** and **Random Forest** algorithms for fraud detection.

---

# ❓ Business Problem
Banks and financial institutions lose millions of dollars because of fraudulent credit card transactions.

Traditional systems often fail to detect fraud accurately because fraudulent transactions are very rare compared to legitimate transactions.

## 🎯 Problem Statement
> How can Machine Learning help detect fraudulent credit card transactions accurately while reducing false predictions?

---

# 🚀 Project Objectives
- Perform data preprocessing
- Analyze fraud patterns
- Handle imbalanced data
- Build Machine Learning models
- Compare Decision Tree and Random Forest
- Evaluate model performance
- Identify important fraud detection features

---

# 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# 📂 Dataset Information

The dataset contains credit card transaction records.

## Target Variable
- `0` → Non-Fraud Transaction
- `1` → Fraud Transaction

## Dataset Source
[Kaggle Credit Card Fraud Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
Data set is too big so u can download it from here i can't able to upload it because its size is 143 and github upload only 25mb
---

# 📊 Exploratory Data Analysis (EDA)

# Step 1: Import Required Libraries

## 🔍 What We Did
Imported all required libraries for:
- Data analysis
- Data visualization
- Machine Learning
- Model evaluation

## 💡 Insight
Libraries create the foundation for the complete Machine Learning workflow.

---

# Step 2: Load Dataset

## 🔍 What We Did
Loaded the dataset into a Pandas DataFrame.

## 💡 Insight
This step helps understand:
- Dataset structure
- Features
- Fraud labels
- Data dimensions

---

# Step 3: Dataset Information

## 🔍 What We Did
Used:
```python
df.info()
```

## 💡 Insight
This helps identify:
- Data types
- Null values
- Dataset size
- Memory usage

## ✅ What We Learned
The dataset mostly contains numerical features and is suitable for Machine Learning.

---

# Step 4: Statistical Summary

## 🔍 What We Did
Used:
```python
df.describe()
```

## 💡 Insight
Statistical summaries help understand:
- Mean
- Standard deviation
- Minimum values
- Maximum values
- Data spread

## ✅ What We Learned
Some features show large variation, indicating scaling differences and possible outliers.

---

# Step 5: Missing Value Analysis

## 🔍 What We Did
Checked null values in the dataset.

## 💡 Insight
Machine Learning models require clean and consistent data.

## ✅ What We Learned
The dataset does not contain major missing value issues.

---

# 📈 Data Visualization

# 1️⃣ Fraud vs Non-Fraud Distribution

![Fraud Distribution](https://github.com/LuckySingh0297/Decision-Tree-and-Random-Forest-project/tree/main/Images)

## 🔍 Why We Performed This
To understand whether the dataset is balanced or imbalanced.

## 💡 Insight
The dataset is highly imbalanced because fraudulent transactions are very rare.

## ✅ What We Learned
Accuracy alone is not enough for fraud detection problems.  
Metrics like:
- Precision
- Recall
- F1-Score
become very important.

---

# 2️⃣ Transaction Amount Distribution

![Transaction Amount Distribution](https://github.com/LuckySingh0297/Decision-Tree-and-Random-Forest-project/tree/main/Images)

## 🔍 Why We Performed This
To analyze transaction amount patterns.

## 💡 Insight
Most transactions are concentrated in lower ranges while high-value transactions occur less frequently.

## ✅ What We Learned
Unusual transaction amounts may indicate suspicious activities.

---

# 3️⃣ Correlation Heatmap

![Correlation Heatmap](https://github.com/LuckySingh0297/Decision-Tree-and-Random-Forest-project/tree/main/Images)

## 🔍 Why We Performed This
To identify relationships between variables.

## 💡 Insight
Correlation analysis helps:
- Detect feature relationships
- Identify hidden patterns
- Understand feature interactions

## ✅ What We Learned
Some features strongly influence fraud prediction.

---

# 🤖 Machine Learning Workflow

# Step 6: Feature and Target Separation

## 🔍 What We Did
Separated:
- Features → `X`
- Target → `y`

## 💡 Insight
This step prepares the dataset for Machine Learning model training.

---

# Step 7: Train-Test Split

## 🔍 What We Did
Split the dataset into:
- Training data
- Testing data

## 💡 Insight
This helps evaluate model performance on unseen data.

## ✅ What We Learned
Proper train-test splitting helps reduce overfitting.

---

# 🌳 Decision Tree Model

## 🔍 Why Decision Tree?
Decision Trees are:
- Easy to understand
- Fast to train
- Good for classification tasks

## 🔍 What We Did
- Trained Decision Tree model
- Generated predictions
- Evaluated model performance

## 💡 Insight
Decision Trees create rule-based splits to classify transactions.

## ✅ Result
The model successfully classified fraudulent and non-fraudulent transactions.

---

# 🌲 Random Forest Model

## 🔍 Why Random Forest?
Random Forest combines multiple decision trees to improve:
- Accuracy
- Stability
- Generalization

## 🔍 What We Did
- Trained Random Forest model
- Generated predictions
- Evaluated performance metrics

## 💡 Insight
Random Forest reduces overfitting and performs better on complex datasets.

## ✅ What We Learned
Random Forest achieved better performance compared to Decision Tree.

---

# 📉 Confusion Matrix Analysis

![Confusion Matrix](https://github.com/LuckySingh0297/Decision-Tree-and-Random-Forest-project/tree/main/Images)

## 🔍 Why We Performed This
To evaluate:
- Correct predictions
- Incorrect predictions
- Fraud detection capability

## 💡 Insight
Confusion Matrix is one of the most important evaluation tools in fraud detection systems.

## ✅ What We Learned
The model correctly identified most legitimate transactions while effectively detecting fraudulent activities.

---

# 📌 Feature Importance Analysis

![Feature Importance](https://github.com/LuckySingh0297/Decision-Tree-and-Random-Forest-project/tree/main/Images)

## 🔍 Why We Performed This
To identify the most important variables affecting fraud prediction.

## 💡 Insight
Feature Importance improves:
- Model explainability
- Business understanding
- Trust in Machine Learning systems

## ✅ What We Learned
Some variables contribute significantly more to fraud detection.

---

# ✅ Final Conclusion

## 📌 Project Summary
In this project:
- Data preprocessing was performed
- EDA was completed
- Multiple visualizations were created
- Decision Tree and Random Forest models were trained
- Fraud detection performance was evaluated

---

# 📊 Final Observation
Random Forest performed better because:
- It combines multiple decision trees
- Reduces overfitting
- Improves prediction accuracy

---

# 💼 Business Impact
This project demonstrates how Machine Learning can help financial institutions:
- Detect fraudulent transactions
- Reduce financial losses
- Improve customer trust
- Strengthen banking security systems

---

# 🚀 Future Improvements
- Hyperparameter tuning
- SMOTE for imbalance handling
- XGBoost implementation
- Real-time fraud detection system
- Streamlit deployment

---

# 👨‍💻 Author
## Lucky Singh

Aspiring Data Scientist passionate about:
- Machine Learning
- Data Analytics
- Artificial Intelligence
- Real-world business problem solving
