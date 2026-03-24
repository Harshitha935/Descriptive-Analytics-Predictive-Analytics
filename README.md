# 🍷 Understanding Wine Purchasing Behaviour using PCA & Regression

## 🧭 Motivation

Traditional analysis often focuses on surface-level metrics like total spending or demographics.  
In this project, I wanted to go deeper and understand:

> *What truly drives wine purchases — who customers are, or how they behave?*

To answer this, I combined **Principal Component Analysis (PCA)** with **Lasso Regression** to uncover hidden patterns in customer behavior.

---

## 🎯 Objectives

- Identify the key drivers of wine purchasing behavior  
- Reduce high-dimensional customer data into meaningful components  
- Understand whether **behavioral** or **demographic** factors matter more  
- Provide actionable business insights based on model findings  

---

## 🧠 Approach

### 1. Dimensionality Reduction (PCA)

Customer data contains many correlated variables (web activity, purchases, demographics, etc.).  
PCA was used to:

- Reduce dimensionality  
- Extract **latent behavioral patterns**  
- Group related variables into interpretable components  

Each principal component represents a **behavioral theme** rather than a single variable.

---

### 2. Predictive Modeling (Lasso Regression)

Lasso regression was applied to:

- Identify the most important components  
- Reduce noise by shrinking less relevant features  
- Improve interpretability  

---

## 📊 Model Performance & Limitations

- Models explain **~52–61% of variance**
- Error rate is relatively high (~50%)

👉 Interpretation:
- The model is useful for identifying **patterns and drivers**
- Not suitable for precise prediction

This project focuses on **insight generation**, not perfect accuracy.

---

## 🔍 Key Findings

The analysis reveals a clear insight:

> **Wine purchasing is driven more by customer behavior than demographics.**

### Most Important Drivers (by PCA components):

1. **Customer Engagement & Tenure (PC11)**  
   - Frequent interaction with the platform  
   - Longer relationship with the company  
   - Strong response to campaigns  

2. **Multi-Channel Purchasing (PC8)**  
   - Web purchases (strongest signal)  
   - In-store activity  

3. **General Consumption Patterns (PC1)**  
   - Spending across categories (fruits, sweets)  

4. **Product Preferences (PC5)**  
   - Meat and premium product purchases  

5. **Deal Sensitivity & Age (PC2)**  
   - Promotions and age-related behavior  

---

## 🧩 Interpretation

- Engagement and interaction frequency matter more than total spending  
- Customers active across multiple channels are more valuable  
- Wine buyers tend to be **broad spenders**, not niche consumers  
- Behavioral patterns outperform static demographic variables  

---

## 👥 Role of Demographics

Demographics play a **secondary role**:

- Positive signal:
  - Higher education (Master’s, PhD)
- Weak or minimal impact:
  - Household composition  
- Less predictive than behavioral variables  

👉 Key takeaway:
> Who the customer *is* matters less than how they *behave*

---

## 🚫 Features with Low Impact

- Several principal components showed weak or negative relationships  
- Some variables had near-zero importance in the Lasso model  

👉 These features can be deprioritized in decision-making.

---

## 🎯 Target Customer Profile

The ideal wine customer is:

- Highly engaged with the platform  
- Active across multiple purchasing channels  
- A frequent and broad spender  
- More likely to have higher education  

---

## 💡 Business Recommendations

### 1. Increase Customer Engagement
- Personalized communication  
- Loyalty programs  
- Campaign targeting  

### 2. Strengthen Digital Channels
- Improve online experience  
- Promote wine through recommendations  

### 3. Leverage Cross-Selling
- Bundle wine with complementary products (meat, sweets, fruits)  

### 4. Shift to Behavioral Segmentation
- Segment users based on activity and engagement  
- Move beyond demographics  

### 5. Target Specific Segments
- Deal-sensitive customers  
- Premium product buyers  

---

## 📌 Key Insight

> Customer behavior — especially engagement and multi-channel activity — is the strongest predictor of wine purchases.

---

## 🧰 Tech Stack

- Python  
- Pandas & NumPy  
- Scikit-learn (PCA, Lasso Regression)  
- Matplotlib & Seaborn (data visualization and insight generation)


