# ☕ Coffee Shop Sales Analysis — Excel Dashboard Project

## Project Overview
This is my **first data analytics project**, where I explored and analyzed real-world business data using **Microsoft Excel**.  
After working for about 2 years in the **pharmaceutical industry**, I realized I wanted more challenges and learning opportunities — so I decided to transition into **data analytics**.  

For this project, I used the **Coffee Shop Sales dataset** provided by **[Maven Analytics](https://mavenanalytics.io/data-playground)**.  
The dataset contains **149,117 transactions** from **January to June 2023** across **3 store locations**.  

The main goal was to analyze sales performance, customer buying patterns, and store revenue, and to design an interactive Excel dashboard that presents clear business insights.

---

## Dataset Information

**Duration:** January – June 2023  
**Records:** 149,117  
**Stores:** 3 locations  

### Columns in the Dataset
| Column | Description |
|---------|-------------|
| transaction_id | Unique ID for each transaction |
| transaction_date | Date of purchase |
| transaction_time | Time of purchase |
| store_id | Store identifier |
| store_location | Store name/location |
| product_id | Product code |
| unit_price | Price per unit |
| transaction_qty | Quantity purchased |
| product_category | Main category (Coffee, Tea, Bakery, etc.) |
| product_type | Product sub-category |
| product_detail | Product name |
| size | Small / Regular / Large |
| total_bill | Total amount per transaction |

---

## Tools & Techniques Used
- **Microsoft Excel**
- **Power Query** (for data cleaning & transformation)
- **Power Pivot** (for measures and KPIs)
- **Pivot Tables & Pivot Charts**
- **Slicers** (for interactivity)
- **Conditional Formatting**
- **Data Storytelling Techniques**

---

## Project Workflow

### 1️⃣ Data Loading
- Imported the raw dataset (`Coffee Shop Sales.csv`) into Excel.  
- Checked and corrected data types (dates, times, numeric values).  
- Verified for missing or duplicate records.

### 2️⃣ Data Cleaning (Power Query)
- Removed duplicate and blank rows.  
- Corrected inconsistent product and store names.  
- Filtered out unnecessary columns.  
- Ensured each column had the correct data type.  
- Loaded the cleaned data into the Excel Data Model.

### 3️⃣ Data Transformation
Created new calculated columns in Power Query:
- **Total Bill** = `Unit Price × Transaction Quantity`
- **Month Name**
- **Day Name**
- **Hour**
- **Day of Week**
- **Month Number**

Reorganized the dataset to make it easier to analyze.

### 4️⃣ Data Modeling (Power Pivot)
Built measures and KPIs in Power Pivot:
- `Total Sales = SUM(Total Bill)`  
- `Total Footfall = COUNT(Transaction_ID)`  
- `Average Order Value = Total Sales / Total Footfall`  
- `Avg Items per Transaction = Total Items Sold / Total Transactions`

### 5️⃣ Dashboard Development
Used **Pivot Tables** and **Pivot Charts** to visualize:
- Monthly Sales Trends  
- Category-wise Sales  
- Product Size Performance  
- Top 5 Best-Selling Products  
- Store-wise Revenue & Footfall  
- Hourly Quantity Ordered  
- Daily Transaction Count  

### 6️⃣ Dashboard Design & Formatting
- Added **Slicers** for Month and Day filters.  
- Used consistent color schemes and clear labels.  
- Applied **conditional formatting** to highlight key data points.  
- Arranged visuals neatly to tell a smooth story.

---

## 📊 Key Metrics
| KPI | Description |
|------|-------------|
| **Total Sales** | Total revenue generated |
| **Total Footfall** | Total number of transactions |
| **Average Order Value (AOV)** | Total Sales ÷ Total Footfall |
| **Avg Items per Transaction** | Total Items Sold ÷ Total Transactions |

---

## Key Insights
1. **Coffee (Small size)** is the most sold product, followed by Tea.  
2. Sales are highest during **morning hours (7 AM – 11 AM)**, then remain steady throughout the day.  
3. Overall **sales and footfall increased month by month** from January to June 2023.  
4. Among all 3 stores, one location consistently performs best in both sales and footfall.  
5. Customers prefer smaller-sized beverages, but larger sizes generate more revenue per order.  
6. The **Average Order Value** stayed consistent, showing stable customer spending patterns.

---

## Dashboard Overview
| Section | Description |
|----------|-------------|
| **KPI Cards** | Shows Total Sales, Total Footfall, AOV, Avg Items per Transaction |
| **Line Chart** | Monthly Sales Trend |
| **Column Chart** | Store-wise Sales Comparison |
| **Donut Chart** | Product Size Distribution |
| **Bar Chart** | Top 5 Products |
| **Hourly Line Chart** | Hourly Sales Pattern |
| **Slicers** | Filters for Month and Day |
| **Daily Transaction Chart** | Daily Customer Footfall |

---

## Learnings
- Gained hands-on experience in **Power Query** for cleaning and shaping data.  
- Built **data models and KPIs** using Power Pivot.  
- Designed a structured **Excel Dashboard** for storytelling.  
- Learned how to interpret and communicate insights through visuals.  
- Strengthened Excel analytics and visualization skills using real-world data.

---

## Project Structure

