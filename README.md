\# Retail Sales Performance Analysis



\## 📊 Project Overview



This project analyzes retail sales data to understand sales performance, profitability, customer segments, product performance, regional trends, discount levels, and shipping performance.



The project was built as a Data Analyst portfolio project using Microsoft Excel and Power BI.



The analysis combines data cleaning, exploratory analysis, KPI development, business analysis, DAX measures, and interactive dashboard development.



\---



\## 🎯 Business Objectives



The main objectives of this project are to:



\- Analyze overall sales and profitability

\- Identify high-performing product categories

\- Compare sales and profit across regions

\- Analyze customer segments

\- Identify profitable and loss-making sub-categories

\- Identify top-performing products

\- Analyze the relationship between discount levels and profitability

\- Analyze shipping performance

\- Understand monthly sales trends

\- Create an interactive Power BI dashboard for business reporting



\---



\## 🛠️ Tools \& Technologies



\- Microsoft Excel

\- Power BI

\- DAX

\- Pivot Tables

\- Excel formulas

\- Data Cleaning

\- Exploratory Data Analysis

\- Data Visualization

\- Business Analysis



\---



\## 📁 Dataset



This project uses the \*\*Superstore Dataset\*\*.



\### Dataset Source



Kaggle:



https://www.kaggle.com/datasets/vivek468/superstore-dataset-final



The dataset contains approximately 10,000 retail transaction records with information about orders, customers, products, sales, discounts, profit, and shipping.



The original dataset is not included in this repository. Please obtain it from the original source and review its applicable terms before redistribution.



\---



\## 🧹 Data Preparation



The dataset was prepared and analyzed using Microsoft Excel.



The following steps were performed:



\- Checked for duplicate records

\- Reviewed missing values

\- Corrected date formats

\- Verified numerical data types

\- Verified discount values

\- Created calculated columns

\- Calculated profit margin

\- Calculated days to ship

\- Created an order month field

\- Verified the resulting calculations



\### Calculated Columns



\#### 1. Profit Margin



Profit margin was calculated as:




Profit Margin = Profit / Sales



This measures profit as a percentage of sales for each transaction.



2\. Days to Ship



Days to Ship was calculated as:



Days to Ship = Ship Date - Order Date



This measures the number of days between the order date and ship date.



It represents order-to-ship time, not the final delivery time to the customer.



3\. Order Month



An Order Month field was created from the Order Date to support monthly trend analysis.



Example:



2017-01

2017-02

2017-03

📈 Excel Analysis



Several Pivot Tables and analytical summaries were created in Excel.



Category Analysis



Analyzed:



Sales by Category

Profit by Category

Regional Analysis



Analyzed:



Sales by Region

Profit by Region

Customer Segment Analysis



Analyzed:



Sales by Segment

Profit by Segment

Monthly Analysis



Analyzed:



Monthly Sales

Monthly Profit

Sub-Category Analysis



Analyzed:



Sales by Sub-Category

Profit by Sub-Category

Discount Analysis



Analyzed:



Sales by Discount Level

Profit by Discount Level

Shipping Analysis



Analyzed:



Average Days to Ship

Sales by Ship Mode

📊 Power BI Dashboard



The Power BI report contains two analytical pages.



Page 1 — Retail Sales Performance Dashboard



The executive overview contains the following KPIs:



Total Sales

Total Profit

Total Orders

Overall Profit Margin

Average Order Value

Total Quantity

Average Shipping Days

Visualizations

Monthly Sales Trend

Sales by Category

Profit by Category

Sales by Region

Interactive Filters

Year

Region

Category

Segment



These slicers allow users to interactively explore the dashboard.



Page 2 — Product \& Category Analysis



The second page provides deeper product and profitability analysis.



Visualizations

Sales by Sub-Category

Profit by Sub-Category

Top 10 Products by Sales

Top 10 Products by Profit

Sales vs Profit by Sub-Category

Profit by Discount Level

Average Shipping Days by Ship Mode

Interactive Filters

Region

Category

📌 Key Performance Results



Based on the analyzed dataset:



KPI	Result

Total Sales	$2.30M

Total Profit	$286.40K

Total Orders	\~5K

Total Quantity	37,873

Overall Profit Margin	12.47%

Average Shipping Days	3.96 days

🔎 Key Findings

Overall Performance



The analyzed dataset generates approximately $2.30M in total sales and $286.40K in total profit, resulting in an overall profit margin of approximately 12.47%.



Category Performance



Technology generates the highest sales and total profit among the three major product categories.



Regional Performance



The West region has the highest total sales and profit among the four regions.



Customer Segment



The Consumer segment contributes the highest sales and profit among the three customer segments.



Sub-Category Performance



Phones generate the highest sales among the analyzed sub-categories.



Tables and Bookcases have negative total profit in the analyzed dataset.



Discount \& Profitability



Higher discount levels are associated with weaker total profitability in the dataset.



This is an observed association and does not by itself establish that higher discounts cause lower profit.



Further analysis would be required to determine the factors behind this relationship.



Shipping Performance



Standard Class has the longest average order-to-ship time, while Same Day has the shortest.



The shipping metric used in this project is:



Ship Date - Order Date



Therefore, it measures order-to-ship time rather than final customer delivery time.



💡 Business Questions for Further Investigation



The analysis identified several areas that could be investigated further:



Why do Tables and Bookcases generate negative profit?

Are high discount levels concentrated in particular products?

Are high discounts concentrated in particular regions?

Which products contribute the most profit within Technology?

How does discounting vary across customer segments?

Do shipping patterns vary across regions?

Which products have high sales but relatively weak profitability?

📷 Dashboard Preview

Executive Overview



Product \& Category Analysis



📂 Project Structure

Retail-Sales-Performance-Analysis/

│

├── README.md

│

├── data/

│   └── README.md

│

├── excel/

│   └── Retail\_Sales\_Analysis.xlsx

│

├── powerbi/

│   └── Retail\_Sales\_Dashboard.pbix

│

└── screenshots/

&#x20;   ├── dashboard-overview.png

&#x20;   └── product-category-analysis.png

📚 Skills Demonstrated



This project demonstrates practical skills in:



Data Cleaning

Microsoft Excel

Excel Formulas

Pivot Tables

Exploratory Data Analysis

KPI Analysis

Profitability Analysis

Power BI

DAX

Interactive Dashboards

Slicers and Filters

Top-N Analysis

Data Visualization

Business Insight Generation

🚀 Project Outcome



This project demonstrates an end-to-end retail data analysis workflow:



Raw Dataset

&#x20;    ↓

Data Cleaning

&#x20;    ↓

Excel Analysis

&#x20;    ↓

KPI Development

&#x20;    ↓

Exploratory Analysis

&#x20;    ↓

Power BI Modeling

&#x20;    ↓

DAX Measures

&#x20;    ↓

Interactive Dashboard

&#x20;    ↓

Business Insights



The project was created as an independent Data Analyst portfolio project to demonstrate practical data analysis and visualization skills.



👨‍💻 Author



Built as a Data Analyst portfolio project.





\---



\# 2. Dataset README — `Retail-Sales-Performance-Analysis/data/README.md`



Now create a \*\*second file\*\* inside the `data` folder.



Copy \*\*everything below\*\* into that file:



```markdown

\# Dataset



\## 📊 Dataset Name



Superstore Dataset



\## 🔗 Source



The dataset used in this project was obtained from Kaggle:



https://www.kaggle.com/datasets/vivek468/superstore-dataset-final



\## 📋 Dataset Description



The Superstore dataset contains approximately 10,000 retail transaction records.



The dataset contains information related to:



\- Orders

\- Customers

\- Products

\- Categories

\- Sub-Categories

\- Regions

\- Sales

\- Quantity

\- Discounts

\- Profit

\- Shipping



\## 📌 Main Fields



Important fields used in this project include:



\- Row ID

\- Order ID

\- Order Date

\- Ship Date

\- Ship Mode

\- Customer ID

\- Customer Name

\- Segment

\- Country

\- City

\- State

\- Postal Code

\- Region

\- Product ID

\- Category

\- Sub-Category

\- Product Name

\- Sales

\- Quantity

\- Discount

\- Profit



\## 🔧 Dataset Preparation



The dataset was imported into Microsoft Excel and prepared for analysis.



The preparation included:



\- Duplicate checking

\- Data type verification

\- Date formatting

\- Numerical field verification

\- Discount verification

\- Calculated columns

\- Profit margin calculation

\- Days to Ship calculation

\- Order Month creation



\## 📁 Original Dataset



The original dataset is not included in this GitHub repository.



To reproduce the analysis, obtain the dataset directly from the original Kaggle source and place the downloaded data in this folder if required.



Please review the dataset's applicable license and terms before redistributing the original data.



\## 🎓 Usage



This dataset was used for educational, analytical, and portfolio development purposes.



All analysis, calculations, dashboards, and business insights in this repository were created as part of this project.

