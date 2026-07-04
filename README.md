# 🏠 House Price Prediction using Machine Learning

## 📌 Project Overview

This project predicts house prices using the California Housing Dataset and Machine Learning algorithms. The project includes data preprocessing, exploratory data analysis (EDA), model training, evaluation, and house price prediction.

---

## 🎯 Objective

To build a machine learning model that accurately predicts the median house value based on housing characteristics such as location, income, population, and number of rooms.

---

## 📂 Dataset

**Dataset:** California Housing Dataset (`housing.csv`)

### Features

| Feature | Description |
|---------|-------------|
| longitude | House location longitude |
| latitude | House location latitude |
| housing_median_age | Median age of houses |
| total_rooms | Total number of rooms |
| total_bedrooms | Total number of bedrooms |
| population | Population in the area |
| households | Number of households |
| median_income | Median income of residents |
| ocean_proximity | Distance from the ocean |
| median_house_value | Target variable (House Price) |

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook

---

## 📊 Exploratory Data Analysis (EDA)

The project includes:

- Dataset Information
- Statistical Summary
- Missing Value Handling
- Duplicate Checking
- Label Encoding
- Correlation Heatmap
- Histogram
- Scatter Plot
- Box Plot
- Count Plot
- Pair Plot

---

## 🤖 Machine Learning Models

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

---

## 📈 Evaluation Metrics

The models are evaluated using:

- R² Score
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

---

## 📁 Project Structure

```
HousePricePrediction/
│
├── housing.csv
├── HousePricePrediction.ipynb
├── house_price_model.pkl
├── prediction_result.csv
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run

### Step 1

Clone the repository.

```bash
git clone https://github.com/yourusername/HousePricePrediction.git
```

### Step 2

Install the required libraries.

```bash
pip install -r requirements.txt
```

### Step 3

Open Jupyter Notebook.

```bash
jupyter notebook
```

### Step 4

Run all notebook cells in order.

---

## 📊 Project Workflow

1. Load Dataset
2. Data Cleaning
3. Handle Missing Values
4. Exploratory Data Analysis
5. Feature Encoding
6. Split Dataset
7. Train Models
8. Compare Models
9. Predict House Price
10. Save Best Model

---

## 🎯 Sample Prediction

Input

```
Longitude          : -122.23
Latitude           : 37.88
Housing Age        : 41
Total Rooms        : 880
Total Bedrooms     : 129
Population         : 322
Households         : 126
Median Income      : 8.3252
Ocean Proximity    : NEAR BAY
```

Output

```
Predicted House Price

$452,000 (Approx.)
```

---

## 📌 Future Improvements

- XGBoost Regressor
- Gradient Boosting
- Hyperparameter Tuning
- Flask Web Application
- Streamlit Deployment
- Interactive Dashboard

---

## 👨‍💻 Author

**Mohit Kumar**

**Course:** Bachelor of Computer Applications (BCA)

**Specialization:** Machine Learning & Data Science

---

## ⭐ Features

- Complete Data Cleaning
- Professional Visualizations
- Multiple Machine Learning Models
- Model Comparison
- House Price Prediction
- Model Saving using Joblib
- Resume & GitHub Ready Project

---

