# 📊 Data Analytics Project: End-to-End Analysis & Visualization

## 📌 Project Overview
This project focuses on analyzing **e-commerce customer behavior** to understand purchasing patterns, customer demographics, and factors influencing buying decisions.

Using **Python, MySQL, and Power BI**, the project follows a complete data analytics workflow — from raw data exploration and cleaning to SQL-based analysis and interactive dashboard visualization.

The insights from this analysis can help businesses improve:
- Customer segmentation
- Marketing strategies
- Product recommendations
- Retention and loyalty programs

---

## 🛠️ Tech Stack
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn  
- **Database:** MySQL  
- **BI Tool:** Power BI  
- **Environment:** Jupyter Notebook  

---

## 🔄 Project Workflow

### 1️⃣ Data Loading & Inspection (Python)
- Loaded dataset using **Pandas**
- Checked:
  - Dataset shape
  - Data types
  - Missing values
  - Duplicate customer records

---

### 2️⃣ Exploratory Data Analysis (EDA)
Performed EDA to uncover customer behavior patterns:
- Purchase amount distribution
- Category-wise and item-wise sales
- Customer demographics (age, gender, location)
- Purchase frequency analysis
- Impact of discounts and promo codes
- Review rating trends

Visualizations used:
- Histograms & box plots
- Bar charts
- Category-level comparisons

---

### 3️⃣ Data Cleaning & Preprocessing
Key steps included:
- Handling missing values
- Converting categorical and numerical data types
- Standardizing column names
- Ensured data consistency for SQL ingestion

---

### 4️⃣ SQL Analysis (MySQL)
The cleaned dataset was imported into **MySQL** for structured analysis.

- Performed analysis using:
  - `GROUP BY`
  - `JOIN`
  - `CTE`
  - `WINDOW FUNCTIONS`
  - `ROW_NUMBER()` for deduplication

Example insights extracted:
- High-value customer segments
- Most popular product categories
- Repeat vs one-time buyers
- Revenue contribution by demographics

---

### 5️⃣ Power BI Dashboard
An **interactive Power BI dashboard** was created using the MySQL database.

Dashboard features:
- KPIs: Total Customers, Total Revenue, Avg Purchase Value
- Category-wise sales analysis
- Customer demographics breakdown
- Filters for location, gender, and subscription status
- Purchase frequency trends

Dashboard enables:
- Quick decision-making
- High-level business insights
- Drill-down analysis

<img width="1134" height="623" alt="Screenshot 2025-12-28 005012" src="https://github.com/user-attachments/assets/65d391c7-f4e2-4f70-95f8-d3eba62a365f" />

---

## 📈 Key Insights
- Certain product categories drive higher revenue
- Repeat customers contribute significantly to total sales
- Discounts and promo codes influence purchase frequency
- Buying behavior varies across age groups

---

## 🚀 How to Run This Project

### Prerequisites
- Python 3.x
- MySQL Server
- Power BI Desktop

### Steps
1. Clone the repository
   ```bash
   git clone https://github.com/AkshatSaroha/Customer_behavior_analysis.git
2. Run the Jupyter Notebook
   ```bash
   jupyter notebook main.ipynb
3. Import the cleaned dataset into MySQL
4. Execute queries from EDA.sql
5. Open customer_behavior.pbix in Power BI Desktop

---

## 🎯 Future Enhancements
- Churn prediction using machine learning
- Automated ETL pipeline
- Real-time dashboard deployment

---

## 👤 Author
Akshat Saroha
📧 Email: sarohaakshat@gmail.com
💼 LinkedIn: 
   
