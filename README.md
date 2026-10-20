# CPI Inflation Analysis in India (2013–2023)

<p align="left">
  <img src="https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" alt="Microsoft Excel" />
  <img src="https://img.shields.io/badge/Data_Cleaning-4472C4?style=for-the-badge&logoColor=white" alt="Data Cleaning" />
  <img src="https://img.shields.io/badge/Data_Transformation-7030A0?style=for-the-badge&logoColor=white" alt="Data Transformation" />
  <img src="https://img.shields.io/badge/Pivot_Tables-00A6A6?style=for-the-badge&logoColor=white" alt="Pivot Tables" />
  <img src="https://img.shields.io/badge/Pivot_Charts-ED7D31?style=for-the-badge&logoColor=white" alt="Pivot Charts" />
  <img src="https://img.shields.io/badge/Data_Visualization-8E44AD?style=for-the-badge&logoColor=white" alt="Data Visualization" />
  <img src="https://img.shields.io/badge/Statistical_Analysis-2E75B6?style=for-the-badge&logoColor=white" alt="Statistical Analysis" />
  <img src="https://img.shields.io/badge/Correlation_Analysis-C00000?style=for-the-badge&logoColor=white" alt="Correlation Analysis" />
  <img src="https://img.shields.io/badge/Time_Series_Analysis-548235?style=for-the-badge&logoColor=white" alt="Time Series Analysis" />
  <img src="https://img.shields.io/badge/Inflation_Trend_Analysis-FFB900?style=for-the-badge&logoColor=black" alt="Inflation Trend Analysis" />
</p>

## Project Overview

This project analyzes India's Consumer Price Index (CPI) data using Microsoft Excel to understand price movements across different consumption categories and geographical sectors.

The analysis explores year-on-year trends, food inflation, broader consumption categories, pre- and post-COVID comparisons, and correlations between fuel prices and selected categories.

The project demonstrates practical skills in data cleaning, data transformation, Excel-based analysis, and economic data interpretation.

## Objectives

- Analyze India's CPI trends from 2013 to 2023.
- Compare Rural, Urban, and Rural + Urban CPI patterns.
- Examine year-on-year changes in the General Index.
- Investigate monthly food price patterns.
- Compare CPI trends before and after COVID-19.
- Analyze relationships between Fuel and Light and other consumption categories.
- Calculate correlations between selected CPI series.
- Generate meaningful insights from historical CPI data.

## Build an interactive Excel report with slicers for year, month, sector, and category.
<img width="461" height="151" alt="image" src="https://github.com/user-attachments/assets/bccb4e35-43e7-4595-b342-740190b9e4bb" />


## Dataset Information

The workbook contains monthly CPI observations covering **January 2013 to April 2023**.

### Dataset Dimensions

- **Time Period:** January 2013 – April 2023
- **Frequency:** Monthly
- **Geographical Sectors:** Rural, Urban, and Rural + Urban
- **Observations:** 372 data rows in the original dataset
- **Consumption Categories:** Multiple food and non-food categories, including cereals, meat and fish, milk, vegetables, fuel and light, transport and communication, education, health, and others.

### Important Variables

| Variable | Description |
|---|---|
| Sector | Geographical classification of the CPI observation |
| Year | Year of observation |
| Month | Month of observation |
| Cereals and Products | CPI index for cereals and related products |
| Meat and Fish | CPI index for meat and fish |
| Milk and Products | CPI index for milk and related products |
| Vegetables | CPI index for vegetables |
| Fruits | CPI index for fruits |
| Fuel and Light | CPI index for fuel and light |
| Transport and Communication | CPI index for transport and communication |
| Education | CPI index for education |
| Health | CPI index for health |
| General Index | Overall CPI index |

The workbook includes additional consumption categories beyond those listed above.

**Note:** CPI index values represent price levels relative to a reference period. They should not be confused with inflation rates, which measure percentage changes in prices over time.

## Workbook Structure

The Excel workbook contains 15 worksheets:

| No. | Worksheet Name | Purpose |
|---:|---|---|
| 1 | Raw Data | Original CPI dataset |
| 2 | CPI Inflation | Main CPI dataset |
| 3 | Main | Working dataset for analysis |
| 4 | CPI Inflation Unpivot | Restructured data for category-wise analysis |
| 5 | Broader Category Wise Inflation | Analysis of broader consumption categories |
| 6 | Year On Year Inflation | Year-wise comparison of CPI patterns |
| 7 | Months Wise Food Inflation | Monthly analysis of food-related categories |
| 8 | Absolute Inflation | Analysis of CPI index levels |
| 9 | Pre and Post Covid Inflation | Comparison of CPI patterns across COVID periods |
| 10 | Fuel vs Transport Correlation | Relationship between fuel and transport and communication |
| 11 | Fuel vs Education Correlation | Relationship between fuel and education |
| 12 | Fuel vs Food Correlation | Relationship between fuel and food and beverages |
| 13 | Fuel vs Cereals Inflation | Relationship between fuel and cereals and products |
| 14 | Fuel vs Non Alcoholic Inflation | Relationship between fuel and non-alcoholic beverages |
| 15 | Correlation | Summary of selected correlation calculations |

## Analysis Performed

### 1. Year-on-Year Analysis
Examines yearly CPI patterns and differences between Rural, Urban, and Rural + Urban sectors.
<img width="1082" height="580" alt="image" src="https://github.com/user-attachments/assets/87a5d49d-c093-47a7-89cb-9aea06828d9e" />

### 2. Broader Category Analysis
Organizes individual consumption items into broader categories to investigate differences in price movements.
<img width="588" height="382" alt="image" src="https://github.com/user-attachments/assets/ebe2b2cc-f3c3-4550-ac17-7a03c9d5b715" />

### 3. Monthly Food Inflation Analysis
Explores monthly variations in food-related CPI categories, including cereals, milk, fruits, vegetables, and pulses.
<img width="1192" height="623" alt="image" src="https://github.com/user-attachments/assets/aea8ae3f-96fd-4fe1-8f45-c1febffea981" />

### 4. Absolute CPI Analysis
Examines CPI index levels across consumption categories to understand how price levels vary over the study period.
<img width="1145" height="610" alt="image" src="https://github.com/user-attachments/assets/4f7bef90-687f-4987-a2c2-1d9cfa346ad9" />

### 5. Pre- and Post-COVID Comparison
Investigates changes in CPI patterns before, during, and after the COVID-19 disruption.
<img width="1048" height="606" alt="image" src="https://github.com/user-attachments/assets/6007504f-3b0e-4e05-8eb1-3c222585ccab" />


### 6. Fuel and Other Category Relationships
Examines relationships between Fuel and Light and selected categories, including transport, education, food, cereals, and non-alcoholic beverages.

6.1. Fuel vs Non-Alcoholic Beverages (69%): Strong positive correlation. Beverage prices closely track fuel costs, with energy hikes translating into higher beverage inflation, especially in 2021 and 2022.
<img width="1888" height="49" alt="image" src="https://github.com/user-attachments/assets/eb14411e-2203-49de-bc13-b2a122925e47" />

<img width="943" height="548" alt="image" src="https://github.com/user-attachments/assets/9fe95270-71dc-419d-b2e3-3928ed376ea8" />

6.2.Fuel vs Transport & Communication (66%): Strong positive correlation. Transport costs rise almost in tandem with fuel, reflecting direct dependence on energy prices. Peaks in 2021 and 2022 highlight this linkage.
<img width="2032" height="49" alt="image" src="https://github.com/user-attachments/assets/135b13dc-c7ee-48fd-b251-94c0fdc29649" />

<img width="1207" height="595" alt="image" src="https://github.com/user-attachments/assets/5d7c90b3-8a2c-4a8e-806b-cb3c58787117" />

6.3.Fuel vs Education (23%): Weak positive correlation. Education costs show steady growth largely independent of fuel volatility, indicating minimal direct influence from energy inflation.
<img width="1761" height="49" alt="image" src="https://github.com/user-attachments/assets/3e42b04e-9dc4-4735-9ef2-b9e6c86f809e" />

<img width="978" height="571" alt="image" src="https://github.com/user-attachments/assets/35874235-ae5c-458c-9a2c-ba46f494f1f8" />

6.4. Fuel vs Food & Beverages (-20%): Weak negative correlation. Food prices often moved opposite to fuel trends, suggesting supply and demand factors outweighed energy costs in driving food inflation.
<img width="1918" height="49" alt="image" src="https://github.com/user-attachments/assets/96e83db2-51c2-487c-8b06-52de210314c2" />

<img width="878" height="547" alt="image" src="https://github.com/user-attachments/assets/381622f9-4766-4a5f-b2fc-1414c4334a5b" />

6.5. Fuel vs Cereals & Products (-24%): Inverse Relationship. Rising fuel costs coincided with declining cereal prices, highlighting that staple food inflation was not directly tied to energy fluctuations.
<img width="1852" height="49" alt="image" src="https://github.com/user-attachments/assets/5e1c8ae0-d5c7-4aaf-ada3-c80aeb91316a" />

<img width="957" height="550" alt="image" src="https://github.com/user-attachments/assets/0bdcc69c-20ce-44de-aae6-c5c3cb18f5a8" />


### 7. Correlation Analysis
Uses correlation calculations to evaluate the strength and direction of relationships between selected CPI series.
<img width="642" height="372" alt="image" src="https://github.com/user-attachments/assets/b44d9a8d-3702-4a9e-a4a9-ed25b2ad1bfe" />

A positive correlation indicates that two series tend to move in the same direction, while a negative correlation indicates that they tend to move in opposite directions. Correlation does not establish causation.

## Tools and Technologies

- **Microsoft Excel** — Data analysis and reporting
- **Excel Formulas** — Calculations and correlation analysis
- **Data Transformation** — Restructuring data into a category-level format
- **PivotTables** — Summarization and comparison of CPI data
- **GitHub** — Project hosting and version control

## Key Takeaways

This project provides a framework for investigating:

- Long-term changes in India's consumer price levels.
- Differences between Rural and Urban CPI patterns.
- Variations in food and non-food category indices.
- Changes in price patterns across pre- and post-COVID periods.
- Relationships between fuel prices and selected consumption categories.

The conclusions should be based on the actual calculations and charts in the workbook rather than assuming that every category follows the same trend.

## How to Use This Project

1. Download or clone this repository.
2. Open `Whole CPI Inflation Project.xlsx` in Microsoft Excel.
3. Navigate through the 15 worksheets.
4. Review the original data and transformed dataset.
5. Explore the analysis sheets to compare CPI categories, sectors, and time periods.
6. Review the correlation calculations and charts to understand the relationships being investigated.

Microsoft Excel is recommended for compatibility with PivotTables, formulas, and other workbook features.

## Repository Structure

```text
CPI-Inflation-Analysis/
│
├── README.md
├── Whole CPI Inflation Project.xlsx
└── screenshots/
    ├── dashboard.png
    └── analysis.png
```

The `screenshots/` folder is optional. Add screenshots of your actual Excel analysis or charts to improve the presentation of your GitHub repository.

## Limitations

- CPI index values are not equivalent to inflation rates.
- Correlation does not prove causation.
- Pre- and post-COVID findings depend on the periods and categories selected.
- Results depend on the accuracy and completeness of the underlying dataset.
- Correlation calculations should be checked for formula errors and consistent date alignment before interpreting the results.

## Author

**Project:** CPI Inflation Analysis in India  
**Domain:** Data Analytics | Economic Analysis  
**Tool:** Microsoft Excel  
**Period Covered:** 2013–2023
