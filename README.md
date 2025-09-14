# Bank Loan Report: Comprehensive Analysis using SQL, Python and PowerBI

## Project Overview 📊

The Bank Loan Report is a comprehensive business intelligence solution designed to provide in-depth insights into a bank's lending activities and performance
This project addresses the need for a data-driven approach to monitor the health of the bank's loan portfolio, identify key trends, and inform strategic decisions. 
By leveraging SQL, Python, and Power BI, this solution delivers a dynamic and interactive reporting system that offers a holistic view of the lending landscape.

The report is structured around three key dashboards: a **Summary Dashboard** for high-level KPIs, an **Overview Dashboard** for visual trend analysis, and a **Details Dashboard** for granular data exploration.

## Key Features & KPIs 📈

The report provides a detailed analysis of the loan portfolio through a series of key performance indicators (KPIs) and visualizations.

### 1. Summary Dashboard KPIs

* **Total Loan Applications**: The total number of loan applications received. This includes Month-to-Date (MTD) and Month-over-Month (MoM) changes.
* **Total Funded Amount**: The total amount of funds disbursed as loans. This includes MTD and MoM changes.
* **Total Amount Received**: The total amount received from borrowers, essential for assessing cash flow and loan repayment. This also tracks MTD and MoM changes.
* **Average Interest Rate**: The average interest rate across all loans, with MTD and MoM variations.
* **Average Debt-to-Income (DTI)**: The average DTI for borrowers, which helps gauge their financial health. The report computes the average for all loans and tracks MTD and MoM fluctuations.

<br>

---

### 2. Good Loan vs. Bad Loan Analysis 🏦

To evaluate the quality of the loan portfolio, the report distinguishes between 'Good Loans' and 'Bad Loans' based on specific loan status criteria.

* **Good Loans**: Loans with a status of 'Fully Paid' and 'Current'.
    * **Good Loan Application Percentage**: The percentage of applications classified as 'Good Loans'.
    * **Good Loan Applications**: The total number of loan applications falling under this category.
    * **Good Loan Funded Amount**: The total amount of funds disbursed for these loans.
    * **Good Loan Total Received Amount**: The total amount received from borrowers for 'Good Loans'.

* **Bad Loans**: Loans with a status of 'Charged Off'.
    * **Bad Loan Application Percentage**: The percentage of applications categorized as 'Bad Loans'.
    * **Bad Loan Applications**: The total number of applications in this category.
    * **Bad Loan Funded Amount**: The total amount of funds disbursed for these loans.
    * **Bad Loan Total Received Amount**: The total amount received from borrowers for 'Bad Loans'.

<br>

---

## Dashboard Visualizations & Reports 📊

The project's visualizations are designed to provide clear, actionable insights through various chart types.

* **Monthly Trends by Issue Date (Line Chart)**: This chart shows how 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received' vary over time, helping to identify seasonality and trends.
* **Regional Analysis by State (Filled Map)**: This map visually represents lending metrics categorized by state, enabling the identification of regions with significant lending activity.
* **Loan Term Analysis (Donut Chart)**: This chart depicts loan statistics based on different loan terms (e.g., 36 months, 60 months).
* **Employee Length Analysis (Bar Chart)**: This chart illustrates how lending metrics are distributed among borrowers with different employment lengths.
* **Loan Purpose Breakdown (Bar Chart)**: This chart provides a visual breakdown of loan metrics based on the stated purposes of loans.
* **Home Ownership Analysis (Tree Map)**: This chart displays loan metrics categorized by different home ownership statuses (e.g., own, rent, mortgage), providing a hierarchical view.

**Loan Status Grid View** also provides a comprehensive overview of key indicators for each loan status.

<br>

---

## Technical Stack 💻

* **Data Source**: SQL Database, SQL Server Management Studio
* **ETL & Analysis**: Python (Pandas for data manipulation, Matplotlib/Plotly for visualizations)
* **Business Intelligence**: Power BI (for interactive dashboards and reports)

This project showcases a complete data analysis pipeline, from raw data to a professional, interactive business report.
