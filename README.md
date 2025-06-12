# Mental-Health-Classification

## 📌 Overview
This project aims to classifying anxiety and stress levels by identifying five factors influencing the stress of final-year students, including the supervisor role, literature review, analysis method, support system, and research gap

## 📌 Project Goals
- Identifying factors that influence stress and anxiety levels
- Building an accurate predictive model

## 📂 Project Structure
This project include the following main components
1. Data Preprocessing
   - Handling missing value
   - Convert categorical into numerical features manually
   - Balancing Data using SMOTE
   - Standardization using StandarScaler
2. Modelling
   - Applying SVM with multiple kernel functions : Polynomial, Radial Basis Function, Linear, and Sigmoid
   - Adjusting SVM with C value = 10, 100, 1000. Degree for Polynomial = 1, 2, 3. Gamma for RBF and Sigmoid = 1, 2, 3
3. Evaluation
   - Evaluating model performance using Cross Validation with 5-fold

## 📈 Visualization
- Distribution of Stress and Anxiety Levels
- Distribution of Stress and Anxiety Levels each Major
- Feature importance (from best model)

## 🔎 Key Findings
- Highest accuracy for Stress dataset classification is Radial Basis Function kernel with gamma value of 1, and C value of 100 reached 68%
- Highest accuracy for Anxiety dataset classification is Polynomial kernel, degree value of 3 and C value of 100, reaching 50%
- Literature Review, Support System, and Analysis Method were the most influential features
