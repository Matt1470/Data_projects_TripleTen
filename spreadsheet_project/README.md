# 🏙️ NYC Airbnb Market Analysis: Identifying Top Rental Investments  

## 📖 Table of Contents  
- [📌 Project Overview](#-project-overview)  
- [📂 Dataset Description](#-dataset-description)  
- [🏘️ Neighborhood & Property Size Analysis](#-neighborhood--property-size-analysis)  
- [💰 Revenue Analysis & Top Listings](#-revenue-analysis--top-listings)  
- [🔍 Key Insights](#-key-insights)  
- [📊 Recommendations & Business Impact](#-recommendations--business-impact)  
- [🛠 Tools & Technologies](#-tools--technologies)  
- [📥 How to Use This Project](#-how-to-use-this-project)  
- [🔮 Next Steps & Future Work](#-next-steps--future-work)  
- [📄 Author](#-author)  

---

## 📌 Project Overview  
This project analyzes the **Manhattan vacation rental market** using **Airbnb data** to help investors identify the most **profitable neighborhoods and property types**.  

### **Key Objectives:**  
1️⃣ Identify **which neighborhoods** and **property sizes** are most attractive for short-term rentals.  
2️⃣ Estimate **how much revenue** top-performing listings generate.  
3️⃣ Provide **data-driven recommendations** for investment decisions.  

The analysis uses **Airbnb reviews, availability, and revenue estimates** to assess listing performance.  

---

## 📂 Dataset Description  
The dataset consists of **Airbnb listings and booking data**, structured across multiple sheets:  

### **Key Data Tables**:  
- **`listings`** – Contains Airbnb listings with **property details, neighborhoods, reviews, and revenue data**.  
- **`calendar`** – Tracks **daily availability and pricing** for listings.  
- **`Revenue by Bedroom`** – Summarizes revenue based on **property size**.  
- **`Top 10 Revenue`** – Identifies the highest-earning listings.  
- **`Neighborhood Trends`** – Shows the most attractive neighborhoods.  

Additional documentation includes:  
- **`data_dictionary`** – Column definitions.  
- **`Change Log`** – Steps taken for **data cleaning and modifications**.  

---

## 🏘️ Neighborhood & Property Size Analysis  
The first step in the analysis was identifying:  
✔ **Top neighborhoods for vacation rentals** (based on the number of reviews).  
✔ **Most popular property sizes** (number of bedrooms).  
✔ **How preferences vary by neighborhood**.  

### **🏙️ Top 3 Most Attractive Neighborhoods:**  
Based on Airbnb reviews, the **top neighborhoods** for short-term rentals are:  
1️⃣ **Lower East Side**  
2️⃣ **Hell’s Kitchen**  
3️⃣ **Harlem**  

### **🏠 Most Popular Property Sizes:**  
- **Studios** → 441 listings.  
- **1-Bedroom Apartments** → 1,265 listings.  
- **2-Bedroom Apartments** → 526 listings.  

### **📍 Neighborhood-Specific Property Preferences:**  
- **Harlem:** **1-bedroom apartments** are the most popular rental type.  
- **Midtown:** **Studio apartments** are in the highest demand.  

---

## 💰 Revenue Analysis & Top Listings  
To estimate **profitability**, we analyzed Airbnb revenue using **pricing and availability** data from the `calendar` sheet.  

### **📊 Revenue Calculation Process:**  
1️⃣ **Calculate daily revenue** → `adjusted_price` × number of booked nights.  
2️⃣ **Estimate monthly revenue** → Sum **30 days of revenue** for each listing.  
3️⃣ **Project annual revenue** → Multiply **monthly revenue by 12**.  

### **🏆 Highest-Earning Listing:**  
- **Listing ID:** **49946551**  
- **30-Day Revenue:** **$29,940**  
- **Estimated Annual Revenue:** **$359,280**  

### **💰 Average Estimated Annual Revenue for Top Listings:**  
Using the **top 10 listings**, we projected their **annual revenue** to identify the most profitable investments.  

---

## 🔍 Key Insights  
1️⃣ **The Lower East Side, Hell’s Kitchen, and Harlem** are the **most attractive neighborhoods** for vacation rentals.  
2️⃣ **1-Bedroom apartments** are the most profitable size, except in **Midtown**, where **studios** dominate.  
3️⃣ **Top listings generate over $350,000 annually**, proving the potential profitability of short-term rentals.  
4️⃣ **Revenue potential varies significantly** based on **neighborhood and property type**, highlighting the need for **targeted investments**.  

---

## 📊 Recommendations & Business Impact  
🚀 **How can investors maximize profitability?**  

### **✔ Neighborhood Investment Strategy**  
✔ **Invest in 1-bedroom properties** in Harlem, Hell’s Kitchen, and the Lower East Side.  
✔ **Consider studio apartments** for high-demand areas like Midtown.  

### **✔ Pricing & Revenue Optimization**  
✔ **Dynamic pricing strategies** should be applied to increase earnings.  
✔ **Optimize listings based on seasonality** to maximize occupancy rates.  

### **✔ Marketing & Booking Strategy**  
✔ **Enhance listing descriptions and visuals** to attract more bookings.  
✔ Use **Airbnb promotions and discounts** to boost occupancy rates during off-peak months.  

---

## 🛠 Tools & Technologies  
- **Google Sheets / Excel** – Data processing, pivot tables, and analysis.  

---

## 📥 How to Use This Project  
Link to the project is [here](https://docs.google.com/spreadsheets/d/1M-ZBPEPxK7ZKf9OeMbnx3YGgg3jFiNIgPl8JXoOwDYo/edit?usp=sharing)
1️⃣ **Open the dataset** → Navigate to the `listings` and `calendar` sheets.  
2️⃣ **Explore the pivot tables** → Review revenue trends by bedroom and neighborhood.  
3️⃣ **Check investment recommendations** → Use insights to make **data-driven decisions**.  


---

## 📄 Author  
👤 **Matthew Cook**  
📧 Email: matthewcook755@gmail.com  
🔗 LinkedIn: [Here](https://www.linkedin.com/in/matthew-cook-4a92627a/)  

