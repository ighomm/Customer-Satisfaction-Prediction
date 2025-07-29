# Customer Satisfaction Prediction 🎯

This project uses machine learning to predict **customer satisfaction ratings** based on support ticket data. It includes data preprocessing, visualization, feature engineering, model training, and evaluation using Python on Google Colab.

---

## 📁 Dataset

The dataset contains customer support ticket data including:
- Age, gender, product purchased
- Ticket type, priority, channel
- Satisfaction rating (1 to 5)
- Text descriptions of issues

> **📦 File:** `customer_support_tickets.csv`

---

## 📊 Features of the Project

- ✅ Data Cleaning and Preprocessing
- ✅ Exploratory Data Analysis (EDA) with plots
- ✅ Feature Engineering (Label encoding, date parsing)
- ✅ Satisfaction Prediction using:
  - RandomForestClassifier
  - LogisticRegression (optional)
  - XGBoost (optional)
- ✅ Model Evaluation with accuracy, confusion matrix
- ✅ Feature Importance visualization
- ✅ Clustering, Sentiment Analysis (optional)
- ✅ Regression model to predict resolution time (optional)

---

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn
- Google Colab (for running code)
- [TextBlob](https://textblob.readthedocs.io/) (optional, for sentiment)

---

## 🚀 How to Run

> This project is built to run on **Google Colab**.

1. Upload the `customer_support_tickets.csv` file to your Colab session
2. Open the notebook `Customer_Satisfaction_Prediction_Project.ipynb`
3. Run the notebook cell-by-cell
4. (Optional) Install missing packages with `!pip install -r requirements.txt`

---

## 📈 Results

Achieved a satisfaction rating prediction accuracy of around ~80% using Random Forest. Feature importance revealed that ticket priority, type, and channel had high influence.

---
