# Telecom Customer Churn Analysis

## Overview

Telecom Customer Churn Analysis is an end-to-end Data Analytics project focused on identifying customer churn patterns and understanding the key factors that influence customer retention in the telecommunications industry. The project follows a complete analytics workflow, including data preprocessing, exploratory data analysis, business-focused analysis, and interactive dashboard development using Power BI.

The primary objective of this project is to transform raw customer data into meaningful business insights that help telecom companies reduce customer attrition, improve retention strategies, and minimize revenue loss.

---

## Dataset

The dataset contains customer demographic, service, and subscription-related information, including:

* Customer ID
* Gender
* Senior Citizen Status
* Partner Status
* Dependents
* Tenure
* Phone Service
* Multiple Lines
* Internet Service
* Online Security
* Online Backup
* Device Protection
* Tech Support
* Streaming TV
* Streaming Movies
* Contract Type
* Paperless Billing
* Payment Method
* Monthly Charges
* Total Charges
* Churn Status

The dataset consists of approximately 7,000 customer records and was analyzed to identify customer retention trends and churn behavior.

---

## Tools & Technologies

### Data Analysis

* Power Query
* DAX (Data Analysis Expressions)

### Visualization

* Power BI Desktop

### Development Environment

* Power BI Desktop
* Microsoft Excel

---

## Project Workflow

### 1. Data Collection

* Imported telecom customer dataset.
* Examined dataset structure and attributes.
* Verified data quality and consistency.

### 2. Data Cleaning & Transformation

* Removed unnecessary columns.
* Handled missing and null values.
* Standardized data formats.
* Created calculated columns and measures.
* Prepared data model for dashboard development.

### 3. Data Analysis

Performed customer churn analysis based on:

* Contract Type
* Internet Service
* Payment Method
* Customer Tenure
* Monthly Charges
* Senior Citizen Status
* Gender Distribution

### 4. DAX Measures

Created business-focused KPIs including:

* Total Customers
* Churn Rate
* Revenue At Risk
* Average Tenure
* Churned Customers
* Customer Retention Metrics

### 5. Power BI Dashboard Development

Designed an interactive dashboard to visualize:

* Overall Customer Churn
* Contract-wise Churn Analysis
* Internet Service Impact on Churn
* Revenue At Risk
* Customer Tenure Analysis
* Charge Group Analysis
* Customer Segmentation

---

## Dashboard Features

* Interactive Slicers and Filters
* Dynamic KPI Cards
* Churn Distribution Analysis
* Contract-wise Churn Comparison
* Internet Service Performance Analysis
* Revenue Risk Monitoring
* Customer Segmentation Insights
* Charge Group Trend Analysis

---

## Dashboard KPIs

### Total Customers

Displays the total number of customers in the dataset.

### Churn Rate

Shows the percentage of customers who discontinued telecom services.

### Revenue At Risk

Measures potential revenue loss caused by churned customers.

### Average Tenure

Represents the average customer relationship duration.

---

## Key Insights

* The overall churn rate is approximately 26.54%.
* Customers with month-to-month contracts exhibit the highest churn rate.
* Fiber optic service users are more likely to churn compared to DSL users.
* Customers with higher monthly charges show increased churn tendencies.
* Long-term contracts significantly improve customer retention.
* Revenue at risk can be reduced through targeted retention strategies.

---

## Business Recommendations

* Encourage customers to adopt annual or multi-year contracts.
* Improve service quality for high-risk customer segments.
* Offer personalized retention programs for customers with high monthly charges.
* Strengthen customer support for fiber optic subscribers.
* Implement loyalty programs to increase customer tenure.
* Monitor churn-prone customer groups proactively.

---

## Project Structure

```text
Telecom-Customer-Churn-Analysis/
│
├── Dataset/
│   └── telecom_customer_churn.csv
│
├── PowerBI/
│   └── Telecom_Customer_Churn_Dashboard.pbix
│
├── Images/
│   └── dashboard_screenshot.png
│
├── Documentation/
│   └── Project_Report.pdf
│
└── README.md
```

---

## Dashboard Preview

The dashboard provides a modern and interactive interface that enables stakeholders to analyze customer churn patterns through dynamic filters, KPI cards, and visual insights.

Key Visualizations:

* Total Customers by Churn
* Contract Type vs Churn
* Internet Service vs Churn
* Churned Customers by Charge Group
* Revenue At Risk Analysis
* Customer Retention Metrics

---

## How to Run

### Clone the Repository

```bash
git clone https://github.com/yourusername/Telecom-Customer-Churn-Analysis.git
```

### Open Power BI Dashboard

1. Download the repository.
2. Open the `.pbix` file using Power BI Desktop.
3. Refresh the dataset if required.
4. Explore dashboard insights using interactive filters and slicers.

---

## Results

This project demonstrates the application of Business Intelligence and Data Analytics techniques to solve real-world customer retention challenges. Through data modeling, DAX calculations, and interactive visualizations, the dashboard provides actionable insights that support strategic decision-making and customer retention initiatives.

---

## Future Enhancements

* Churn Prediction using Machine Learning
* Customer Lifetime Value (CLV) Analysis
* Predictive Retention Modeling
* Real-Time Dashboard Integration
* Customer Segmentation using Clustering Techniques

---

## Author

**Usman Ali**

MCA Student | Data Analyst | Power BI Developer

GitHub: https://github.com/usmanali35549
