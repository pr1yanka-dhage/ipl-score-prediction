# 🏏 First Innings Score Prediction - IPL  

This project focuses on predicting the **first innings score** in Indian Premier League (IPL) matches using **machine learning techniques**. The goal is to estimate the final first-innings total based on match conditions, teams, and current performance features.  

---

## 📌 Project Workflow  

### **1. Import Libraries**  
- Imported **NumPy, Pandas, Matplotlib, Seaborn**, and **scikit-learn**.  
- Loaded helper functions for data visualization and preprocessing.  

### **2. Exploratory Data Analysis (EDA)**  
- Loaded IPL dataset with **pandas**.  
- Explored team performance trends, batsmen contributions, and venue-based statistics.  
- Visualized feature relationships using **Seaborn plots & Matplotlib charts**.  

### **3. Data Preprocessing**  
- Handled missing values and irrelevant columns.  
- Encoded categorical variables such as **batting team, bowling team, city** using **One-Hot Encoding**.  
- Engineered new features to improve prediction.  

### **4. Feature Selection & Train-Test Split**  
- Selected important features like:  
  - Batting Team  
  - Bowling Team  
  - Current Score  
  - Overs Played  
  - Wickets Lost  
  - Venue (city)  
- Split the dataset into **training and testing sets** (80-20).  

### **5. Model Building**  
- Built regression models with **scikit-learn**:  
  - Linear Regression  
  - Decision Tree Regressor  
  - Random Forest Regressor  
- Tuned hyperparameters to improve accuracy.  

### **6. Model Evaluation**  
- Evaluated models with metrics:  
  - **R² Score**  
  - **Mean Absolute Error (MAE)**  
  - **Root Mean Squared Error (RMSE)**  
- Compared different models to identify the best performer.  

---

## 🚀 Key Learnings  
- Preprocessing cricket datasets with categorical and numerical features.  
- Importance of **team, venue, and match context** in score prediction.  
- Comparing regression models for numerical prediction tasks.  

---

## 🛠️ Tech Stack  
- **Python**  
- **Pandas, NumPy**  
- **Matplotlib, Seaborn**  
- **scikit-learn**  

---

## 📊 Results  
- **Random Forest Regressor** performed the best with higher accuracy and lower error compared to Linear Regression and Decision Trees.  
- The model can reasonably predict IPL first innings scores with the given features.  

---

## 📌 Next Steps  
- Experiment with advanced models (XGBoost, LightGBM).  
- Add contextual features like **player form, pitch reports, and weather**.  
- Deploy as a web application for live score prediction.  

---

✨ This project demonstrates how machine learning can be applied to **sports analytics** to make real-time predictions in cricket.  
