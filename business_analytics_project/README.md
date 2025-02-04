# 📊 E-Commerce Event Log Analysis: Conversion Funnel & Cohort Retention  

## 📖 Table of Contents  
- [📌 Project Overview](#-project-overview)  
- [📂 Dataset Description](#-dataset-description)  
- [📊 Conversion Funnel Analysis](#-conversion-funnel-analysis)  
- [📊 Cohort Analysis & Retention Tracking](#-cohort-analysis--retention-tracking)  
- [🔍 Key Insights](#-key-insights)  
- [📊 Recommendations & Business Impact](#-recommendations--business-impact)  
- [🛠 Tools & Technologies](#-tools--technologies)  
- [📥 How to Use This Project](#-how-to-use-this-project)  
- [🔮 Next Steps & Future Work](#-next-steps--future-work)  
- [📄 Author](#-author)  

---

## 📌 Project Overview  
This project analyzes **event log data** from an e-commerce company to extract **business metrics** for optimizing conversion and retention. The project focuses on two main objectives:  

1. **Conversion Funnel Analysis** – Evaluating how effectively the website converts visitors into customers.  
2. **Cohort Analysis & Retention Tracking** – Segmenting users based on their first purchase date and tracking their repeat purchases over time.  

The results provide **actionable insights** for improving user engagement, optimizing marketing efforts, and increasing customer retention.  

---

## 📂 Dataset Description  
The dataset consists of **raw transaction logs** from an e-commerce website. Each row represents a **user activity (event)**, including product views, cart additions, and purchases.  

### **Columns in Raw Data (`raw_user_activity`)**:  
- **user_id** – Unique identifier for each customer.  
- **event_type** – User action (`view`, `shopping_cart`, `purchase`).  
- **category_code** – Product category.  
- **brand** – Manufacturer of the product.  
- **price** – Price of the product in USD.  
- **event_date** – Date of user activity.  

Additionally, processed datasets were created:  
- **`conversion_funnel`** – Conversion rates at each stage.  
- **`cohort_analysis`** – Monthly cohort user retention.  
- **`retention_rates`** – Aggregated retention percentages.  

---

## 📊 Conversion Funnel Analysis  
The **conversion funnel** tracks user behavior across three key stages:  

| **Stage**           | **Unique Users** | **Conversion Rate** |
|---------------------|-----------------|---------------------|
| **Viewed Product**  | 10,453           | -                   |
| **Added to Cart**   | 3,036            | **29.04%**          |
| **Completed Purchase** | 1,081        | **35.6%** (Cart → Purchase) / **10.3% Total CR** |

### 🔍 **Key Takeaways:**  
✔ **High drop-off after product views** – Only 29% of users add items to their cart.  
✔ **Cart abandonment is significant** – 64.4% of users do not complete checkout.  
✔ **Overall conversion rate is 10.3%**, indicating potential for optimization.  

---

## 📊 Cohort Analysis & Retention Tracking  
Users were **grouped into cohorts** based on their **first purchase month**, and their repeat purchases were tracked over time.  

### **Sample Cohort Retention Rates:**  
| **Cohort (First Purchase Month)** | **Month 1** | **Month 2** | **Month 3** | **Month 4** |
|-----------------------------------|------------|------------|------------|------------|
| **September 2020**                | 12.5%      | 6.25%      | 0.00%      | 3.1%       |
| **October 2020**                  | 7.49%      | 3.74%      | 0.53%      | 0.53%      |
| **November 2020**                 | 5.46%      | 2.94%      | 0.42%      | 0.00%      |
| **December 2020**                 | 4.43%      | 2.95%      | 0.00%      | 0.00%      |

### 🔍 **Key Takeaways:**  
✔ **Sharp retention decline after the first month** across all cohorts.  
✔ **Later cohorts show lower retention rates**, suggesting possible changes in customer acquisition quality.  
✔ **Average retention rate by Month 4 is near 0%**, indicating a need for improved retention strategies.  

---

## 🔍 Key Insights  
1️⃣ **Only 10.3% of visitors complete a purchase.**  
2️⃣ **Cart abandonment is a major issue**, with only **35.6%** of users proceeding to checkout.  
3️⃣ **Retention rates drop dramatically after Month 1**, with most cohorts losing nearly all customers by Month 4.  
4️⃣ **Later cohorts show declining retention**, suggesting newer customers are **less engaged or lower quality**.  

---

## 📊 Recommendations & Business Impact  
🚀 **How can we improve conversion and retention?**  

### **Improving Conversion Rates**  
✔ Implement **cart abandonment email reminders** for users who leave without purchasing.  
✔ Offer **limited-time discounts** at checkout to increase conversion.  
✔ Optimize **product pages & recommendations** to encourage purchases.  

### **Enhancing Customer Retention**  
✔ Introduce a **loyalty program** to reward repeat purchases.  
✔ Send **personalized email campaigns** based on user behavior.  
✔ Offer **post-purchase incentives** to encourage customers to return.  

---

## 🛠 Tools & Technologies  
- **Google Sheets / Excel** – Data processing, pivot tables, and analysis.  
- **SQL (Optional)** – Data filtering and extraction.  
- **Tableau (Optional)** – Visualizing funnel and cohort analysis.  

---

## 📥 How to Use This Project  
1️⃣ **Access the dataset and analysis**  
   - Open the **Sprint 3 Project.xlsx** file.  
   - Navigate to the **conversion_funnel** and **cohort_analysis** sheets.  

2️⃣ **Understand the metrics**  
   - **Funnel metrics** → Show conversion rates at each stage.  
   - **Cohort analysis** → Tracks customer retention over time.  

3️⃣ **Apply insights**  
   - Use recommendations to **improve conversions & retention**.  
   - Experiment with **A/B testing and marketing optimizations**.  

---

## 🔮 Next Steps & Future Work  
🚀 **Potential Enhancements:**  
- **Predictive modeling** for customer lifetime value (CLV).  
- **Deeper segmentation** of user behavior (e.g., product preferences).  
- **A/B testing** for different retention strategies.  

---

## 📄 Author  
👤 **[Your Name]**  
📧 Email: [YourEmail@example.com]  
🔗 LinkedIn: [Your LinkedIn Profile]  
📂 Portfolio: [Your Portfolio Link]  

