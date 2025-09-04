# 📊 Case Study Project: Sales Performance Analysis

## 🎯 Objective
Analyze the sales performance of a retail store using **descriptive statistics** and provide insights into:
- Customer purchasing behavior
- Product performance
- Regional sales performance

---

## 📂 Dataset
**Fields:**
- `Order_ID`
- `Product_Category`
- `Region`
- `Sales` (in ₹ or $)
- `Quantity`
- `Discount`
- `Profit`

📌 If dataset is not available:
- Use a sample dataset from **Kaggle**
- Or create dummy data in **Excel/CSV (~1000 rows)**

---

## 🛠️ Tools & Libraries

### 🔹 Current (Python Analysis)
- **NumPy** → numerical operations  
- **Pandas** → data cleaning & analysis  
- **Matplotlib / Seaborn** → data visualization  
- **SciPy** → advanced statistics (mode, skewness, kurtosis, IQR, etc.)  

### 🔹 Upcoming (Future Work)
- **SQL** → query large datasets (joins, aggregations, filters)  
- **Power BI / Excel** → build dashboards and interactive reports  

---

## 🔍 Steps & Topics Covered (Python)

### 1. Frequency Tables
- Orders by **Product_Category**
- Orders by **Region**

### 2. Histograms
- Distribution of **Sales**  
- Distribution of **Profit**

### 3. Bar Graphs
- Average **sales per region**  
- Total **quantity sold by category**

### 4. Pie Charts
- % contribution of **Product_Category** to total sales  
- % of orders from different **Regions**

### 5. Box Plots
- Outlier detection for **Sales**  
- Compare sales distribution across **Regions**

### 6. Measures of Central Tendency
- Mean, Median (Pandas / NumPy)  
- Mode (SciPy `stats.mode`)  
- Skewness & Kurtosis (SciPy)

### 7. Variation & Range
- Range of **Sales**  
- Variance of **Profit**

### 8. Quartiles & Percentiles
- Q1, Q2, Q3 of **Sales**  
- 90th percentile of **Profit** (top earners)

### 9. Interquartile Range (IQR)
- Detect outliers in **Sales** using `scipy.stats.iqr`

### 10. Standard Deviation
- Standard deviation of **Sales**  
- Interpretation: spread of sales values

---

## 📈 Insights to Add in Report
- Which **region** sells the most?  
- Which **product category** contributes most to revenue?  
- Are **profits** normally distributed or skewed?  
- Which **customers/products** are outliers?  
- Business recommendations:  
  - Focus on **high-profit categories**  
  - Reduce discounts in **low-performing regions**  
  - Optimize inventory based on **demand patterns**

---

## 🚀 Deliverables
- **Jupyter Notebook (Python)** → analysis & visualizations  
- **Future Work:**  
  - SQL queries for dataset preparation  
  - Power BI Dashboard for real-time sales tracking  

---

## 📌 Scope

### ✅ In Scope (Now)
- Descriptive statistics with **Python**  
- Charts & visualizations  
- Outlier detection and insights  

### ❌ Out of Scope (Now)
- Predictive modeling (forecasting, clustering, ML models)  
- Real-time dashboards (will be added in **Power BI phase**)  

---

## 📊 Sample Visualizations (Python)
- Frequency table: `Product_Category`  
- Histogram: Sales distribution  
- Pie chart: Category contribution to revenue  
- Box plot: Sales outliers across regions  

---

## 📌 Next Steps
- Extend project with **SQL queries** (joins, aggregations)  
- Build a **Power BI Dashboard** for visualization  
- Add **predictive analytics** (optional future expansion)  

---

👨‍💻 **Author:** Priyal Patel  
