# Bank Loan Analysis Python Project

_This repository contains an end-to-end data analysis project on bank loan data within the finance domain. The project aims to provide valuable insights into lending activities, loan performance, and borrower behavior by using various key performance indicators (KPIs) and data visualizations._

---

## 📊 Table of Contents
- <a href="#project-overview">Project Overview</a>
- <a href="#problem-statement">Problem Statement</a>
- <a href="#domain-knowledge">Domain Knowledge</a>
- <a href="#key-performance-indicators">Key Performance Indicators</a>
- <a href="#data-visualizations">Data Visualizations</a>
- <a href="#data-terminology">Data Terminology</a>
- <a href="#tools--technologies">Tools & Technologies</a>
- <a href="#project-workflow">Project Workflow</a>
- <a href="#contact">Contact</a>

---
<h2><a class="anchor" id="project-overview"></a>📂 Project Overview</h2>

This project focuses on performing a comprehensive data analysis of bank loan data. The analysis is driven by business requirements to provide key insights into lending activities, loan performance, and borrower behavior. The findings are designed to help with crucial decision-making processes for a financial institution.

---
<h2><a class="anchor" id="problem-statement"></a>❓ Problem Statement</h2>

The main objective of this project is to analyze bank loan data to answer key business questions, such as:

- How can we evaluate the creditworthiness of borrowers and predict default probabilities?

- How can we assess the overall risk of the lending portfolio and manage it effectively?

- How can we identify and detect fraudulent loan applications and activities?

- How can we gain insights into customer behavior and tailor loan products to specific segments?

- How can we assess the profitability of the loan portfolio and optimize loan terms?

---
<h2><a class="anchor" id="domain-knowledge"></a>🧠 Domain Knowledge</h2>

Bank loans are a critical financial tool for individuals and businesses. Banks collect loan data from various sources, including loan applications, credit reports, internal records, online portals, and third-party data sources. The process of granting a loan involves multiple steps, from application and review to risk assessment, disbursement of funds, and ongoing monitoring. The analysis of this data is vital for risk assessment, decision-making, portfolio management, fraud detection, and regulatory compliance.

---
<h2><a class="anchor" id="key-performance-indicators"></a>📊 Key Performance Indicators (KPIs)</h2>

The following KPIs are essential for measuring the lending portfolio's performance:

General Loan Metrics

1. Total Loan Applications: Total and Month-to-Date (MTD) loan applications.

2. Total Funded Amount: Total and MTD funded amount.

3. Total Amount Received: Total and MTD amount received from borrowers.

4. verage Interest Rate: The average cost of the lending portfolio.

5. Average Debt-to-Income Ratio (DTI): An average to gauge borrowers' financial health.

Good Loan vs. Bad Loan Metrics
The project requires a set of KPIs to differentiate between good and bad loans.

Good Loan -- Bad Loan  

Good Loan Application Percentage -- Bad Loan Application Percentage 

Good Loan Applications -- Bad Loan Applications

Good Loan Funded Amount -- Bad Loan Funded Amount 

Good Loan Total Received Amount -- Bad Loan Total Received Amount 

---
<h2><a class="anchor" id="data-visualizations"></a>📈 Data Visualizations</h2>

The following charts provide a comprehensive visual overview of the lending portfolio, with each chart displaying 
Total Loan Applications, Total Funded Amount, and Total Amount Received.

1. Monthly Trends (Line/Area Chart): To identify seasonality and long-term trends.

2. Regional Analysis by State (Bar Chart): To identify regions with significant lending activity.

3. Loan Term Analysis (Donut Chart): To show the distribution of loans across various term lengths.

4. Employee Length Analysis (Bar Chart): To assess the impact of employment history on loan metrics.

5. Loan Purpose Breakdown (Bar Chart): To provide a visual breakdown of loan metrics based on the stated purposes of loans.

6. Home Ownership Analysis (Treemap/Heatmap): To provide a hierarchical view of how home ownership impacts loan applications and disbursements.

---
<h2><a class="anchor" id="data-terminology"></a>📖 Data Terminology</h2>
The following terms are used as data fields in this project, and their purpose and use for banks are defined:

Loan ID: A unique identifier for each loan.

Address State: Indicates the borrower's location, helping with regional risk assessment.

Employee Length: Provides insights into the borrower's employment stability.

Employee Title: Specifies the borrower's occupation or job title.

Grade: A risk classification assigned to a loan based on creditworthiness.

Sub Grade: Refines the risk assessment within a grade.

Home Ownership: Indicates the borrower's housing status, offering insights into financial stability.

Issue Date: The loan's origination date, crucial for tracking.

Last Credit Pull Date: The date the borrower's credit report was last accessed, used to monitor creditworthiness.

Last Payment Date: The most recent loan payment received, tracking payment history.

Loan Status: Indicates the current state of a loan (e.g., fully paid, current, default).

Next Payment Date: Estimates the date of the next loan payment, assisting in cash flow forecasting.

Purpose: Specifies the reason for the loan (e.g., debt consolidation, education).

Term: Defines the duration of the loan in months.

Verification Status: Indicates if the borrower's financial information has been verified.

Annual Income: Reflects the borrower's total yearly earnings, assessing repayment capacity.

DTI (Debt-to-Income Ratio): Measures the borrower's debt burden relative to income. 

Instalment: The fixed monthly payment amount for loan repayment.

Interest Rate: Represents the annual cost of borrowing.

Loan Amount: The total borrowed sum.
---
<h2><a class="anchor" id="tools--technologies"></a>🛠️ Tools & Technologies</h2>

- Jupyter Notebook: The primary environment for the analysis, as indicated by the Bank Loan Project.ipynb file.

- Python Libraries: This project heavily utilizes Python libraries like Pandas, Numpy, and Matplotlib for data manipulation and visualization.

- Version Control: The project uses Git and is hosted on GitHub for project management and collaboration.

---
<h2><a class="anchor" id="project-workflow"></a>⚙️ Project Workflow</h2>

Data Loading: The financial_loan.xlsx dataset was loaded into the project.

Data Cleaning & Transformation: Initial data cleaning and preparation steps were performed.

KPI Calculation: Python code was used to calculate all required KPIs, including total amounts, averages, and good vs. bad loan metrics.

Data Visualization: Interactive charts were created to visualize key trends and insights.

Documentation: This README file and a problem statement document were created to provide a detailed overview of the project's objectives, requirements, and findings.

---
<h2><a class="anchor" id="contact"></a>📞 Contact</h2>

**Harshad Mourya**<br>
Data Analyst<br>
📧 Email: mouryaharshad@gmail.com<br>
🔗 [LinkedIn](https://www.linkedin.com/in/harshad-mourya/)