# 📊 Advertising Prediction — Machine Learning Project

## 📌 Introduction
This project builds a machine learning model that predicts product **sales** based on advertising budgets in three media channels:

- **TV**
- **Radio**
- **Newspaper**

The goal is to analyze how advertising spending influences sales and use these relationships to make accurate predictions.

Dataset used: **Advertising.csv**

---

## 🚀 Getting Started

### 1️⃣ Clone the repository
```bash
git clone https://github.com/Arsen-Aghajanyan/Advertising-prediction
cd Advertising-prediction
```

### 2️⃣ Install dependencies
Make sure Python 3.9+ is installed.
```bash
pip install -r requirements.txt
```
If you are using Jupyter Notebook, simply open
Sale_pred.ipynb

### ▶️ How to Run and Test the Project
### Option A — Run through Jupyter Notebook
1. Open Sale_pred.ipynb
2. Run all cells from top to bottom

### The notebook will automatically:
- Load the dataset
- Display data statistics
- Generate visualizations
- Split data into train/test
- Train the ML model
- Test the model
- Show predictions and accuracy

### 📚 Libraries and Functions Used

#### pandas
Used for data loading and analysis.
Functions:
- read_csv()
- head()
- describe()

#### numpy
Used for numerical operations and arrays.

#### matplotlib / seaborn / plotly
Used for visualizations:
- Scatterplots
- Histograms
- Correlation heatmap

#### scikit-learn
Used for machine learning:
- train_test_split() — splits dataset
- LinearRegression() — regression model
- model.fit() — training
- model.predict() — predictions
- model.score() — R² accuracy metric

### 🏁 Conclusion
This project demonstrates how advertising spending affects sales and how machine learning can be used to model these relationships and make predictions based on real data
