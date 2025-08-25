# Nike Sales Data Analysis 🏷️📊

## 📌 Project Overview
This project focuses on cleaning, preprocessing, and analyzing Nike Sales Data to uncover key insights and profit trends across Indian cities.

## 🔧 Steps Performed
### 1. Data Cleaning & Preprocessing
- Imported dataset `Nike_Sales_Uncleaned.csv`
- Dropped columns with excessive null values: `Units_Sold`, `Discount_Applied`, `MRP`, `Revenue`
- Filled missing categorical values (`Size`) with `"Unrecorded"`
- Standardized inconsistent `order_date` formats into a single format
- Verified cleaned dataset with exploratory checks and grouped by `Region`

### 2. Data Visualization (Power BI)
- **Profit Trends**:  
  - Profitable cities: *Bangalore, Mumbai, Pune*  
  - Average performance: *Delhi*  
  - Declining performance: *Hyderabad, Kolkata*  
- **Time Analysis**:  
  - Highest profits in *January*  
  - Lowest profits in *October*  
- **Top Products**: Identified top 5 products yielding the highest returns

## 📂 Repository Structure
- DataSets
    - Raw dataset
- Notebooks
   -Jupyter notebooks
- Reports
   -Power BI reports
## 🛠️ Tools & Technologies
- **Python (Pandas, NumPy)**
- **Jupyter Notebook**
- **Power BI**
- **GitHub**

## 📈 Key Learnings
- Handling messy datasets with missing & inconsistent values  
- Standardizing date formats  
- Business insights using visualization tools  
