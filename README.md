# 🚗 Vehicle Market Analytics Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?logo=powerbi)
![MySQL](https://img.shields.io/badge/MySQL-Database-blue?logo=mysql)
![ETL](https://img.shields.io/badge/ETL-Data%20Pipeline-green)
![Data Analytics](https://img.shields.io/badge/Data-Analytics-orange)

## 📊 Project Overview

This project demonstrates an **end-to-end data analytics pipeline** where multiple **CSV datasets were processed using an ETL workflow**, stored in **MySQL**, and visualized using an **interactive Power BI dashboard**.

The goal of this project was to analyze **vehicle market trends, sales distribution, fuel types, and model performance** to generate actionable insights.

---

# ⚙️ Project Workflow

```
CSV Files
   │
   ▼
ETL Process
(Extract → Transform → Load)
   │
   ▼
MySQL Database
   │
   ▼
Master Table Creation
   │
   ▼
Power BI Connection
   │
   ▼
Interactive Dashboard
```

---

# 📂 Data Source

The dataset was originally stored in **multiple CSV files** containing vehicle market data.

### Dataset Includes

- Vehicle Brand
- Vehicle Model
- Fuel Type
- Transmission Type
- Sales Data
- Year
- Pricing Information

---

# 🔄 ETL Process

The ETL pipeline was used to prepare and consolidate the data before analysis.

### 1️⃣ Extract
- Imported multiple **CSV datasets**
- Loaded raw data into the ETL environment

### 2️⃣ Transform
Performed data transformation such as:

- Data cleaning
- Removing duplicates
- Data type standardization
- Handling missing values
- Data normalization

### 3️⃣ Load
- Loaded the cleaned dataset into a **MySQL database**
- Created a **Master Table** combining all processed datasets

---

# 🗄 Database (MySQL)

After transformation, the cleaned data was loaded into **MySQL**.

### Key Steps

- Created database schema
- Imported ETL processed data
- Built a **Master Table** for analytics

This **Master Table** was used as the primary data source for the Power BI dashboard.

---

# 📈 Power BI Dashboard

The **Power BI dashboard** was connected directly to the **MySQL master table** to visualize insights.

### Dashboard Highlights

✔ Total Cars Analyzed  
✔ Total Sales Revenue  
✔ Total Vehicle Models  
✔ Fuel Type Distribution  
✔ Brand Analysis  

---

# 📊 Dashboard Visualizations

### KPI Cards
- Total Cars: **50,000**
- Total Sales: **1.30M**
- Total Models: **10**
- Total Fuel Types: **5**
- Total Brands: **10**

### Charts Included

📊 **Cars by Fuel Type**  
Shows distribution of vehicles across fuel types:
- Diesel
- Electric
- CNG
- Hybrid
- Petrol

📊 **Sales by Year**
Comparison of sales performance across years.

📊 **Cars by Model**
Breakdown of vehicle distribution by model.

📊 **Manual vs Automatic**
Transmission type distribution.

---

# 🖼 Dashboard Preview

![Vehicle Dashboard](https://github.com/mayankyaduvnsi/Vehicle-Market-Analysis-Dashboard/blob/main/Vehicle_Market_Dashboard.png)

---

# 💡 Key Insights

- Diesel and Electric vehicles dominate the market share.
- Vehicle sales remained consistent across multiple years.
- Manual and Automatic transmissions have nearly equal distribution.
- Multiple models contribute evenly to the total market share.

---

# 🛠 Tech Stack

| Tool | Purpose |
|-----|------|
| CSV Files | Raw data source |
| ETL Tool | Data extraction & transformation |
| MySQL | Data storage & querying |
| Power BI | Dashboard visualization |

---

## 👨‍💻 Author

**Mayank Yadav**  
Aspiring Data Analyst | Power BI Enthusiast  

---

## ⭐ If you like this project

Give it a ⭐ on GitHub and feel free to connect!
