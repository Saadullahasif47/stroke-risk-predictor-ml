# 🧠 Predicting Stroke Susceptibility Through AI Models  

This project presents an advanced **machine learning framework** for predicting the likelihood of stroke from patient health records.  
By combining rigorous **data preprocessing**, **class imbalance handling**, and **ensemble learning**, the system achieves high predictive performance and is deployed with a scalable web interface.  

---

## 🔬 Methodology  

### 1. Data Preprocessing  
- Applied **StandardScaler** to normalize continuous features.  
- Encoded categorical variables using **One-Hot Encoding**.  
- Addressed significant class imbalance via **SMOTE (Synthetic Minority Oversampling Technique)**.  
- Conducted exploratory feature analysis and engineered new relevant features.  

### 2. Model Development  
- Evaluated multiple machine learning models including **Logistic Regression**, **Decision Tree**, **Random Forest**, **KNN**, and **SVM**.  
- Implemented an **Ensemble Stacking Classifier** combining:  
  - **Logistic Regression**  
  - **Random Forest**  
  - **XGBoost**  
- Optimized hyperparameters for better generalization and balanced performance.  

### 3. Evaluation  
- Conducted stratified cross-validation for robust evaluation.  
- Achieved an overall **Accuracy of 94%**, with balanced **Precision, Recall, and F1-Score**, ensuring reliability even under class imbalance.  

### 4. Deployment  
- Model deployed using **Flask API**.  
- Exposed securely to the web via **Ngrok tunneling**.  
- Integrated a **decision-threshold mechanism** to balance sensitivity and specificity.  

### 5. Frontend  
- Built with **HTML, CSS, and JavaScript**.  
- Includes modern UI with categorical features represented as toggle buttons (Yes/No).  
- Interactive prediction card dynamically displays the classification result.  

---

## 📊 Results  

- **Accuracy:** 94%  
- **Robustness:** Optimized across multiple metrics (Precision, Recall, F1-Score).  
- **Outcome:** Reliable binary classification output **Stroke / No Stroke**.  

---

## 🛠️ Technology Stack  

- **Data Processing & ML:** Python, Pandas, NumPy, Scikit-learn, Imbalanced-learn, XGBoost  
- **Model Deployment:** Flask + Ngrok  
- **Frontend:** HTML, CSS, JavaScript  

---

## 👨‍💻 Contributor  

- **Saad Hassan Faisal**  
  - GitHub: [github.com/SaadHassanFaisal ](https://github.com/SaadHassanFaisal )  
  - Email: saadhassanfaisal1403@gmail.com 
