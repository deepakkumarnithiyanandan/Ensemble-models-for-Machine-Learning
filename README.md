# 🤖 Ensemble Models for Machine Learning  

## 📌 Overview  
This project explores **Ensemble Learning**, combining multiple models to improve prediction accuracy. We implemented and compared various **ensemble methods** such as **Bagging, Boosting, and Stacking** to evaluate their performance on a dataset.  

## 🚀 Features  
- ✅ **Bagging (Bootstrap Aggregating)**: Reduces variance by training multiple models on different data subsets.  
- ✅ **Boosting**: Corrects previous mistakes by assigning higher weights to misclassified samples.  
- ✅ **Stacking**: Combines multiple base models with a meta-learner for improved accuracy.  
- ✅ **Performance Evaluation**: Benchmarks models using metrics like **accuracy, precision, recall, and F1-score**.  

## 🏗️ How It Works  
### **1️⃣ Data Preprocessing**  
- Cleaned and normalized the dataset.  
- Handled missing values and performed feature engineering.  

### **2️⃣ Implemented Ensemble Models**  
- **Bagging**: Used **Random Forest** and **BaggingClassifier** to reduce variance.  
- **Boosting**: Implemented **AdaBoost, Gradient Boosting, and XGBoost** to enhance weak learners.  
- **Stacking**: Combined **multiple classifiers** (e.g., Decision Tree, Logistic Regression, SVM) with a **meta-learner**.  

### **3️⃣ Model Evaluation**  
- Compared models using metrics:  
  - 🎯 **Accuracy**  
  - 📊 **Precision, Recall, F1-score**  
  - 📉 **ROC-AUC Curve**  

## 📊 Performance Comparison  
- **Boosting models (XGBoost & Gradient Boosting) outperformed Bagging models** in most cases.  
- **Stacking achieved the highest accuracy** by leveraging multiple model strengths.  

## 🛠️ Technologies Used  
- **Python** - Programming language  
- **scikit-learn** - Machine learning models  
- **XGBoost** - Gradient boosting framework  
- **Pandas & NumPy** - Data manipulation  
- **Matplotlib & Seaborn** - Data visualization  
