# Crypto Trade Analysis using Machine Learning

A machine learning project focused on analyzing real-world cryptocurrency trading data through data cleaning, feature engineering, exploratory data analysis, and comparative evaluation of multiple regression models.


##  Project Overview
The objective of this project is to predict the **Closed Profit & Loss (PnL)** of cryptocurrency trades using various machine learning algorithms.

The project follows a complete data science workflow:
- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Model Training
- Model Evaluation
- Comparative Performance Analysis

The following preprocessing steps were performed:

- Removed duplicate records
- Handled missing values
- Removed unnecessary columns
- Encoded categorical variables
- Converted timestamps into usable features
- Log transformation on skewed numerical columns
- Feature scaling (where required)
- Outlier analysis


## Exploratory Data Analysis

Performed analysis using:

- Distribution plots
- Correlation heatmap
- Boxplots
- Feature relationships

## Machine Learning Models

The following models were trained and compared:

- Linear Regression
- Random Forest Regressor
- AdaBoost Regressor
- XGBoost Regressor
- Catboost Regressor

Additional models can be added in future versions.


## Evaluation Metrics

Models were evaluated using:

- Mean Squared Error (MSE)
- R² Score
- Cross Validation Score

Performance comparison between models was carried out to identify the best-performing algorithm.

---

## 📁 Project Structure

## 🧰 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## Results

- Successfully cleaned and transformed a real-world cryptocurrency dataset.
- Built multiple regression models.
- Compared model performance using standard evaluation metrics.
- Identified the most suitable model based on prediction accuracy.


## Future Improvements

- Hyperparameter tuning
- LightGBM implementation
- Feature selection techniques
- Time-series forecasting
- Deep Learning models
- Model deployment using Flask/FastAPI


## Sample Workflow

```
Raw Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Feature Engineering
      │
      ▼
EDA
      │
      ▼
Model Training
      │
      ▼
Performance Evaluation
      │
      ▼
Model Comparison
```

---

## Author

**Keshav Sharma**
B.Tech Artificial Intelligence & Data Science
GitHub: https://github.com/kkeshavsharma
