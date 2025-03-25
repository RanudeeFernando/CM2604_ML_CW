# Bank Marketing Term Deposit Classification System 💼📊

This project is a machine learning-based classification system that predicts whether a bank client will subscribe to a term deposit based on personal, contact, and campaign-related features. It is built using the UCI Bank Marketing dataset and optimized to perform well in real-world scenarios with imbalanced data.


## 🎯 Project Objective

To build a predictive model that classifies clients based on the likelihood of subscribing to a term deposit, while improving key performance metrics like **recall** and **ROC-AUC**.


## 🗂️ Dataset

- **Source:** [UCI Machine Learning Repository – Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/bank+marketing)
- **Records:** ~41,000  
- **Target Variable:** `y` (Yes/No - subscription to term deposit)  
- **Features:** Client demographics, contact details, campaign information, and economic indicators


## 🧪 Key Steps

### ✅ Data Preprocessing

- 🧹 Cleaned and handled missing/inconsistent values
- 🔍 Detected and treated outliers
- 🔄 Applied **label encoding** and **one-hot encoding**
- 📊 Scaled features using **StandardScaler**
- ⚖️ Handled class imbalance with **SMOTE (Synthetic Minority Over-sampling Technique)**

### 🧠 Modeling & Tuning

- Used **Random Forest** and **Neural Networks**
- Performed hyperparameter tuning with **GridSearchCV**
- Applied **EarlyStopping** to avoid overfitting (especially in neural nets)
- Evaluated with:
  - Accuracy
  - Precision, Recall
  - F1-score
  - ROC-AUC Score


## 📈 Results & Evaluation

The models were trained, validated, and compared based on their ability to:

- Maximize **recall** (important in marketing campaigns)
- Improve **ROC-AUC** score
- Handle **class imbalance** effectively without sacrificing generalization

---

## 💡 Features

- 🔍 End-to-end classification pipeline
- 📊 Exploratory Data Analysis (EDA) included
- 💼 Practical handling of imbalanced marketing datasets
- 🧠 Model comparison with interpretability and metric tracking
- 📁 Modular, reproducible code for retraining and evaluation

---

## 🛠️ Tech Stack

- **Python**  
- **Pandas**, **NumPy**  
- **Scikit-learn**  
- **Imbalanced-learn** (for SMOTE)  
- **Matplotlib**, **Seaborn** (for EDA)  
- **Keras** / **TensorFlow** (for Neural Networks)

