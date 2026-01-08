
# 📊 Retail Sales Performance Dashboard 

## 🔍 Project Overview
This is an end-to-end retail sales dashboard built using **Power BI**.  
I created synthetic retail sales data and used it to perform **data cleaning, data modeling, analysis, and visualization**.  
The goal of this project is to convert raw sales data into **interactive dashboards and meaningful business insights** that support decision-making.

---

## 🛠️ Tools & Technologies Used
- Power BI (Dashboard & Visualization)
- Power Query (Data Cleaning)
- DAX (Measures & KPIs)


---
## 📁 Dataset Description
The data used in this project is **synthetic data** created for learning and practice purposes.

Excel files created:
- **Sales.xlsx** – Transaction-level sales data
- **Products.xlsx** – Product and category details
- **Stores.xlsx** – Store, city, state, and region information

Additional table:
- **Date Table** – Created inside Power BI for time-based analysis

## 📂 Repository Structure
```
End-to-End-Retail-Sales-Analysis/
|__ Datasets/
│   |__ Products.xlsx
│   |__ Sales.xlsx
│   |__ Sales Data Cleaned.xlsx
│   |__ Stores.xlsx
│
|__ Power BI/
    |__ Data_Modeling_Star_Schema.png
│   |__ Retail Sales Dashboard.pbix
│   
│
|__ README.md
```



## 🧹 Data Cleaning
Data cleaning was performed using **Power Query** in Power BI.

Key steps included:
- Handling missing values in payment method, unit price, state, and region columns.
- Replacing null values using business logic
- Standardizing data formats (dates, numbers)
- Ensuring data consistency across tables

---

## 🏗️ Data Modeling
A **Star Schema** design was implemented for better performance and clarity.

- **Fact Table**
  - Sales

- **Dimension Tables**
  - Products
  - Stores
  - Date (created in Power BI)

Proper relationships were created to support accurate filtering and time-based analysis.
### 📐 Data Model (Star Schema)
The dashboard follows a star schema design with a central Sales fact table and supporting dimension tables.

![Star Schema Data Model](Power%20BI/Data_Modeling_Star_Schema.png)

----

## 📊 Dashboard Review

The dashboard is designed to be **interactive, user-friendly, and business-focused**.

### Key Features:
- **Main Page**
  - High-level KPIs (Total Quantity, Total Profit)
  - Quarter, Category, and Payment Method slicers
  - Top 5 States by Sales
  - Actual vs Monthly Target performance

- **Bar Analysis Page**
  - Unit Price and Quantity by Region
  - Unit Price Contribution by State
  - Target reference lines for comparison
  - **Tooltips** added to provide extra context on hover

- **Map Page**
  - State and region-wise sales and profit distribution
  - Visual geographic comparison

- **Q&A Page**
  - Natural language question-and-answer feature
  - Enables non-technical users to explore data easily

- **Insights Page**
  - Clear business insights and recommendations
  - Highlights key trends, strong areas, and improvement opportunities

### Navigation:
- Buttons and bookmarks are used to switch between views
- This avoids overcrowding and allows users to focus on what they want to see

---

## 💡 Business Insights
- Q2 and Q4 are the strongest quarters, contributing higher quantity and profit compared to Q1 and Q3
- Food & Beverages is the top-performing category
- Household & Cleaning shows lower performance in both quantity and profit
- Maharashtra, Gujarat, and Tamil Nadu are the leading states by sales
- Gujarat has the highest unit price contribution by state
- North and West regions perform strongly in unit price and quantity

---

## 🎥 Dashboard Walkthrough Video
A short video walkthrough is included to explain:
- Dashboard navigation
- KPIs and charts
- Insights and business interpretation

📌 **Video link:**https://drive.google.com/file/d/1QgL2oqZNExCoWgUXMUbLgoerktKE3n93/view?usp=sharing**

- The video demonstrates page navigation, filters, KPIs, charts, and the insights section of the dashboard.
---


## 🎯 Project Purpose
This project demonstrates:
- End-to-end Power BI development
- Strong understanding of data modeling and visualization
- Ability to translate data into business insights
- Focus on usability for both technical and non-technical users

---


