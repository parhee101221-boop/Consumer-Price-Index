<div align="center">

# Consumer Price Index (CPI) Analysis
### Exploring India’s Price-Level Trends | 2013–2023

**An Excel-based data analytics case study on long-term CPI movement, category contribution, year-over-year change, month-over-month change, and pre-/post-COVID patterns.**


![Excel](https://img.shields.io/badge/Tool-Microsoft%20Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Focus-Data%20Analytics-0F766E?style=for-the-badge)
![Period](https://img.shields.io/badge/Period-2013--2023-1D4ED8?style=for-the-badge)

</div>

---

## 1. 📌 Project Overview

This project analyzes India’s Consumer Price Index (CPI) data from **January 2013 to April 2023** to understand how the general price level changed over time and how different consumer categories contributed to the analysis.

The workbook compares Rural, Urban, and Rural+Urban index series and includes focused analysis of annual trends, monthly movement, category-level patterns, pre- and post-COVID periods, and possible relationships with fuel and light prices.

> **Important distinction:** CPI measures changes in the price level relative to a base period; inflation refers to the rate at which that price level changes over time.

## 2. 🔍 Key Insights

- **Long-term increase:** The Rural+Urban General Index annual average rose from approximately **110.03 in 2013** to **177.62 for the available 2023 data**, an increase of about **61.4%**.
- **2023 is a partial year:** The dataset available in this workbook covers January–April 2023, so its average should not be treated as a full-year result.
- **Food is the largest category in the workbook’s contribution analysis:** It accounts for **44.44%** of the category-index total used in this analysis.
- **Luxury and Clothing** are the next largest categories in that contribution summary, at **14.81%** and **11.11%**, respectively.
- **Rural and Urban CPI series** can be compared to explore whether price-level movements differ across sectors.

*Contribution percentages above describe the workbook’s analytical calculation; they are not official CPI expenditure weights or a direct measure of each category’s contribution to inflation.*

## 3. 🛠️ Tools and Techniques

- **Microsoft Excel** — data organization, calculations, summaries, and reporting.
- **Power Query** — data cleaning, reshaping, and transformation where applied.
- **PivotTables** — category, year, month, and sector summaries.
- **Excel formulas and percentage calculations** — year-over-year (YoY), month-over-month (MoM), and contribution analysis.
- **Charts and dashboard design** — communicate trends and comparisons visually.
- **Data interpretation** — turn summary outputs into clear findings while noting limitations.

## 4. 🔄 Workflow

1. **Understand the dataset** — review the CPI fields, time period, categories, and sector labels.
2. **Prepare the data** — check data types, arrange month/year fields, and structure category columns for analysis.
3. **Summarize the index** — calculate yearly and monthly averages and compare Rural, Urban, and Rural+Urban series.
4. **Analyze movement** — review annual trends, YoY changes, MoM changes, and pre-/post-COVID patterns.
5. **Explore categories** — compare category index levels and calculate the contribution percentages used in the workbook.
6. **Build visualizations** — present the main findings using charts and dashboard summaries.
7. **Validate and document** — check calculations, describe partial-year coverage, and avoid interpreting correlation as proof of causation.

## 5. 📈 Visualizations

### Y=O-Y CPI Trand
<img width="500" height="200" alt="image" src="https://github.com/user-attachments/assets/36cb724f-f776-42eb-a5cd-e85593d5e08a" />


### Category Contribution Summary

![Category contribution](visualizations/category_contribution.png)

Food is the largest category in the workbook’s contribution calculation. These percentages are based on the category-index total used in this analysis and should not be confused with official CPI weights.

### Rural vs Urban Comparison

![Rural and Urban comparison](visualizations/rural_urban_comparison.png)

This comparison helps review how the General Index has moved across Rural, Urban, and Rural+Urban series over the available period.

## 6. 💡 Challenges and Learning

- Organizing month and year fields into a reliable time sequence.
- Reshaping category-level data for comparison and analysis.
- Distinguishing a **price index level** from a **rate of inflation**.
- Interpreting partial-year data without making an unfair full-year comparison.
- Understanding that correlation between fuel prices and another category does not, by itself, establish causation.
- Presenting numerical findings with context, definitions, and caveats.

## 7. 🚀 Future Improvements

- Add a fully interactive Excel dashboard with slicers for year, sector, and category.
- Extend the dataset with the latest official CPI releases.
- Add a clearly defined inflation-rate analysis alongside the index-level analysis.
- Compare category movements using official CPI weights where available.
- Document the source URL, release date, base year, and data definitions.
- Rebuild the dashboard in Power BI for interactive filtering and richer drill-down analysis.

## 8. 🗂️ Repository Structure

```text
Consumer-Price-Index-Analysis/
├── README.md
├── Consumer Price Index.xlsx
└── visualizations/
    ├── annual_cpi_trend.png
    ├── category_contribution.png
    └── rural_urban_comparison.png
```

*Update the workbook filename in this structure if your uploaded file has a different name in the GitHub repository.*

## 9. 📚 Data Source

- **Dataset:** All-India Consumer Price Index data included in the project workbook.
- **Coverage:** January 2013 to April 2023 in the available dataset.
- **Series:** Rural, Urban, and Rural+Urban; General Index and category-level indices.
- **Source attribution:** The original download URL/publisher citation was not recorded in the workbook available for this analysis. Before public submission, add the original official source link and any applicable usage notes. Do not present the workbook itself as the original data publisher.

## 10. 👩‍💻 Author

**Heena Parthesh Shah**  
*Data Analytics Learner | Excel | Data Cleaning | Data Visualization*

This project demonstrates practical skills in data preparation, exploratory analysis, Excel reporting, visualization, and insight communication.

---

<div align="center">

**Turning price data into meaningful insights.**

</div>

