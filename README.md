# Rossmann-Retail-Sales-Prediction---ML_Project-Regression-
Rossmann Retail Sales Prediction - Regression_Supervised_ML_Project
<img width="640" height="360" alt="1_C6QjcwkJGUmw0sot8pd4Cw" src="https://github.com/user-attachments/assets/ec01fc31-ede3-4d37-8e73-2691391ed829" />




🧠 Project Overview

Retail businesses generate massive amounts of sales data every day. Accurately forecasting future sales is essential for effective inventory management, workforce planning, promotional strategy, and overall business growth.

In this project, machine learning techniques were used to predict daily sales for Rossmann drug stores based on historical sales data and store-related features such as promotions, holidays, competition, seasonality, and store type.

The project includes:

1. Data Cleaning & Preprocessing
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Machine Learning Model Building
5. Model Comparison
6. Feature Importance Analysis
7. Model Deployment Preparation

The final model successfully achieved approximately 89% prediction accuracy (R² Score) using the Random Forest Regressor.

🚀 Business Problem

Rossmann operates thousands of retail stores, making manual sales forecasting difficult and inefficient.

Incorrect sales forecasting may lead to:
1. Overstocking
2. Understocking
3. Revenue loss
4. Poor workforce planning
5. Inefficient promotional strategies

The goal of this project is to build a machine learning model capable of accurately forecasting future sales using historical sales data and business-related factors.

🎯 Project Objective

The main objectives of this project are:

1. Analyze historical retail sales data
2. Identify important factors affecting sales
3. Perform exploratory data analysis
4. Build multiple machine learning models
5. Compare model performance
6. Select the best-performing model
7. Prepare the model for deployment

🗂️ Dataset Information

The project uses two datasets:

1. Train Dataset
Contains:

(i)   Store sales
(ii)  Customer count
(iii) Promotions
(iv)  Holidays
(v)   Daily operational information

2. Store Dataset
Contains:

Store type
Assortment type
Competition distance
Promotional campaign details

🛠️ Tools & Technologies Used
Programming Language
Python 🐍
Libraries Used
Data Manipulation
Pandas
NumPy
Data Visualization
Matplotlib
Seaborn
Machine Learning
Scikit-learn
XGBoost
Model Saving
Joblib
Pickle
Statistical Testing
Scipy
Explainability
SHAP
Environment
Jupyter Notebook
Google Colab

**📊 Exploratory Data Analysis (EDA)**

**The following analyses were performed:**

Sales Distribution Analysis
Promotion vs Sales Analysis
Store Type vs Sales Analysis
Seasonal Sales Trends
Competition Impact Analysis
Correlation Heatmap
Pair Plot Analysis

**Key Insights**
Promotions significantly increased sales
Customer count strongly affected revenue
Seasonal trends influenced store performance
Competition distance impacted sales
Certain store types performed better than others

**🧹 Data Preprocessing & Feature Engineering**

The following preprocessing steps were performed:

✅ Handling missing values
✅ Removing duplicate rows
✅ Removing closed stores
✅ Removing zero-sales records
✅ Date conversion & feature extraction
✅ Label encoding categorical variables
✅ Log transformation of target variable
✅ Feature selection

**🤖 Machine Learning Models Used**

The following models were trained and evaluated:
| Model                   | R² Score |
| ----------------------- | -------- |
| Linear Regression       | 0.226    |
| Decision Tree Regressor | 0.417    |
| Random Forest Regressor | 0.892    |
| XGBoost Regressor       | 0.869    |


**🏆 Best Performing Model**
**Random Forest Regressor
Performance Metrics**
| Metric   | Score   |
| -------- | ------- |
| RMSE     | 1012.52 |
| MAE      | 686.96  |
| R² Score | 0.892   |

**Why Random Forest?**
Random Forest performed best because:
1. Handles nonlinear relationships effectively
2. Reduces overfitting
3. Captures feature interactions
4. Performs well on structured retail data

**🔍 Feature Importance**

Feature importance analysis revealed that the following variables had the highest impact on sales prediction:

Promo
Customers
CompetitionDistance
StoreType
Month
DayOfWeek

This helped identify the major business drivers influencing store sales.

**📈 Hypothesis Testing**

A statistical T-Test was performed to determine whether promotions significantly affected sales.

**Result:**
Promotions showed a statistically significant positive impact on sales.

**💾 Model Saving & Deployment**

The final Random Forest model was saved using:
Joblib

This allows:
Real-time predictions
Easy deployment
Reusability without retraining

**📌 Project Workflow**
Data Collection
       ↓
Data Cleaning
       ↓
Exploratory Data Analysis
       ↓
Feature Engineering
       ↓
Model Building
       ↓
Model Evaluation
       ↓
Feature Importance
       ↓
Model Saving
       ↓
Deployment Ready

**📷 Sample Visualizations**
The project includes:

Histograms
Boxplots
Scatterplots
Heatmaps
Pairplots
Feature Importance Charts

**📚 Project Learnings**
Through this project, I learned:

End-to-end machine learning workflow
Retail sales forecasting techniques
Feature engineering strategies
Model evaluation & comparison
Business-focused data analysis
Model explainability
Deployment preparation

**🌟 Business Impact**
This project can help retail businesses:

Improve inventory management
Optimize promotional campaigns
Forecast future sales accurately
Improve operational efficiency
Enhance decision-making through predictive analytics

**🔮 Future Improvements**
Possible future enhancements:

Deep Learning models (LSTM)
Real-time sales prediction dashboard
Hyperparameter tuning
Streamlit/Flask deployment
Advanced time-series forecasting

**📂 Project Structure**
Rossmann-Sales-Prediction/
│
├── data/
├── notebooks/
├── images/
├── models/
├── README.md
├── requirements.txt
└── rossmann_sales_prediction.ipynb

**🙋‍♂️ Author**
**Tanmay Gautam**
Machine Learning & Data Science Enthusiast

**⭐ If You Like This Project**
If you found this project useful, consider giving it a ⭐ on GitHub!
