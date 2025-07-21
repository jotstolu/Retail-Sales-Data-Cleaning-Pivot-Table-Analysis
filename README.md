# Retail-Sales-Data-Cleaning-Pivot-Table-Analysis

This project demonstrates a full pipeline for transforming a raw retail sales dataset—spanning cleansing, reshaping, and pivot-based analysis—using Python and spreadsheets.

---

## 🧩 Project Overview

1. **Data Import & Initial Audit**  
   - Load CSV data  
   - Inspect structure, types, missing values  

2. **Cleaning Workflow**  
   - Standardize column names  
   - Handle missing values (e.g., imputation, null removal)  
   - Detect and remove outliers via IQR  
   - Correct inconsistent or malformed entries  

3. **Feature Engineering**  
   - Parse `date` → year, month, day  
   - Categorize stores/items  
   - Flag seasonal peaks and special events  

4. **Pivot Table Analysis**  
   - Summarize sales by store & month  
   - Compare product performance  
   - Identify highest and lowest revenue categories  

---

## 📷 Sample Outputs

![Cleaned Data Table](./screenshots/cleaned_data.png)  
*Before vs. after cleansing effect*

![Pivot Table Summary](./screenshots/pivot_summary.png)  
*Monthly store performance overview*

![Category Trend Chart](./screenshots/category_trend.png)  
*Sales trajectory by item category*

![Seasonal Analysis](./screenshots/seasonality.png)  
*Highlighting seasonal demand patterns*

---

## 📊 Analysis Highlights

- **Data Quality Insights**: Visual reports on missing values and distribution anomalies  
- **Sales Pivot Tables**: Compare daily/monthly stats by store & product  
- **Performance Trends**: Track sales and category behavior over time  
- **Seasonal Signals**: Detect patterns like holiday & weekend spikes  

---
