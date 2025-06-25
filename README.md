# 📊 Apple_Sales_2024_Data_Analysis_with_Pandas


This project is about analyzing apple product using python 

I used a CSV file called `apple_sales_2024.csv` which includes sales data for iphones, ipads, Mac, Wearable and service revenue from different regions and states 

---


## 🛠 What I Used
- **Pandas** – for data analysis   
- **Google Colab** – to write and run the code  

## 🔍 What I Did

### 1. **Loaded the Data**
I used `read_csv()` to load the dataset and explored it using basic functions like:
- `head()`, `tail()` to look at the first/last rows  
- `info()` and `describe()` to understand the structure and stats  

### 2. **Cleaned the Data**
- Filled missing values with 0  
- Removed duplicate rows  
- Renamed columns to simpler names like `iphone_sales`  
- Replaced text values like "Europe" with "EU"  
- Converted some columns to float for easier calculations  

### 3. **Filtered & Selected Data**
- Selected specific columns like `Region`, `iphone_sales`  
- Filtered rows where iPhone sales were greater than a number  
- Used conditions to filter based on region or state  

### 4. **Sorted & Indexed Data**
- Sorted rows by sales  
- Changed the index to use the `State` column  
- Reset the index when needed  

### 5. **Grouped & Aggregated Data**
- Grouped data by Region and State  
- Calculated sum, average, min, max for sales  
- Created pivot tables and crosstabs for summary tables  

### 6. **Merged & Joined Datasets**
- Merged Apple sales with another CSV (Samsung sales)  
- Used different join types like left, right, outer, and inner joins  
- Stacked two datasets side by side and vertically  

### 7. **Calculated and Transformed Data**
- Found total units sold by adding multiple columns  
- Used functions like `mean()`, `max()`, `min()`, `std()`  
- Created new columns using `apply()` and `lambda` functions  
- Performed row-wise and column-wise math operations  

---

## ✅ What You Can Learn from This
- Basics of data analysis using Python  
- How to clean, filter, and group real-world datasets  
- How to use pandas functions to explore and summarize data  
- How to prepare your data for visualization or further analysis
