#  CPI Inflation Analysis in India (2013–2023)

##  Project Overview

This project analyzes **Consumer Price Index (CPI) trends in India from January 2013 to May 2023** using Microsoft Excel. It explores changes in price indices across rural, urban, and combined rural–urban sectors and examines how inflation patterns differ across major expenditure categories.

The project uses data cleaning, data transformation, PivotTables, charts, year-wise and month-wise comparisons, pre- and post-COVID analysis, and correlation analysis to identify meaningful patterns in India's consumer price indices.

The objective is to understand long-term price movements, identify categories with substantial index increases, and explore relationships between fuel and other expenditure categories.

##  Project Objectives

* Analyze long-term CPI trends in India from 2013 to 2023.
* Compare CPI movements across rural, urban, and rural–urban combined sectors.
* Examine inflation patterns across major expenditure categories.
* Study year-on-year and month-wise variations in CPI indices.
* Compare food inflation across different months and years.
* Analyze pre-COVID and post-COVID price index trends.
* Investigate correlations between fuel and light and other expenditure categories.
* Present findings through Excel PivotTables, charts, and analytical summaries.

##  Dataset Description

The project workbook contains CPI data organized by sector, year, month, and expenditure category.

**Dataset coverage:**

* **Time period:** January 2013 – May 2023
* **Original dataset:** 372 observations
* **Columns:** 30
* **Sectors:** Rural, Urban, and Rural+Urban
* **Data format:** Monthly CPI index values

The workbook also contains a transformed, unpivoted dataset with approximately 10,044 records, making it easier to analyze individual expenditure categories.

### Major Variables

| Variable                     | Description                                 |
| ---------------------------- | ------------------------------------------- |
| Sector                       | Rural, Urban, or Rural+Urban                |
| Year                         | Year of observation                         |
| Month                        | Month of observation                        |
| General Index                | Overall consumer price index                |
| Food and Beverages           | CPI index for food and beverage expenditure |
| Fuel and Light               | CPI index for fuel and lighting expenses    |
| Health                       | CPI index for healthcare expenditure        |
| Education                    | CPI index for education-related expenditure |
| Transport and Communication  | CPI index for transport and communication   |
| Clothing and Footwear        | CPI index for clothing and footwear         |
| Household Goods and Services | CPI index for household expenditure         |

The dataset includes additional categories such as cereals, meat and fish, eggs, milk, fruits, vegetables, pulses, housing, recreation, personal care, and miscellaneous expenditure.

**Note:** CPI index values represent price levels relative to a reference base; they should not be interpreted directly as percentage inflation rates. Percentage inflation requires comparing index values across periods.

##  Tools and Technologies

* **Microsoft Excel** — Data preparation, analysis, and visualization
* **Excel PivotTables** — Aggregation and category-wise comparisons
* **Excel Charts** — Visual representation of CPI trends
* **Excel Formulas** — Percentage change and correlation calculations
* **Data Transformation (Unpivoting)** — Restructuring the dataset for category-level analysis

##  Project Structure

The Excel workbook is organized into the following analytical sheets:

| Sheet                             | Purpose                                                   |
| --------------------------------- | --------------------------------------------------------- |
| `Raw Data`                        | Original CPI dataset                                      |
| `CPI Inflation`                   | CPI data prepared for analysis                            |
| `Main`                            | Main working dataset                                      |
| `CPI Inflation Unpivot`           | Restructured data for category-level analysis             |
| `Broader Category Wise Inflation` | Distribution of observations across broader categories    |
| `Year On Year Inflation`          | Annual CPI comparisons across sectors                     |
| `Months Wise Food Inflation`      | Monthly comparisons of selected food categories           |
| `Absolute Inflation`              | Category-wise CPI index comparisons                       |
| `Pre and Post Covid Inflation`    | Comparison of selected indices across the COVID-19 period |
| `Fuel vs Transport Correlation`   | Relationship between fuel and transport indices           |
| `Fuel vs Education Correlation`   | Relationship between fuel and education indices           |
| `Fuel vs Food Correlation`        | Relationship between fuel and food indices                |
| `Fuel vs Household Correlation`   | Relationship between fuel and household indices           |
| `Fuel vs Clothing Inflation`      | Relationship between fuel and clothing indices            |
| `Fuel vs Health Inflation`        | Relationship between fuel and health indices              |
| `Fuel vs Recreation Inflation`    | Relationship between fuel and recreation indices          |
| `Fuel vs Fuel`                    | Comparison of fuel and light with non-alcoholic beverages |

##  Analysis Performed

### 1. Year-on-Year CPI Analysis

Compared annual average general index values across rural, urban, and combined sectors to understand long-term changes in consumer price levels.

### 2. Category-Wise Analysis

Examined CPI movements across food, clothing, education, fuel and light, health, transport, housing, and other expenditure categories.

### 3. Monthly Food Index Analysis

Compared monthly index values for milk and products, vegetables, fruits, and pulses to identify differences in their price movements.

### 4. Pre- and Post-COVID Comparison

Examined the trends in food and beverages, health, and household goods and services across the years surrounding the COVID-19 period.

### 5. Fuel Correlation Analysis

Investigated the relationships between changes in fuel and light indices and selected expenditure categories using correlation analysis.

## 📈 Key Findings

The following observations are based on the values and correlation coefficients displayed in the workbook.

* **Long-term increase in CPI:** The annual average general index rises over the years covered by the analysis, indicating a substantial increase in consumer price levels.
* **Differences across sectors:** Rural and urban CPI index levels vary by year and expenditure category, highlighting the importance of sector-wise comparisons.
* **Food category representation:** Food accounts for approximately 44.44% of the observations in the unpivoted dataset, making it a major component of the project's category-level analysis.
* **Monthly variation in food indices:** Vegetables, fruits, milk, and pulses show different monthly and yearly index patterns.
* **Pre- and post-COVID trends:** The workbook enables comparisons of selected expenditure categories before and after the onset of COVID-19, although these comparisons alone do not establish that COVID-19 caused the observed changes.
* **Fuel and transport correlation:** The workbook reports a correlation coefficient of approximately **0.66**, indicating a positive relationship in the analyzed series.
* **Fuel and recreation correlation:** The reported coefficient is approximately **0.58**, indicating a moderate positive relationship.
* **Fuel and clothing correlation:** The reported coefficient is approximately **0.42**, indicating a moderate positive relationship.
* **Fuel and health correlation:** The reported coefficient is approximately **0.40**, indicating a moderate positive relationship.
* **Fuel and household expenditure correlation:** The reported coefficient is approximately **0.31**, indicating a relatively weak positive relationship.
* **Fuel and education correlation:** The reported coefficient is approximately **0.23**, indicating a weak positive relationship.
* **Fuel and food correlation:** The reported coefficient is approximately **-0.20**, indicating a weak negative relationship in the analyzed series.

*Correlation coefficients describe statistical relationships, not causation. Their interpretation depends on the variables, time periods, and calculation method used.*

##  Business and Economic Insights

This project demonstrates how CPI data can be used to:

* Monitor changes in consumer price levels over time.
* Compare price movements between rural and urban populations.
* Identify expenditure categories that deserve closer monitoring.
* Explore relationships between different consumer expenditure indices.
* Support economic reporting and data-driven decision-making.
* Communicate complex economic data through charts and summary tables.

##  How to Explore the Project

1. Clone or download this GitHub repository.
2. Open the Excel workbook in Microsoft Excel.
3. Start with the `Raw Data` sheet to understand the dataset.
4. Review the `CPI Inflation Unpivot` sheet to understand the transformed data.
5. Explore the PivotTables and charts in the analytical sheets.
6. Compare sector-wise trends, monthly patterns, pre- and post-COVID indices, and correlation results.

## 📌 Limitations

* The analysis is limited to the data and time period available in the workbook.
* CPI index movements do not necessarily represent the same rate of inflation across all categories.
* Correlation does not imply causation.
* A pre- and post-COVID comparison does not isolate the causal effect of the pandemic.
* Results depend on the accuracy of the source data and the calculations used in the workbook.

##  Future Improvements

* Create an interactive Power BI dashboard.
* Add year-on-year and month-on-month inflation rate calculations.
* Develop a more detailed rural-versus-urban comparison.
* Add statistical significance tests and time-series analysis.
* Extend the analysis with newer CPI observations.
* Include a data source citation and a separate data dictionary.

##  Skills Demonstrated

* Data Analysis
* Data Cleaning and Transformation
* Microsoft Excel
* PivotTables and PivotCharts
* Data Visualization
* Exploratory Data Analysis (EDA)
* Correlation Analysis
* Economic Data Interpretation
* Analytical Reporting

##  Disclaimer

This project is intended for educational and analytical purposes. The findings describe patterns in the CPI index data included in the workbook and should not be interpreted as official economic forecasts or proof of causal relationships.

## Conclusion

The CPI Inflation Analysis project demonstrates how Microsoft Excel can be used to explore long-term consumer price index movements, compare rural and urban sectors, study expenditure categories, and investigate relationships between selected price indices.

It provides a foundation for further economic analysis and demonstrates practical data analytics skills through data transformation, PivotTables, charts, and statistical comparisons.

---

**If you find this project useful, consider giving the repository a star!** ⭐
