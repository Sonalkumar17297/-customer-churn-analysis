# -customer-churn-analysis
Customer Churn Prediction using  ML | Python | Scikit-learn | Pandas
#  Customer Churn Prediction

## 📌 Project Overview
Built an ML pipeline to predict customer churn
using Python achieving 85%+ accuracy

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## 📊 Dataset
- Customer records with features like:
 Tenure 	City_Tier 	CC_Contacted_LY 	Payment 	Gender 	Service_Score 	Account_use
- Target: Churn (Yes/No)

## 🔍 Key Steps
1. Data Cleaning & EDA
2. Feature Engineering
3. Model Building
4. Model Evaluation
5. Business Insights

## 📈 Results
- Best Model: Random Forest
- Accuracy: 80%+

## 💡 Business Impact
Identified key factors causing churn

---

## 🔍 Key Insights from Feature Importance (Random Forest)

### 📊 Feature Insights
- 🔴 Subscribers with **no recharge in last 90 days** 
  should be treated as churned and targeted immediately
- 💰 **Cashback offers** should be provided to customers 
  whose last transaction was 2-3 months ago
- 📞 **CC Agent Score** is a critical factor — needs 
  improvement for better customer satisfaction
- 📲 **Number of customer calls** is an important 
  indicator of potential churn
- 🏙️ **City Tier 2** needs more focus as very few 
  customers are retained there
- 👥 Number of **Male customers > Female customers**
- ⭐ Higher service scores are concentrated 
  on a 3-point scale

---

## 💡 Recommendations to Prevent Customer Churn

### 🎯 Customer Segment Strategy
- **Super and Super Plus** account segments are 
  major customers — prioritize retention offers 
  based on their transaction history
- Customers with **tenure between 1-8 months** 
  need special offers to prevent early churn
- More than **80% of churning customers** gave 
  service score 2 or 3 — immediate action needed

### 📈 Service Quality Improvements
- **CC Agent Score** feedback shows ratings of 
  1 and 2 (lowest) — major cause of dissatisfaction
- Improving service quality directly reduces churn risk

### 🚀 Business Recommendations
| Strategy | Action |
|---|---|
| **Targeted Promotions** | Personalized offers based on customer history |
| **Long Term Contracts** | Incentivize customers to commit longer |
| **Combo Offerings** | Bundle multi-services for min 3 months |
| **OTT Content** | Discover content preferences to increase engagement |
| **Loyalty Program** | Boost subscriber loyalty to reduce churn risk |

---

## 🏆 Business Impact
> Implementing these recommendations can help retain 
> at-risk customers, improve service scores, and 
> reduce overall churn rate significantly.

## 👤 Author
Sonal Kumar
