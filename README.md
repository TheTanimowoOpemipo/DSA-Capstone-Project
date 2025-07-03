# Amazon Product Review Analysis using Excel

## Overview  
This project was based on a dataset containing Amazon product reviews. My goal was to clean the data, explore it using Excel, and answer key business questions through analysis and visual insights. I used Excel features like pivot tables, formulas, and charts to summarize the data and build a simple dashboard.

## Tools Used  
- Microsoft Excel  
- Pivot Tables  
- Formulas (`IF`, `COUNTIF`, `AVERAGEIF`)  
- Basic Charts (Bar, Column, Pie)

## Objective  
The task was to understand product performance based on reviews and pricing. I analyzed things like average discounts, most reviewed products, product rating patterns, and how prices were distributed across categories.

## Key Steps

### 1. Data Cleaning  
I started by removing duplicate entries and rows with missing data. Some product categories were shown as long paths, so I focused on the main category to simplify the analysis.  
*You can add screenshots of the raw and cleaned data here if needed.*

### 2. Pivot Table Analysis  
I created several pivot tables to answer specific questions:
- Average discount by product category  
- Most reviewed products  
- Highest-rated products  
- Review counts by price range  

[All Pivot](https://github.com/user-attachments/files/21039287/All.Pivot.analysis.and.answers.to.all.question.as.analysed.xlsx)

### 3. Dashboard Creation  
I combined the most useful charts and KPIs into one dashboard sheet. This included bar and pie charts showing category performance, top-rated products, and review count comparisons.  
![Amazon_Dashboard](https://github.com/user-attachments/assets/5f449eeb-b54c-4705-bdb9-2f704823f8a9)

## Questions Answered

**Q1. What is the average discount by product category?**  
Answer: 

**Q2. Which product got the most reviews?**  
Answer: _[Insert top product name or ID]_

**Q3. Which products had the highest average ratings?**  
Answer: _[Top 3 products]_

**Q4. How are the products priced?**  
Answer: Most products fell into mid-to-high price ranges. I grouped them into:
- Under 1000
- 1000 to 10000
- Over 10000

**Q5. Do ratings change by price range?**  
Answer: _[Insert observation — e.g., higher prices = better ratings, or no clear trend]_

## What I Learned  
This was a great exercise in using Excel to work with raw data and extract useful insights. I got better at using pivot tables for summaries and formulas for deeper analysis. I also practiced organizing results into a simple dashboard for easy interpretation and reporting.

---

*Note: Screenshots and dashboard file can be added to this repository for visual reference.*










# Palmoria Group HR Analytics Dashboard (Power BI)

## Overview  
Palmoria Group is a manufacturing company dealing with HR issues related to gender imbalance, performance gaps, and salary inequality across regions and departments. The company needed a detailed analysis to uncover these issues and take corrective actions.

This project involved analyzing employee data using Power BI. I cleaned and prepared the data, built relationships between tables, and created a multi-page dashboard to help management understand patterns in gender distribution, performance, salary structure, and bonus allocation.

## Tools Used  
- Power BI Desktop  
- Power Query  
- Data Modeling (Relationships, Measures, DAX)  
- Custom Columns and Calculated Fields  
- Stacked Bar Charts, Pie Charts, KPI Cards, and Slicers

## Objective  
To help Palmoria’s management team identify HR challenges like gender imbalance, pay gaps, and compliance with salary regulations. The final deliverable was a 4-page interactive Power BI dashboard with charts, metrics, and filters.

## Key Steps

### 1. Data Cleaning  
- Removed employees without salary (former staff)  
- Removed rows with NULL departments  
- Handled missing or undisclosed gender values  
- Converted performance ratings from text to numeric values  
- Created additional fields like Salary Bands and Join Keys for lookup  
*Screenshots of Power Query transformation steps can be added here.*

### 2. Data Modeling  
- Built relationships between the main employee table and a bonus rules table  
- Used a custom `JoinKey` (Department + Rating) to match bonus rules  
- Created calculated columns using DAX for Bonus Amount and Total Pay  
*Diagram of the data model can be uploaded here.*

### 3. Dashboard Development (4 Pages)

#### Page 1: Gender Overview  
- Overall gender distribution  
- Gender breakdown by department and region  
- Employee count summary

#### Page 2: Performance & Ratings  
- Rating distribution by gender  
- Average rating per department  
- Optional slicers for filtering by region or department

#### Page 3: Salary Insights  
- Salary band distribution (grouped by $10K)  
- Salary band by region  
- Average salary by gender (company-wide, by region, and by department)  
- Compliance check for $90K minimum wage (KPI card and employee count)

#### Page 4: Bonus Allocation  
- Bonus amount by region  
- Total bonus payout card (company-wide)  
- Total pay (salary + bonus) chart  
- Optional slicers by department or rating

*Screenshots of each dashboard page can be added here.*

## Key Measures and Calculations  
- **Bonus Amount** = Bonus % × Salary  
- **Total Pay** = Salary + Bonus  
- **Employees Below 90K** = Count of employees earning less than regulation threshold  
- **Salary Band** = Grouping by $10K ranges for visual distribution  
*You can include DAX snippets or screenshots of formulas here.*

## Questions Answered

**Q1. What is the gender distribution across the organization, departments, and regions?**  
Answer: Visualized using pie and stacked bar charts on Page 1.

**Q2. How do performance ratings differ by gender?**  
Answer: Page 2 shows rating averages per gender.

**Q3. Is there a gender-based salary gap? If yes, where?**  
Answer: Found in the salary visuals on Page 3, broken down by region and department.

**Q4. Are salaries compliant with the $90,000 minimum regulation?**  
Answer: Yes/No (based on result). The dashboard displays count of employees below $90K and the distribution by region.

**Q5. How are bonuses allocated, and what is the total payout?**  
Answer: Page 4 shows total bonuses, per region, and per employee.

## What I Learned  
This project taught me how to take raw HR data and turn it into interactive business insights using Power BI. I practiced advanced Power Query transformations, DAX formulas, and dashboard design across multiple pages. I also learned how to model relationships between tables and deal with real-world data challenges like duplicates, NULLs, and missing joins.

---

*Note: Screenshots of the dashboard pages, PBIX file, and bonus rules table can be added to this repository for full reference.*
