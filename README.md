# Adorna ERP Revenue & Analytics System

## Overview

This project demonstrates a hybrid **ERP financial reporting and data science forecasting system** modeled on real wedding venue business operations. The solution simulates core ERP modules (GL, AR, AP, Billing) while applying machine learning to forecast revenue and support business decision-making.

The dataset is simulated for confidentiality while preserving real-world business logic.

---

## Business Context

A large convention center hosts 60–100 events per year including weddings, receptions, and corporate events. Revenue is driven by:

* Venue rental
* Catering services
* Decoration services

Management requires:

* ERP-style financial reporting
* Budget vs actual analysis
* AR aging and revenue recognition
* Revenue forecasting and demand planning

This project solves those needs.

---

## ERP / MIS Components

### ERP Modules Simulated

| ERP Module          | Implementation                          |
| ------------------- | --------------------------------------- |
| Billing             | Event revenue modeling                  |
| Accounts Receivable | Payment delay & AR aging                |
| General Ledger      | GL posting logic with chart of accounts |
| Accounts Payable    | Vendor expense simulation               |
| Financial Reporting | P&L, revenue, variance reports          |
| Budgeting           | Budget vs actual variance               |
| Cost Center         | Event-type based reporting              |
| Revenue Recognition | Recognized vs deferred revenue          |

### ERP Features Implemented

* Chart of Accounts design
* GL posting logic for each business event
* Monthly P&L reporting
* Revenue by account analysis
* Budget vs actual variance reporting
* AR aging analysis
* Revenue recognition simulation
* Cost center reporting

These processes follow standard PeopleSoft, SAP, Oracle, and Workday financial flows.

---

## Data Science & Analytics Components

### Analytics Performed

* Data cleaning and feature engineering
* Exploratory data analysis
* Correlation analysis
* Revenue trend analysis

### Machine Learning

* Random Forest regression model
* Revenue forecasting
* Feature importance analysis
* Actual vs predicted comparison
* Forecast trend visualization

### Key Insights

* Food plate pricing is the strongest revenue driver
* Guest count is the second highest driver
* Decor billing significantly increases profitability
* Venue rent alone has limited impact
* Seasonality has lower impact than pricing and guest volume

---

## Tech Stack

* Python
* Pandas
* Scikit-learn
* Matplotlib
* Google Colab
* Jupyter Notebook

---

## Files in Repository

| File                               | Description                |
| ---------------------------------- | -------------------------- |
| adorna_erp_revenue_analytics.ipynb | Full project notebook      |
| adorna_events_cleaned.csv          | Simulated business dataset |
| README.md                          | Project documentation      |

---

## Project Workflow

1. Dataset generation and cleaning
2. ERP posting and reporting
3. Financial analytics and variance reporting
4. AR aging and revenue recognition
5. Cost center analysis
6. Machine learning forecasting
7. Business insight generation

---

## Business Value

This system enables:

* Better revenue planning
* Improved pricing strategy
* Financial transparency
* Budget control
* Demand forecasting
* ERP reporting automation

---

## Disclaimer

All data used in this project is simulated for confidentiality while preserving real-world business structure and logic.

---

## Author

Eshan Hiriyur
Computer Science | ERP Analytics | Data Science | Data Analytics
