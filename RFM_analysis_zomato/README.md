# 📊 RFM Analysis on Zomato Customer Data  

## 📖 Table of Contents  
- [📌 Project Overview](#-project-overview)  
- [📊 What is RFM Analysis?](#-what-is-rfm-analysis)  
- [📂 Dataset Description](#-dataset-description)  
- [⚙️ Methodology](#️-methodology)  
  - [1️⃣ RFM Score Calculation](#1️⃣-rfm-score-calculation)  
  - [2️⃣ Customer Segmentation](#2️⃣-customer-segmentation)  
  - [3️⃣ Visualizations](#3️⃣-visualizations)  
- [🔍 Key Insights](#-key-insights)  
- [📊 Recommendations by Segment](#-recommendations-by-segment)  
- [📊 Tableau Dashboard](#-tableau-dashboard)  
- [🛠 Tools & Technologies](#-tools--technologies)  
- [📥 How to Use This Project](#-how-to-use-this-project)  
- [🔮 Next Steps & Future Work](#-next-steps--future-work)  
- [📄 Author](#-author)  

---

## 📌 Project Overview  
With increasing competition in the **restaurant aggregator and delivery industry**, businesses need **precise marketing strategies** to stay competitive. This project performs **Recency, Frequency, and Monetary (RFM) Analysis** on **Zomato customer data** to:  

✔ Identify **high-value customers** for retention strategies.  
✔ Segment customers based on their engagement and spending behavior.  
✔ Optimize **marketing budgets** to focus on the most impactful customer groups.  

The insights from this analysis help tailor **personalized marketing efforts** to improve **customer retention, revenue generation, and engagement strategies**.  

---

## 📊 What is RFM Analysis?  
**RFM Analysis** is a powerful **customer segmentation technique** that evaluates customers based on:  

- **Recency (R)** – How recently a customer made a purchase.  
- **Frequency (F)** – How often a customer makes a purchase.  
- **Monetary (M)** – How much a customer spends over time.  

By scoring customers based on these factors, businesses can:  
✔ Personalize marketing campaigns 🎯  
✔ Improve customer retention strategies 💡  
✔ Identify high-value customers for loyalty programs 👑  

---

## 📂 Dataset Description  
The **Zomato dataset** consists of **customer transaction history**, including:  
- **Customer ID** – Unique identifier.  
- **Order Date** – Used to calculate Recency.  
- **Order Amount** – Used to calculate Monetary value.  
- **Total Purchases** – Used to calculate Frequency.  

Since this dataset is commonly used for training, **Exploratory Data Analysis (EDA) was skipped**, and the focus was on **RFM scoring and segmentation**.  

---

## ⚙️ Methodology  

### 1️⃣ **RFM Score Calculation**  
Each customer was **scored on a scale of 1-5** based on:  
- **Recency** → Days since their last order.  
- **Frequency** → Total number of purchases.  
- **Monetary** → Total spending over their purchase history.  

These scores were combined into a **total RFM score** ranging from **3 to 15**.  

---

### 2️⃣ **Customer Segmentation**  
Customers were grouped into **five segments** based on their **total RFM score**:  

| **RFM Score Range** | **Segment**            | **Description** |
|---------------------|------------------------|----------------|
| **13 - 15**        | **Champions**          | Most engaged and high-spending customers. |
| **10 - 12**        | **Loyal Customers**     | Frequent buyers with strong spending habits. |
| **7 - 9**          | **Potential Loyalists** | Customers with potential for increased engagement. |
| **4 - 6**          | **At-Risk Customers**   | Infrequent buyers who may churn. |
| **< 4**           | **Lost Customers**      | Customers who have stopped engaging. |

---

### 3️⃣ **Visualizations**  
Multiple visualizations were created to **analyze RFM segmentation**:  
✅ **Customer count per segment** – Understanding the distribution of different customer types.  
✅ **Revenue contribution by segment** – Identifying which segments drive the most revenue.  
✅ **RFM Heatmaps** – Comparing Recency, Frequency, and Monetary scores.  
✅ **Monetary score distribution** – Visualizing spending patterns across customers.  

---

## 🔍 Key Insights  

### 📌 **Segment Contribution to Revenue**
- **Champions (9% of customers)** → **Contribute 36% of revenue** 💰  
- **Loyal Customers (44% of customers)** → **Contribute 40% of revenue** ✅  
- **Potential Loyalists (24% of customers)** → **Contribute 21% of revenue** 📈  
- **At-Risk Customers (18% of customers)** → **Contribute only 2% of revenue** 🚨  
- **Lost Customers (5% of customers)** → **Contribute only 0.07% of revenue** ❌  

🚀 **Key Takeaway:** The **top two segments (Champions & Loyal Customers) drive 76% of revenue**, meaning retention efforts should focus on them.  

---

## 📊 Recommendations by Segment  

### 🏆 **Champions (10% of marketing budget)**  
✔ Provide **exclusive loyalty rewards** to maintain engagement.  
✔ Offer **early access** to promotions & new features.  
✔ **Personalized thank-you emails** to strengthen relationships.  

---

### 💙 **Loyal Customers (20% of marketing budget)**  
✔ Focus on **increasing Frequency scores** with targeted promotions.  
✔ Use **personalized offers** to incentivize repeat purchases.  
✔ Leverage **referral programs** to encourage customer advocacy.  

---

### 🌟 **Potential Loyalists (40% of marketing budget)**  
✔ **Biggest growth opportunity** – effort here can **increase revenue significantly**.  
✔ **Regular engagement & reminders** to encourage consistent purchases.  
✔ **Discounts on repeat orders** to improve Frequency scores.  

---

### ⚠️ **At-Risk Customers (25% of marketing budget)**  
✔ **"We Miss You" emails** to re-engage inactive customers.  
✔ **Limited-time offers** to drive immediate action.  
✔ Analyze past behavior to create **tailored reactivation campaigns**.  

---

### ❌ **Lost Customers (5% of marketing budget)**  
✔ **Minimal marketing focus** – low ROI for retention efforts.  
✔ Focus only on **subsegments showing engagement potential**.  
✔ Allow churn while improving retention efforts for other groups.  

---

## 📊 Tableau Dashboard  
🔗 **View the Tableau Dashboard:**  
[Zomato RFM Dashboard](https://public.tableau.com/app/profile/matthew.cook5582/viz/RFMZomato/Dashboard1?publish=yes)  

---

## 🛠 Tools & Technologies  
- **Tableau** – Interactive visualization of customer segmentation.  
- **Excel/CSV** – Data storage & manipulation.  
---
## 📄 Author  
👤 **Matthew Cook**  
📧 Email: matthewcook755@gmail.com  
🔗 LinkedIn: [Here](https://www.linkedin.com/in/matthew-cook-4a92627a/)  


