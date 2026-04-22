# Marketing-Insights-For-E-Commerce-Company
📁 Project Overview

This project provides end-to-end marketing analytics for an e-commerce company using transactional, customer, marketing, and tax data. The goal is to extract insights, build predictive models, perform customer segmentation, and create dashboards for monitoring KPIs.

# E-Commerce Customer Analytics Case Study

## Project Overview

This project focuses on performing end-to-end analytics for an e-commerce company using transactional customer data. The objective is to generate business insights, build predictive models, and support strategic decision-making through data analysis.

The project covers:

* Revenue & invoice calculations
* Exploratory Data Analysis (EDA)
* Customer segmentation
* Customer Lifetime Value prediction
* Cross-selling / Market Basket Analysis
* Next Purchase Day prediction
* Cohort Analysis

---

## Dataset Columns

Main fields used in the project:

* customerid
* gender
* location
* tenure_months
* transaction_id
* transaction_date
* product_sku
* product_description
* product_category
* quantity
* avg_price
* delivery_charges
* coupon_status
* discount_pct
* gst
* offline_spend
* online_spend
* total_spend

---

## Business Metrics Used

### Invoice Value

Invoice\ Value=((Quantity \times Avg_price)\times(1-Discount_pct)\times(1+GST))+Delivery_Charges

### Average Order Value

AOV = \frac{Revenue}{Transactions\ per\ Customer}

### Purchase Frequency

Purchase\ Frequency = \frac{Total\ Transactions}{Total\ Customers}

### Repeat Rate

Repeat\ Rate = \frac{Repeat\ Customers}{Total\ Customers}\times100

### Churn Rate

Churn\ Rate = \frac{Lost\ Customers}{Total\ Customers}\times100

---

## Project Objectives

## 1. Revenue / Invoice Calculation

Calculated item-level and transaction-level revenue using pricing, discount, tax, and delivery charges.

---

## 2. Exploratory Data Analysis

Performed detailed analysis on:

* Monthly customer acquisition
* Customer retention month-over-month
* Revenue from new vs existing customers
* Impact of discounts on revenue
* Revenue trends by category, month, week, weekday
* Orders by day/week/month
* Marketing spend vs revenue
* Product demand analysis
* Seasonal trends by category/location

---

## 3. Customer Segmentation

### Heuristic Segmentation

Used:

* RFM Analysis
* Revenue-based grouping

Segments:

* Premium
* Gold
* Silver
* Standard

### Scientific Segmentation

Used:

* K-Means Clustering

Identified behavioral customer groups and profile patterns.

---

## 4. Customer Lifetime Value Prediction

Created target labels:

* Low Value
* Medium Value
* High Value

Built machine learning classification model to predict future customer value.

**Model Accuracy:** ~80%

---

## 5. Cross-Selling Analysis

Used:

* Product pair analysis
* Market Basket Analysis

Identified products frequently purchased together for bundling opportunities.

---

## 6. Next Purchase Day Prediction

Predicted how soon customers may return:

* 0–30 Days
* 30–60 Days
* 60–90 Days
* 90+ Days

Used repeat customer purchase gaps and classification modeling.

---

## 7. Cohort Analysis

Created monthly cohorts based on first purchase month.

Analyzed:

* Customer retention trends
* Repeat behavior by acquisition month

**Highest Month-2 Retention Cohort:** June 2019 (14.6%)

---

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* MLxtend
* Jupyter Notebook

---

## Key Insights

* Existing customers contributed significantly to revenue growth.
* Discounts improved conversions but impacted margins.
* Some cohorts showed stronger retention than others.
* High-value customers can be targeted for loyalty campaigns.
* Product bundles can improve cart value.

---

## Business Recommendations

* Launch retention campaigns for low-performing cohorts
* Upsell premium customers
* Use bundles for cross-selling
* Optimize discounts by category
* Re-engage churn-risk customers early

---

## Repository Structure

```text
├── data/
├── notebooks/
├── images/
├── README.md
└── requirements.txt
```

---

## Author

**Vivek Kumar**
Data Scientist | Data Analyst | SQL | Excel | Power BI | Python

---

