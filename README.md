# Adventure Works Shaping And Combining Data – Power BI Project

## Project Overview
This project demonstrates how to create Power BI reports using **Excel sales data from multiple regions**. The aim is to empower business analysts to build dashboards in Power BI Service and explore self-service BI capabilities.

## Objective
- Import and transform sales data from **Europe** and **North America** Excel files.  
- Shape, clean, and combine data to create a unified dataset.  
- Prepare the data for analysis and reporting in Power BI.  

## Tools Used
- **Power BI Desktop**  
- **AdventureWorks Excel files**:  
  - sales-Europe.xlsx  
  - sales-North America.xlsx  
  - country code.xlsx  

## Tasks Completed

### Importing Data from Excel
1. Opened **Power BI Desktop**.  
2. Imported **sales-Europe Excel file** and loaded the Europe table.  
3. Imported **sales-North America Excel file** and opened it in **Power Query Editor**.  

### Shaping and Combining Data
1. Selected **Europe** table in the Queries pane.  
2. Removed unnecessary columns: `ProductKey` and `SalesOrderNumber`.  
3. Renamed columns:  
   - `SalesTerritoryCountry` → `Country`  
   - `SalesTerritoryGroup` → `Sales Territory`  
   - `EnglishProductCategoryName` → `Main Category`  
   - `EnglishProductSubcategoryName` → `Sub Category`  
   - `EnglishProductName` → `Product`  
4. Moved the `Color` column to the left.  
5. Repeated steps 1–4 for the **North America** table.  
6. Appended **Europe** and **North America** tables to create a unified dataset.  
7. Imported **country code.xlsx** and merged it with the Europe dataset.  
8. Extracted `Country Code` from the merged column and moved it to the beginning.  
9. Renamed the column `Code` → `Country Code`.  
10. Saved the transformed dataset as **Shaping and Combining Data.pbix**.

## Key Learnings
- How to import and transform Excel data in Power BI.  
- Removing unnecessary columns and renaming for clarity.  
- Combining multiple regional datasets using **Append Queries**.  
- Merging additional reference tables (e.g., country codes) into main datasets.  
- Preparing data for analysis and self-service reporting in Power BI.

## Conclusion
The project demonstrates the process of shaping, combining, and cleaning sales data from multiple regions. The unified dataset enables business analysts to build meaningful dashboards in Power BI Service, supporting self-service BI capabilities.

## File
- **Shaping and Combining Data.pbix** – Power BI report containing the transformed and combined dataset.
