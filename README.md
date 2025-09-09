

# Customer Churn Prediction using Artificial Neural Networks (ANN)

## 📌 Project Overview

This project builds an **Artificial Neural Network (ANN)** to predict **customer churn** — identifying customers who are likely to leave a service.

Reducing churn is crucial for improving **customer retention** and driving **business growth**.
The project demonstrates an end-to-end machine learning pipeline with neural networks.

---

## ⚙️ Tech Stack

* **Python** 3.x
* **Libraries**: TensorFlow / Keras, scikit-learn, pandas, numpy, matplotlib, seaborn

---

## 🚀 Workflow

1. **Data Loading** – Import and explore the dataset.
2. **Exploratory Data Analysis (EDA)** – Understand churn distribution and feature insights.
3. **Preprocessing** – Handle missing values, encode categorical data, scale numerical features.
4. **Train/Test Split** – Split dataset with stratification.
5. **Model Building** – ANN using Keras (Sequential API).
6. **Training** – Fit model with callbacks (e.g., EarlyStopping).
7. **Evaluation** – Accuracy, Precision, Recall, F1, ROC-AUC, confusion matrix.
8. **Insights & Conclusions** – Translate results into business impact.

---

## 📊 Results

* ANN achieves strong predictive performance (details inside notebook).
* Provides actionable insights: e.g., customers with shorter tenure and higher monthly charges have higher churn risk.

---

## 🔧 How to Run

```bash
# Clone repo
git clone https://github.com/your-username/churn-ann.git
cd churn-ann

# Create environment
python -m venv venv
source venv/bin/activate  # (Linux/Mac)
venv\Scripts\activate     # (Windows)

# Install dependencies
pip install -r requirements.txt

# Run notebook
jupyter notebook "Churn_Model_Using_ANN_documented.ipynb"
```

