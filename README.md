<div align="center">

📊 Retail Sales Data Analysis in Excel
A spreadsheet-based project exploring retail transactions, sales performance, products, payment methods, and regional patterns.



</div>

📌 Project Overview
This project uses a retail sales workbook to practise spreadsheet-based data analysis. It explores transaction records and compares sales across product categories, individual products, payment methods, and regions. It also includes an analysis-and-calculation worksheet for practising filters and conditional calculations.
The project focuses on turning raw rows into information that is easier to interpret through summaries, calculations, and charts.
🎯 Objectives
- Understand the structure of a transaction-level retail dataset.
- Practise sorting, filtering, and working with multiple conditions.
- Calculate and compare sales and quantities.
- Explore product, category, payment-method, and regional performance.
- Present findings with charts and readable summary tables.
- Identify the limits of the available spreadsheet environment and document possible next steps.
🗂️ Workbook Structure
Worksheet	Purpose
Dataset	Transaction-level source data
Analysis & Calculation	Analysis, calculations, summaries, or visualisations as named in the worksheet
Data Visualisation	Analysis, calculations, summaries, or visualisations as named in the worksheet


📁 Dataset at a Glance
Item	Details
Dataset rows	250
Dataset columns	20
Unique transaction IDs	250
Total quantity recorded	753
Sum of Total_Amount	229,192.47
Date range	11 Apr 2024 – 11 Apr 2025
Date coverage	11 Apr 2024 – 11 Apr 2025


Main fields
The workbook includes transaction and customer details, product information, sales values, and grouping fields. Depending on the source columns, these include:
- Transaction fields: transaction ID and date
- Customer fields: customer ID/name, customer segment, and customer-since information
- Product fields: product ID/name, category, and product abbreviation
- Sales fields: quantity, unit price, and total amount
- Grouping fields: payment method and region
📈 Visual Analysis
The following charts are generated from the dataset to make comparisons easier to understand.
1. Sales by Product Category
<img width="645" height="465" alt="Screenshot 2026-10-17 112118" src="https://github.com/user-attachments/assets/2c9bcec5-023c-4f56-be0d-8d665810079e" />

This comparison helps identify which categories account for the largest share of recorded sales.
2. Sales by Product

This chart compares total sales for individual products and helps highlight products with higher recorded revenue.
3. Sales by Payment Method

This view compares the sales total associated with each payment method. It describes the records in the dataset; it does not, by itself, explain why customers choose a method.
4. Sales by Region

This comparison helps explore differences in recorded sales across regions.
Note: These charts summarise the provided data. They are descriptive views, not proof of causation or forecasts of future sales.
<img width="645" height="465" alt="Screenshot 2026-10-17 112118" src="https://github.com/user-attachments/assets/09ae2ccd-9685-48dd-b7a2-ab65df99b42c" />
<img width="1017" height="550" alt="Screenshot 2026-10-17 112212" src="https://github.com/user-attachments/assets/ce956429-90d8-4e63-9497-de6b6d402ff2" />
<img width="700" height="513" alt="Screenshot 2026-10-17 112134" src="https://github.com/user-attachments/assets/5cd7d0dc-10f9-483b-b7ab-8e81e7f7eb9a" />

🧮 Analysis and Spreadsheet Techniques
The workbook provides practice with:
- Sorting and filtering transaction records
- Applying more than one condition to filter data
- Reviewing transactions above a selected amount
- Comparing sales by category and region
- Summarising quantities and total sales
- Using chart-based visualisation to communicate patterns
- Working with customer and date-related fields for further analysis
💻 Tools and Working Environment
Excel for the web
I completed this project using Excel for the web because Microsoft Excel was not installed on my desktop computer. This allowed me to work with the spreadsheet online without needing the desktop application.
However, the web version available to me did not provide the What-If Analysis tools I needed, and it also did not offer the Linear Regression workflow/functionality I intended to use for the project. As a result, I could not complete those particular advanced-analysis steps in the same way I would have attempted them in the desktop version or a dedicated statistical tool.
I have documented this limitation rather than presenting those analyses as completed. The current workbook focuses on the analysis and visualisations that were feasible in my available environment.
Why this limitation matters
- What-If Analysis can be used to explore how changing input values affects a result, for example, how a change in price or quantity might affect revenue.
- Linear regression can be used to examine a linear relationship between variables and, when its assumptions and data suitability are considered, estimate outcomes.
- These are different techniques: What-If Analysis explores scenarios, while regression estimates relationships from data.
⚠️ Limitations
- The project was completed in Excel for the web, where the required What-If Analysis option was unavailable in my working environment.
- The intended linear-regression analysis could not be completed with the tools available in that environment.
- The charts are descriptive; no predictive model is claimed in this README.
- Findings depend on the quality, completeness, and representativeness of the supplied dataset.
- If the workbook data changes, summaries and charts should be checked or refreshed as appropriate.
- Customer names or other identifying fields should be anonymised before publishing real customer data publicly.
🚀 Future Improvements
If the required tools become available, this project could be extended by:
1. Completing What-If Analysis scenarios for changes in price, quantity, or costs.
2. Performing linear regression on suitable numerical variables and evaluating the model rather than relying on the fit alone.
3. Adding monthly and quarterly sales trends.
4. Comparing average transaction value across customer segments and regions.
5. Building an interactive dashboard with slicers and pivot charts.
6. Validating the data for missing values, duplicates, and inconsistent entries.
7. Reproducing advanced analysis in desktop Excel, Python, or another suitable statistics tool.
▶️ How to Explore the Project
1. Download the Excel workbook from this repository.
2. Open it in Excel for the web or a compatible spreadsheet application.
3. Start with the source-data worksheet to understand the columns.
4. Review the analysis/calculation worksheet for filtering and formula examples.
5. Explore the visualisation worksheet and the charts included in assets/.
6. Use the future-improvements section as a guide for extending the project.
📦 Repository Structure
.
├── README.md
├── Final Project (1).xlsx
└── assets/
    ├── sales_by_category.png
    ├── sales_by_product.png
    ├── sales_by_payment_method.png
    └── sales_by_region.png
🧠 Key Learning Outcomes
Through this project, I practised organising and exploring structured data, comparing grouped sales values, using spreadsheet calculations and filters, and presenting results visually. I also learned to recognise how software availability can affect the methods used in a project and how to document those limitations transparently.
👩‍💻 Author
Mohammad Taqi Panjwani
Computer Engineering Student
Student of Data Science & AI/ML
Red & White Skill Education-Bhavnagar
Interested in data analysis, AI, and machine learning.
<div align="center">

Thank you for visiting this project! ⭐
</div>
