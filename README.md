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

## Outputs

**Before vs. after cleansing effect**

![Cleaned Data Table](https://github.com/jotstolu/Retail-Sales-Data-Cleaning-Pivot-Table-Analysis/blob/main/data_cleaning/before_and_after_cleaning.png?raw=true)  

![Cleaned Data Table_2](https://github.com/jotstolu/Retail-Sales-Data-Cleaning-Pivot-Table-Analysis/blob/main/data_cleaning/before_and_after_cleaning2.png?raw=true)

**Monthly store performance overview**
![Pivot Table Summary](https://github.com/jotstolu/Retail-Sales-Data-Cleaning-Pivot-Table-Analysis/blob/main/data_cleaning/Monthly%20Net%20Sales%20Summary.png?raw=true)  


**Sales trajectory by item category**
![Category Trend Chart](https://github.com/jotstolu/Retail-Sales-Data-Cleaning-Pivot-Table-Analysis/blob/main/data_cleaning/Net%20Sales%20vs.%20Total%20Sales%20by%20Product%20Category.png?raw=true)  

![Seasonal Analysis](./screenshots/seasonality.png)  
*Highlighting seasonal demand patterns*

---

## 📊 Analysis Highlights

- **Data Quality Insights**: Visual reports on missing values and distribution anomalies  
- **Sales Pivot Tables**: Compare daily/monthly stats by store & product  
- **Performance Trends**: Track sales and category behavior over time  
- **Seasonal Signals**: Detect patterns like holiday & weekend spikes  

---
