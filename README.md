# Mental-Health-Classification

## 📌 Overview
This project aims to predict a person's sleep duration based on various health and lifestyle factors such as stress level, physical activity level, BMI Category, etc using multiple regression models in Python 

## 📌 Project Goals
- Understand which features impact sleep duration
- Build machine learning models to predict sleep duration
- Evaluate model performance using MSE and R<sup>2</sup>
- Visualize results and extract insights from feature importance

## 📂 Project Structure
This project include the following main components
1. Data Preprocessing
   - Handling missing value
   - Handling outliers using Z-Score
   - Standardization using StandarScaler
   - Convert categorical features into numerical using LabelEncoder
2. Modelling
   - Applying multiple regression models : Linear Regression, Random Forest, XGBoost, Support Vector Machine
3. Evaluation
   - Evaluating model performance using MSE and R<sup>2</sup>

## 📈 Visualization
- Sleep Duration by Categorical Feature
- Correlation heatmap (Numerical Feature)
- Model performance bar charts
- Feature importance (from best model)

## 🔎 Key Findings
- Random Forest performed the best (R<sup>2</sup> = 0.9895)
- Stress Level and Physical Activity were the most influential features
