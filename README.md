# 📦 Ecommerce Return Prediction – ReturnPal

<p align="center">
  <img src="./project images/Banner.jpg" alt="Ecommerce Return Prediction" width="100%">
</p>

---

## 📌 Project Overview  
This project focuses on predicting **ecommerce product returns** to help retailers reduce losses, optimize inventory, and enhance customer satisfaction.  

Ecommerce returns cost retailers billions annually and generate significant **environmental impact** (24M metric tons of CO₂ and 9.5B pounds of waste). This solution applies **data analytics and machine learning** to build a return-prediction system that empowers sustainable commerce.  

📺 **[Watch the Project Demo on YouTube](https://youtu.be/66e9IJGRQ1I?si=72ODYk_L6V0AQPEO)**  

---

## 🎯 Objectives  
- Analyze ecommerce sales & return behavior.  
- Build predictive ML models to identify **high-return risk products**.  
- Develop actionable insights for **return reduction strategies**.  
- Support **sustainable retail practices** by lowering waste and CO₂ emissions.  

---

## 📊 Dataset  
- Source: Public ecommerce dataset (Q1 2023).  
- Size: ~20,000 rows × 15 columns (bootstrapped to 100,000 for modeling).  
- Key Features: product details, price, brand, category tree, return status.  

---

## 🧹 Data Cleaning & Preparation  
- Dropped unnecessary columns (URLs, specs, images).  
- Split category hierarchy into subcategories.  
- Grouped into **7 super categories** for analysis.  
- Bootstrapped dataset to balance return vs. non-return classes.  
- Applied feature engineering (temporal features, brand extraction, categorical encoding).  

---

## 🔎 Exploratory Data Analysis (EDA)  
- **Fashion** products had the highest sales and return rates.  
- Returns were also high in **Electronics and Furniture**.  
- Subcategories like **Clothing, Jewelry, and Bags** showed strong return patterns.  
- Top brands with frequent returns were identified, e.g., *Allure Auto* in Automotive.  

---

## 🤖 Machine Learning Model  
- Algorithm: **Support Vector Machine (SVM)**.  
- Addressed class imbalance with **undersampling**.  
- Accuracy: ~51%  
- Recall for returned items: **57%** (capturing more actual returns).  
- F1-score: Balanced precision/recall around **0.51**.  

---

## 📂 Deliverables  
- 🎥 [Presentation (PPTX)](./deliverables/Ecommerce_Return_Prediction_Presentation.pptx)  
- 📄 [Final Report (PDF)](./deliverables/Ecommerce_Return_Prediction_Report.pdf)  
- 📊 [Tableau Dashboard (.twbx)](./deliverables/Ecommerce_Return_Prediction_Dashboard.twbx)  
- 🐍 [Jupyter Notebook (IPYNB)](./deliverables/Ecommerce_Return_Prediction.ipynb)  
- 📺 [YouTube Demo Video](https://youtu.be/66e9IJGRQ1I?si=72ODYk_L6V0AQPEO)  

---

## 🛠 Tools & Technologies  
- **Python** (pandas, numpy, scikit-learn) – Data prep & ML  
- **Tableau** – Interactive dashboards & visuals  
- **Excel** – Preprocessing and exploration  
- **Jupyter Notebook** – EDA & modeling  
- **Anvil** – Web app interface for model deployment  

---

## ✅ Outcomes  
- Built a predictive system for **ecommerce returns**.  
- Delivered a return-risk classification model with **explainable insights**.  
- Identified product segments most vulnerable to returns.  
- Recommended **policy & UX improvements** for sustainable ecommerce.  
- Deployed an **interactive web app using Anvil** to make predictions accessible to end-users.  

---

## 👥 Stakeholders & Beneficiaries  
- 🛒 **Ecommerce Retailers** – Reduce return-related revenue loss.  
- 🌍 **Sustainability Advocates** – Lower waste & emissions.  
- 📦 **Logistics & Return Management Firms** – Optimize return handling.  
- 👥 **Consumers** – Improved shopping experience & reduced hassle.  

---

✨ *Predicting returns today for a more sustainable ecommerce tomorrow.*  
