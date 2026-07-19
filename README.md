# 🎓 Student SGPA Prediction using Machine Learning

A machine learning project that predicts a student's **Semester Grade Point Average (SGPA)** using academic, behavioural, and lifestyle factors. This project demonstrates a complete end-to-end machine learning workflow, including data preprocessing, exploratory data analysis, feature engineering, model training, hyperparameter tuning, and performance evaluation.

---

## 📌 Project Overview

The objective of this project is to build a regression model capable of accurately predicting a student's SGPA based on various factors such as:

- Attendance
- Study Hours
- Screen Time
- Stress Level
- Gender
- Academic Habits
- Lifestyle Features

The project compares multiple machine learning algorithms and identifies the best-performing model through cross-validation and hyperparameter tuning.

---

## 🚀 Features

- Comprehensive data cleaning and preprocessing
- Missing value handling
- Categorical data encoding
- Feature engineering
- Exploratory Data Analysis (EDA)
- PCA and t-SNE visualizations
- Multiple regression models
- Cross-validation
- Hyperparameter tuning using GridSearchCV
- Feature importance analysis
- Model comparison and evaluation

---

## 📂 Project Structure

```
├── FinalProject_Updated.ipynb      # Main Jupyter Notebook
├── sgpa_dataset_medium_messy_6000.csv
├── README.md
```

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Machine Learning Workflow

### 1. Data Loading

- Import dataset
- Explore dataset shape
- Inspect missing values
- Analyze data types

---

### 2. Data Cleaning

The dataset contains intentionally messy data. Cleaning includes:

- Removing `%` from Attendance values
- Converting attendance into numerical format
- Standardizing column names
- Cleaning Gender values
- Encoding Stress Level into ordinal values
- Handling missing values

---

### 3. Exploratory Data Analysis (EDA)

Performed visual analysis including:

- Distribution plots
- Correlation heatmap
- Scatter plots
- Box plots
- Outlier detection
- Relationship between features and SGPA

---

### 4. Feature Engineering

New features were created to improve model performance:

- **Study Efficiency**
  - Study Hours × Attendance

- **Screen-to-Study Ratio**
  - Screen Time / Study Hours

Additional preprocessing includes:

- Feature scaling
- Data transformation

---

### 5. Dimensionality Reduction

Visualization using:

- Principal Component Analysis (PCA)
- t-SNE

These techniques help understand the distribution of students across different SGPA ranges.

---

### 6. Machine Learning Models

The following regression algorithms were trained and compared:

- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor
- Support Vector Regressor (SVR)
- K-Nearest Neighbors Regressor (KNN)

---

### 7. Model Evaluation

Models were evaluated using **5-Fold Cross Validation**.

Performance metrics include:

- R² Score
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

---

### 8. Hyperparameter Tuning

The best-performing model was optimized using:

- GridSearchCV

This improves prediction accuracy by selecting the optimal hyperparameters.

---

### 9. Final Evaluation

The tuned model was evaluated on an unseen test dataset to measure its real-world prediction capability.

---

### 10. Feature Importance

Feature importance analysis was performed to identify which variables contribute most to SGPA prediction.

---

## 📈 Results

The project compares multiple regression algorithms and selects the best-performing model based on:

- Highest R² Score
- Lowest MAE
- Lowest RMSE

Hyperparameter tuning further improves the final model's performance.

---

## 📷 Visualizations Included

- Feature Distributions
- Correlation Heatmap
- Scatter Plots
- Box Plots
- PCA Visualization
- t-SNE Visualization
- Actual vs Predicted Graph
- Feature Importance Plot

---

## 💡 Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis
- Feature Engineering
- Regression Modeling
- Cross Validation
- Hyperparameter Optimization
- Model Evaluation
- Data Visualization
- Machine Learning Pipeline

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/student-sgpa-prediction.git
```

2. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Open the notebook

```bash
jupyter notebook FinalProject_Updated.ipynb
```

4. Run all cells.

---

## 📌 Future Improvements

- Deploy the model using Flask or Streamlit
- Experiment with XGBoost and LightGBM
- Perform advanced feature selection
- Implement ensemble learning
- Build an interactive dashboard for predictions

---

## 👨‍💻 Author

**Abheer Walia**

---

## ⭐ If you found this project useful

Give this repository a ⭐ on GitHub and feel free to contribute or provide feedback!
