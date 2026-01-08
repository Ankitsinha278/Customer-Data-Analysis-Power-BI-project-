# 📊 Customer Data Analysis using Power BI

## 🧩 Project Overview
This project focuses on analyzing customer purchasing behavior using retail transaction data. The objective is to convert raw customer data into actionable business insights that help stakeholders understand customer demographics, product performance, revenue drivers, and payment preferences.

An interactive Power BI dashboard was developed to answer key business questions related to gender, age groups, product categories, payment methods, and sales trends.

---

## 🎯 Business Problem Statements
The analysis answers the following business questions:

1. How is the shopping distribution according to gender?
2. Which gender purchased more products?
3. Which gender generated more revenue?
4. What is the distribution of purchase categories?
5. How is shopping behavior distributed across age groups?
6. Which age category purchased more products?
7. Which age category generated more revenue?
8. How do purchase categories relate to other attributes?
9. Does the payment method have a relationship with other variables?
10. What is the overall distribution of payment methods?
11. What insights and recommendations can be provided to the business?

---

## 🗂️ Dataset Description
The dataset contains customer-level transactional data with over 1,000 records.

### Key Attributes:
- Invoice Number  
- Customer ID  
- Gender  
- Age  
- Age Category (Teen, Adult, Senior Citizen)  
- Product Category  
- Quantity  
- Price  
- Revenue  
- Payment Method (Cash, Credit Card, Debit Card)  
- Shopping Mall  
- Invoice Date  
- Month & Year  

---

## 🛠️ Tools & Technologies
- Power BI – Dashboarding, DAX, Data Modeling  
- Power Query – Data cleaning and transformation  
- Excel / CSV – Data source  

---

## 🔄 Data Preparation
- Cleaned and validated raw data  
- Created calculated columns for Revenue, Age Category, and Month-Year  
- Standardized data types for dates, currency, and categorical values  
- Built relationships to enable cross-filtering in dashboards  

---

## 📊 Dashboard Preview

### 🔹 Gender-wise Customer Analysis
![Gender Analysis](images/Gender-Wise.png)
**Insight:** Female customers contribute a higher share of total purchases and revenue compared to male customers.

---

### 🔹 Category-wise Purchase Analysis
![Category Analysis](images/Category-Wise.png)
**Insight:** Clothing and Cosmetics are the top-performing categories in terms of quantity sold and revenue generated.

---

### 🔹 Age Group & Revenue Analysis
![Age Group Analysis](images/AgeCategory-Wise.png)
**Insight:** Adults are the most active shoppers and generate the highest revenue, followed by Senior Citizens.

---

### 🔹 Payment Method Analysis
![Payment Method Analysis](images/Payment_Method.png)
**Insight:** Cash is the most preferred payment method across most shopping malls, while credit cards are more common in premium malls.

---

## 💡 Key Insights
- Female customers dominate both purchase quantity and revenue contribution.
- Adult age group is the most valuable customer segment.
- Clothing and Cosmetics drive the majority of sales.
- Cash payments contribute the highest share of revenue overall.
- 2022 was the strongest business year, while 2023 shows a decline in purchases.
- Teen customers show the lowest purchasing power.

---

## 📌 Business Recommendations
- Introduce targeted promotions to increase male customer engagement.
- Focus marketing efforts on Adult customers to maximize ROI.
- Expand and promote high-performing categories like Clothing and Cosmetics.
- Encourage digital payments through discounts or loyalty rewards.
- Investigate factors behind the decline in customer activity in 2023.
- Create youth-focused offers to improve engagement among Teen customers.

---

## 📂 Repository Structure
```
📁 Customer-Data-Analysis-PowerBI
│── 📁 images
│   ├── Gender-Wise.png
│   ├── Category-Wise.png
│   ├── AgeCategory-Wise.png
│   └── Payment_Method.png
│── 📄 PowerBI_Dashboard.pbix
│── 📄 Customer_Data.csv
│── 📄 README.md
```

---

## 🚀 Conclusion
This project demonstrates the power of data visualization and analytics in driving business decisions. By leveraging Power BI, complex customer data was transformed into meaningful insights that can help optimize sales strategy, customer targeting, and revenue growth.
