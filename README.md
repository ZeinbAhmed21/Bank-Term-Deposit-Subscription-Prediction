# 🏦 Bank Term Deposit Subscription Prediction

## 📌 Project Overview

This project focuses on predicting whether a bank client will subscribe to a term deposit using supervised machine learning techniques.

The objective is to build and evaluate multiple classification models to support data-driven marketing decisions and improve campaign efficiency.

---

## 🎯 Business Problem

Banks conduct marketing campaigns to encourage customers to subscribe to term deposits.  
However, contacting every customer is costly and inefficient.

This project aims to:

- Predict customer subscription behavior
- Reduce marketing costs
- Improve campaign targeting
- Increase conversion rates

---

## 📊 Dataset

**Dataset Name:** Bank Marketing Dataset  

The dataset includes customer-related attributes such as:

- Age
- Job
- Marital status
- Education
- Credit default
- Housing loan
- Contact type
- Campaign details
- Previous campaign outcomes

**Target Variable:**  
`y` → Whether the client subscribed to a term deposit (Yes / No)

---

## ⚙️ Technologies & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- imbalanced-learn (SMOTE)

---

## 🧠 Machine Learning Pipeline

### 1️⃣ Data Preprocessing
- Handling missing values
- Encoding categorical variables
- Feature scaling
- Train/Test split

### 2️⃣ Handling Class Imbalance
- Applied SMOTE (Synthetic Minority Oversampling Technique)

### 3️⃣ Dimensionality Reduction
- Principal Component Analysis (PCA)

### 4️⃣ Models Implemented

- Logistic Regression
- Naive Bayes
- (Any additional model you used)

### 5️⃣ Model Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC Curve
- Cross-Validation

---

## 📈 Workflow

1. Data Loading
2. Exploratory Data Analysis (EDA)
3. Data Cleaning
4. Feature Engineering
5. Handling Imbalance (SMOTE)
6. Model Training
7. Model Evaluation
8. Performance Comparison

---

## 📊 Key Results

- Improved classification performance after applying SMOTE
- Logistic Regression showed strong baseline performance
- ROC Curve analysis provided deeper insight into model discrimination power
- Cross-validation ensured model generalization

---

## 🚀 How to Run the Project

1️⃣ Clone the repository:

```

git clone [https://github.com/your-username/Machine-Learning-Projects.git](https://github.com/your-username/Machine-Learning-Projects.git)

```

2️⃣ Navigate to the classification folder:

```

cd classification-bank-marketing

```

3️⃣ Install required dependencies:

```

pip install -r requirements.txt

```

4️⃣ Run the notebook:

```

jupyter notebook bank_term_deposit_subscription_prediction.ipynb

```

---

## 📁 Project Structure

```

classification-bank-marketing/
│
├── bank_term_deposit_subscription_prediction.ipynb
├── dataset/
└── README.md

```

---

## 🔎 Future Improvements

- Hyperparameter tuning using GridSearchCV
- Try ensemble models (Random Forest, XGBoost)
- Feature importance analysis
- Model deployment as an API
- Threshold optimization for business cost minimization

---

## 🤝 Contributors
- Zeinab Ahmed
- Ibrahim Hamdy
