# ❤️ Heart Disease Prediction Using Machine Learning  

## 📌 Project Overview  
This project predicts the likelihood of heart disease in patients using **machine learning algorithms**.  
The dataset used is from the **UCI Machine Learning Repository (Cleveland Heart Disease dataset)**.  

We applied and compared different ML models, including **Logistic Regression, K-Nearest Neighbors (KNN), Random Forest, and Support Vector Machine (SVM)**, to find the most effective model for early detection of heart disease.  

---

## 🎯 Goals of the Project  
- Identify key health indicators (age, cholesterol, blood pressure, max heart rate, etc.) that contribute to heart disease.  
- Compare different ML algorithms to determine the best-performing model.  
- Support healthcare professionals in **early diagnosis** and **better decision-making**.  

---

## 🛠️ Methodology  
1. **Data Preprocessing**  
   - Handled missing values with mode imputation.  
   - Encoded categorical variables.  
   - Normalized numerical features.  

2. **Exploratory Data Analysis (EDA)**  
   - Visualized distributions using histograms and boxplots.  
   - Used correlation heatmaps to identify feature relationships.  

3. **Feature Selection**  
   - Selected important clinical features strongly linked with heart disease.  

4. **Model Development**  
   - Implemented Logistic Regression, KNN, Random Forest, and SVM.  
   - Trained using an 80-20 split with cross-validation.  

5. **Model Evaluation**  
   - Compared Accuracy, Precision, Recall, F1-score, and ROC-AUC.  

---

## 📊 Results  
- **Random Forest** performed the best with:  
  - **Accuracy:** 88%  
  - **ROC-AUC:** 92%  
- Key predictors: **maximum heart rate (thalach)**, **chest pain type (cp)**, **number of major vessels (ca)**, **ST depression (oldpeak)**, and **thalassemia type (thal)**.  

---

## ⚙️ Tech Stack  
- **Python**  
- **NumPy, Pandas, Scikit-learn**  
- **Matplotlib, Seaborn**  
- **Jupyter Notebook**  

---
## 📄 Research Paper
The detailed research paper related to this project is available in a separate repository:  
👉 [Heart Disease Prediction – Research Paper]()


