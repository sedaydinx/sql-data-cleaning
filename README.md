# Layoffs Data Cleaning

**Database:** MySQL  
**Focus:** Duplicates, standardization, null handling  

## Objective
Clean the layoffs dataset to create a consistent and analysis-ready table.

## Steps
1. Remove duplicates (`ROW_NUMBER` + `DELETE`)  
2. Standardize data (`TRIM`, country and industry fixes)  
3. Handle null and empty values  
4. Drop unnecessary columns (`row_num`)  

## SQL Features
- CTE (`WITH duplicate_cte AS …`)  
- Window functions (`ROW_NUMBER() OVER(...)`)  
- `JOIN` to fill missing values  
- `ALTER TABLE`, `UPDATE`, `DELETE`  

## Files
- `data_cleaning.sql` → main SQL script
