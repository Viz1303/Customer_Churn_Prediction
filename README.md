# 📉 Customer Churn Prediction – Telecom Industry  

## 📌 Overview  
Customer churn is one of the **biggest revenue risks** in the telecom industry. Acquiring a new customer costs **5–7x more** than retaining an existing one, and even a **1% reduction in churn can save millions annually**.  

This project develops a **machine learning–based churn prediction model** that identifies customers at risk of leaving and reveals the **drivers behind churn behavior**. By combining predictive modeling with business insights, the project shows how telecom companies can:  

- 💰 **Protect recurring revenue** by proactively retaining high-value customers.  
- 🎯 **Personalize retention offers** based on churn drivers.  
- 📊 **Optimize marketing spend** by focusing only on at-risk customers.  
- 📈 **Increase Customer Lifetime Value (CLV)** through targeted engagement.  

---

## 🔗 Dataset  
Source: [Kaggle Customer Churn Dataset](https://www.kaggle.com/code/bhartiprasad17/customer-churn-prediction/input)  

**Features include:**  
- Services each customer signed up for (phone, internet, fiber).  
- Customer account details (tenure, payment method, charges).  
- Demographics (gender, senior citizen, partner, dependents).  
- Churn label (Yes/No).  

---

## 🛠️ Tech Stack  
- **Python** (pandas, NumPy, seaborn, matplotlib)  
- **scikit-learn** (Logistic Regression, LDA, Random Forest, etc.)  
- **Data Preprocessing**: Missing value imputation, feature scaling.  
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-score, ROC-AUC.  

---

## 📸 Visual Insights  

### 1. Churn Distribution  
<p align="center">
  <img src="https://github.com/Viz1303/Customer_Churn_Prediction/blob/main/documents/Churn_M_F.png?raw=true" width="400"/>
</p>  
*Insight*: Roughly **26.5% of customers churned**, while 73.5% stayed. This represents a massive recurring revenue loss if unmanaged.  

---

### 2. Churn by Contract Type  
<p align="center">
  <img src="https://github.com/Viz1303/Customer_Churn_Prediction/blob/main/documents/Churn_contract.png?raw=true" width="500"/>
</p>  
*Insight*: Customers on **month-to-month contracts** churned the most. Incentivizing them to move to **annual or multi-year contracts** could dramatically reduce churn.  

---

### 3. Churn by Payment Method  
<p align="center">
  <img src="https://github.com/Viz1303/Customer_Churn_Prediction/blob/main/documents/Churn_payment.png?raw=true" width="500"/>
</p>  
*Insight*: Customers paying with **electronic checks** churned far more than those using auto-pay or credit cards. Promoting easier, reliable billing options could improve retention.  

---

### 4. Feature Importance (Model Drivers)  
<p align="center">
  <img src="https://github.com/Viz1303/Customer_Churn_Prediction/blob/main/documents/feature.png?raw=true" width="500"/>
</p>  
*Insight*: **Contract type, tenure, and payment method** are the top churn predictors. These are **business-controllable levers**, meaning telecoms can directly act on them.  

---

### 5. Confusion Matrix (Model Performance)  
<p align="center">
  <img src="https://github.com/Viz1303/Customer_Churn_Prediction/blob/main/documents/Confusion_matrix.png?raw=true" width="500"/>
</p>  
*Insight*: The model shows **high recall for churners** (≈89%), meaning it effectively identifies customers most at risk, enabling proactive retention campaigns.  

---

## 🤖 Model Exploration & Results  
We tested multiple ML models (Logistic Regression, LDA, Random Forest, Voting Classifier) with **10-fold cross-validation**:  

- **Logistic Regression**: Accuracy = **81.6%**, ROC-AUC = **0.84**.  
- **Linear Discriminant Analysis (LDA)**: Accuracy = **80.3%**, Sensitivity = **93%** (strong at detecting churners).  
- **Ensemble methods** also performed well, but Logistic Regression was selected for simplicity, interpretability, and efficiency.  

---

## 💡 Business Impact  

1. **Revenue Retention**  
   - Targeting the **26% at-risk customers** with loyalty offers could save millions in subscription revenue annually.  

2. **Targeted Retention Campaigns**  
   - Example: Offer discounts on yearly contracts for high-risk monthly subscribers.  
   - Encourage alternative payment methods for customers flagged as high churn risk.  

3. **Operational Strategy**  
   - Fiber optic service churn suggests **improving service reliability** could reduce dissatisfaction.  
   - Onboarding programs for **new subscribers** could increase retention in the first 6 months.  

4. **Marketing Efficiency**  
   - Instead of blanket promotions, focus on **high-value churn-risk customers**, reducing wasted spend.  

---

## 📝 Lessons Learned  

- Churn prediction is not just about accuracy — it’s about **turning predictions into retention strategy**.  
- Features like contract type, payment method, and tenure are both **predictive and actionable**.  
- Logistic Regression provided the best balance of **interpretability and accuracy**, making it production-ready.  
- The approach is **scalable to other industries** (banking, SaaS, e-commerce) where churn impacts recurring revenue.  

---

✨ **In essence**: This project demonstrates how machine learning can directly **protect revenue, reduce acquisition costs, and extend customer lifetime value**. By predicting who is most likely to leave — and why — telecom providers can move from reactive churn management to proactive retention, creating a measurable impact on profitability.  
