# Supermarket Sales Data Analysis

### Project Overview
This project involves the analysis of supermarket sales data from three branches in Myanmar. The goal is to assess, clean, and analyze the data to derive meaningful business insights and recommendations for optimizing sales performance across different cities and product categories.

---

## Project Files
1. **Supermarket_report.pbix** - Power BI report containing visualizations and insights derived from the supermarket sales data.
2. **Data Wrangling Report.pdf** - Detailed report on the data wrangling process, including data cleaning and preparation techniques.
3. **Key_Business_Insights.pdf** - Business insights report containing key findings, trends, and recommendations based on the analysis of sales data.
4. **capstone_project_wrangling.ipynb** - Python notebook used for data wrangling, including data cleaning and transformation steps.

---

## Objectives
1. **Data Wrangling**:
   - Assess and clean the data to ensure its quality for analysis.
   - Fix issues like missing values, duplicate rows, inconsistent formats, and incorrect data types.

2. **Business Insights**:
   - Analyze sales trends, customer behavior, and preferences based on city, gender, and product category.
   - Provide actionable recommendations for targeted marketing, promotions, and customer engagement strategies.

---

## Data Wrangling Summary
- **Source**: The data is from three branches in Yangon, Naypyidaw, and Mandalay.
- **Key Issues**:
  - Multiple branches were represented as separate columns.
  - Missing values in columns like `Tax 5%` and `Total`.
  - Negative values in the `Quantity` column.
  - Inconsistent time formatting.
  - Incorrect customer types and duplicate rows.
  
- **Solutions Implemented**:
  - Merged branch columns into a single `city` column.
  - Calculated missing values for `Tax 5%` and `Total`.
  - Removed duplicate rows.
  - Standardized the `Time` column and corrected customer type misspellings.
  - Fixed other data type inconsistencies for accurate analysis.

For detailed data wrangling steps, [Data Wrangling Report](https://github.com/georgeemiL787/Full-Data-analysis-project--capstone-/blob/43344b5f257579fc2f6b1fdbd7f3331b00326a8e/Data%20Wrangling%20Report.pdf)

---

## Key Business Insights
The analysis highlights several trends and patterns across various dimensions:

### 1. Gender-Based Preferences:
- Females are more interested in Fashion Accessories and Sports and Travel.
- Males show higher interest in Health and Beauty and Electronic Accessories.

### 2. City-Specific Preferences:
- **Yangon**: Morning purchases are common, with a preference for Home and Lifestyle.
- **Mandalay**: Evening purchases dominate, and customers prefer Health and Beauty products.
- **Naypyidaw**: Afternoon purchases are popular, with the most interest in Sports and Travel.

### 3. Category-Based Insights:
- **Fashion Accessories** have the highest customer ratings.
- **Health and Beauty** has underperformed compared to other categories.
- **Home and Lifestyle** is the least popular.

### 4. Sales Trends:
- Sales peak at specific times: 11 AM, 3 PM, and 7 PM for Food and Beverages.
- January had the highest sales of the past three months, followed by March and February.

For more insights and trends, [Key_Business_Insights report](
https://github.com/georgeemiL787/Full-Data-analysis-project--capstone-/blob/7c3f759a55f855d921e5f30b28c00ff97a376de1/Key_Business_Insights.pdf
)

And for thee visual report, [Power bi-Supermarket_report](
https://github.com/georgeemiL787/Full-Data-analysis-project--capstone-/blob/8709d69a34dbf8a7613d3d0595c543e3e186a8a6/Power%20bi-Supermarket_report.pbix
)


---

## Recommendations
1. **Targeted Marketing**: Focus promotions on low-performing categories like Health and Beauty and Home and Lifestyle.
2. **Optimizing Timing**: Schedule promotions during peak shopping hours to drive sales.
3. **City-Specific Campaigns**: Tailor marketing strategies for each city based on purchase behavior.
4. **Membership Programs**: Encourage membership enrollment through exclusive deals to boost customer loyalty.

---

## Technologies Used
- **Power BI**: For visualizations and dashboard creation.
- **Python**: For statistical analysis and data cleaning.
- **Excel**: Initial data storage and format before loading into the analytical tools.

---

## Conclusion
This analysis offers a comprehensive understanding of customer preferences and sales performance across various product categories. By implementing the suggested marketing strategies and optimizing sales processes, the supermarket can enhance customer satisfaction, increase revenue, and improve overall business performance.

---
This file conderd as a summery for the work we done for more details check the documentation and thanks.
