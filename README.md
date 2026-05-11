# wine-fraud-detection
Wine Fraud Detection using Machine Learning is a classification project that identifies whether a wine sample is genuine or fraudulent based on physicochemical properties such as acidity, pH, alcohol content, and sulfur dioxide levels. SMOTE is applied to handle class imbalance and improve prediction accuracy.
# Wine Fraud Detection using Random Forest and SMOTE

## 📌 Project Overview

This project aims to detect fraudulent wine samples using Machine Learning techniques, specifically the **Random Forest Classifier**.

The dataset contains physicochemical properties of wine such as:

- Acidity
- Sugar Content
- pH Level
- Alcohol Content
- Sulfur Dioxide Levels
- Sulphates
- Volatile Acidity
- Wine Type and Quality

Wine fraud occurs when low-quality wine is mislabeled or sold as high-quality wine. The objective of this project is to build a classification model that can accurately identify whether a wine sample is genuine or fraudulent.

Since the dataset is imbalanced, **SMOTE (Synthetic Minority Oversampling Technique)** was applied to improve prediction performance for the minority fraud class.

---

# 🎯 Problem Statement

The goal of this project is to predict whether a wine sample is fraudulent based on its physicochemical properties and quality-related attributes.

Accurate fraud detection can help improve quality control and prevent misleading labeling in the wine industry.

---

# ⚙️ Solution Approach

The following steps were performed to solve the problem:

## 1. Data Preprocessing

- Checked for missing values (none found)
- Encoded categorical variables into numerical format
- Separated features and target variable
- Prepared dataset for model training

---

## 2. Handling Class Imbalance

Applied **SMOTE (Synthetic Minority Oversampling Technique)** to balance the dataset.

Benefits of SMOTE:

- Improves minority class prediction
- Reduces model bias toward majority class
- Enhances fraud detection performance

---

## 3. Exploratory Data Analysis (EDA)

Performed data visualization and analysis using:

- Boxplots
- Distribution plots
- Correlation analysis

Key observations:

- Some features contained outliers
- Alcohol and sulphates showed strong influence on wine quality
- Fraudulent cases were significantly fewer than genuine cases

---

## 4. Feature Scaling

Applied **Standardization** to normalize numerical feature values before model training.

---

## 5. Model Building

Implemented **Random Forest Classifier**.

Random Forest works by combining multiple decision trees to improve:

- Accuracy
- Stability
- Robustness

---

## 6. Model Evaluation

The model was evaluated using:

- Accuracy Score
- Confusion Matrix
- ROC Curve

Performance was compared before and after applying SMOTE.

---

## 7. Conclusion

- Random Forest performed effectively in detecting wine fraud
- SMOTE significantly improved prediction of fraudulent wine samples
- Important features included:
  - Alcohol
  - Sulphates
  - Volatile Acidity

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- imbalanced-learn (SMOTE)
- Jupyter Notebook / Google Colab

---

# 📂 Project Structure

```bash
├── Wine_Fraud_Detection.ipynb
├── wine_fraud.csv
├── README.md
```

---

# 📊 Machine Learning Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis
4. Handling Class Imbalance using SMOTE
5. Feature Scaling
6. Model Training
7. Model Evaluation
8. Prediction & Interpretation

---

# 🚀 How to Run the Project

## 1. Clone Repository

```bash
git clone <your-github-repository-link>
```

---

## 2. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn
```

---

## 3. Run Jupyter Notebook

```bash
jupyter notebook
```

Open:

```bash
Wine_Fraud_Detection.ipynb
```

---

# 📈 Results

The Random Forest model successfully detected fraudulent wine samples using physicochemical wine properties.

Applying SMOTE improved the model's ability to correctly classify minority fraud cases and enhanced overall prediction performance.

---

# 🔮 Future Improvements

- Apply advanced ensemble models
- Hyperparameter tuning
- Cross-validation
- Deploy model using Flask or Streamlit
- Build interactive fraud detection dashboard

---

# 👨‍💻 Author

Mannat

---

# ⭐ Conclusion

This project demonstrates the complete Machine Learning workflow for wine fraud detection using Random Forest Classification and SMOTE, including preprocessing, visualization, handling class imbalance, model training, evaluation, and interpretation.
