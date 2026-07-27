# 🏡 House Price Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-green)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-orange)
![Data Analysis](https://img.shields.io/badge/Data-Analysis-red)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

## 📌 Overview

Accurate house price prediction helps buyers, sellers, and real estate businesses make informed decisions.

This project uses **Machine Learning** and **Exploratory Data Analysis (EDA)** to predict residential house prices based on various property features such as area, number of bathrooms, bedrooms, parking availability, air conditioning, and furnishing status.

The project compares multiple machine learning algorithms and analyzes the importance of different housing features to understand what truly drives property prices.

---

# 🎯 Objectives

- Analyze the housing dataset
- Perform exploratory data analysis (EDA)
- Identify features influencing house prices
- Build predictive machine learning models
- Compare model performance
- Generate business insights for the real estate market

---

# 📂 Project Structure

```text
house-price-prediction/
│
├── README.md
├── LICENSE
├── requirements.txt
├── .gitignore
├── House_Price_Prediction.ipynb
│
├── data/
│   └── Housing.csv
│
├── images/
│   ├── price_distribution.png
│   ├── correlation_heatmap.png
│   ├── actual_vs_predicted.png
│   ├── feature_importance.png
│   └── model_comparison.png
│
├── reports/
│   └── Executive_Summary.pdf
│
└── models/
    └── trained_model.pkl
```

---

# 📊 Dataset

The project uses a housing dataset containing residential property information.

### Dataset Features

- Area
- Bedrooms
- Bathrooms
- Stories
- Parking
- Main Road Access
- Guest Room
- Basement
- Hot Water Heating
- Air Conditioning
- Preferred Area
- Furnishing Status

### Target Variable

- House Price (₹)

---

# ⚙ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

# 🔍 Exploratory Data Analysis

The analysis includes:

- Price distribution
- Correlation analysis
- Feature importance
- Price prediction visualization
- Model comparison

---

# 🤖 Machine Learning Workflow

```text
Housing Dataset
        │
        ▼
Data Cleaning
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Feature Engineering
        │
        ▼
Data Preprocessing
        │
        ▼
Train-Test Split
        │
        ▼
Machine Learning Models
        │
        ▼
Model Evaluation
        │
        ▼
House Price Prediction
```

---

# 🤖 Machine Learning Models

The following machine learning models were implemented:

- Linear Regression
- Random Forest Regressor

---

# 📈 Visualizations

## House Price Distribution

```markdown
![House Price Distribution](images/price_distribution.png)
```

---

## Correlation Heatmap

Shows the relationship between all housing features and the target variable.

```markdown
![Correlation Heatmap](images/correlation_heatmap.png)
```

---

## Actual vs Predicted House Prices

Comparison between actual and predicted house prices using Linear Regression.

```markdown
![Actual vs Predicted](images/actual_vs_predicted.png)
```

---

## Feature Importance

Random Forest identifies the most influential features affecting house prices.

```markdown
![Feature Importance](images/feature_importance.png)
```

---

# 📊 Model Performance

The models were evaluated using:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

### Best Performing Model

✅ **Linear Regression**

- R² Score ≈ **0.65**
- Average prediction error ≈ **₹970K**

---

# 📈 Key Findings

The analysis revealed several important insights:

- **Area** is the strongest predictor of house price.
- Houses with more **bathrooms** generally command higher prices.
- **Air conditioning** has a stronger influence on price than the number of bedrooms.
- Parking availability and additional stories positively affect property value.
- Furnishing status also contributes to house prices.
- Linear Regression outperformed Random Forest for this dataset because the relationships between features and price are largely linear.

---

# 💼 Business Recommendations

Based on the analysis:

- Prioritize larger plot sizes in marketing campaigns.
- Renovations that add bathrooms can significantly increase property value.
- Installing air conditioning offers a strong return on investment.
- Improve premium amenities rather than simply increasing bedroom count.
- Focus on properties with parking and multiple stories to maximize resale value.

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/babikaghub/house-price-prediction.git
```

Navigate to the project

```bash
cd house-price-prediction
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
House_Price_Prediction.ipynb
```

---

# 📦 Requirements

```
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
```

Or install using

```bash
pip install -r requirements.txt
```

---

# 🔮 Future Improvements

- XGBoost Regressor
- LightGBM
- CatBoost
- Hyperparameter Optimization
- SHAP Explainability
- Streamlit Web Application
- House Price Recommendation System
- Real-time Price Prediction API

---

# 📄 License

This project is licensed under the MIT License.

---

# 👩‍💻 Author

**Babika Masua**

M.Tech (Computer Science & Engineering)

Machine Learning | Artificial Intelligence | Data Science

📧 Email: babikamasua31@gmail.com

🔗 LinkedIn: www.linkedin.com/in/babikamasua5b4418/


💻 GitHub: https://github.com/babikaghub

---

⭐ **If you found this project useful, please consider giving it a Star!**
