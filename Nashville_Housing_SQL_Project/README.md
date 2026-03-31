# Nashville Housing Data Cleaning (SQL Project)

## Project Overview
This project focuses on cleaning and preparing housing data using SQL. The dataset contains property sales information from Nashville, and the goal is to make the data clean, consistent, and ready for analysis.

---

## Tools Used
- Microsoft SQL Server  
- SQL (Structured Query Language)  

---

## Dataset
- **Name:** Nashville Housing Data  

- **Contains information such as:**
  - Property Address  
  - Owner Address  
  - Sale Price  
  - Sale Date  
  - Legal Reference  

---

## Data Cleaning Steps

### 1️⃣ Standardising Date Format
- Converted the `SaleDate` column into proper `DATE` format  
- Created a new column `SaleDateConverted`  

---

### 2️⃣ Handling Missing Values
- Found missing `PropertyAddress` values  
- Used self join to fill missing addresses based on matching `ParcelID`  

---

### 3️⃣ Splitting Address Columns
- Split `PropertyAddress` into:
  - `PropertySplitAddress`  
  - `PropertySplitCity`  

- Split `OwnerAddress` into:
  - `OwnerSplitAddress`  
  - `OwnerSplitCity`  
  - `OwnerSplitState`  

---

### 4️⃣ Data Formatting
- Replaced:
  - `Y` → `Yes`  
  - `N` → `No`  
- Applied on `SoldAsVacant` column  

---

### 5️⃣ Removing Duplicates
- Used `ROW_NUMBER()` with CTE  
- Identified duplicate records  
- Kept only unique rows  

---

### 6️⃣ Dropping Unnecessary Columns
- Removed unused columns:
  - `OwnerAddress`  
  - `TaxDistrict`  
  - `PropertyAddress`  
  - `SaleDate`  

---

## Final Result
- Clean and structured dataset  
- Ready for data analysis or visualization  
- Improved data quality and consistency  

---

## What I Learned
- Data cleaning using SQL  
- Using JOINs to handle missing data  
- String functions like `SUBSTRING` and `PARSENAME`  
- Using CTE and `ROW_NUMBER()` for duplicate removal  
- Writing efficient and readable SQL queries  

---

## Project Files
- SQL Script (Data Cleaning Queries)  

---


## Future Improvements
- Perform data analysis and visualization  
- Connect with Power BI or Tableau  
- Build dashboard from cleaned data  
