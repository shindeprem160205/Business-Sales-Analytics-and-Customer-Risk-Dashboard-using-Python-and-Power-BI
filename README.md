

```markdown
# Business Sales Analytics & Customer Risk Dashboard

A business analytics project built using **Python, Pandas, Jupyter Notebook, and Microsoft Power BI** to analyze customer behavior, estimated revenue, churn risk, and fraud indicators.

## 📊 Dashboard

![Business Sales Analytics Dashboard](images/Screenshot%202026-09-23%20174841.png)

## 🎯 Project Objective

The objective of this project is to transform raw customer data into meaningful business insights through data cleaning, exploratory analysis, customer risk segmentation, and interactive Power BI visualizations.

## 🛠️ Tools & Technologies

- Python
- Pandas
- Jupyter Notebook
- Microsoft Power BI
- DAX
- Git & GitHub

## 📁 Project Structure

```text
Business-Sales-Analytics-and-Customer-Risk-Dashboard/
│
├── Dashboard/
│   └── Business_Sales_Analytics_Risk_Dashboard.pbix
│
├── data/
│   └── business_sales_cleaned.csv
│
├── images/
│   └── Dashboard Screenshot
│
└── notebook/
    └── Business_Sales_Analytics_Risk_Dashboard.ipynb
```

## 🔍 Data Preparation

The dataset was cleaned and prepared using Python and Pandas.

Key preprocessing steps included:

- Handling missing values
- Converting date columns into datetime format
- Creating customer age groups
- Creating customer risk categories
- Calculating estimated revenue
- Checking data consistency
- Preparing the cleaned dataset for Power BI

## 📈 Key Analysis

The dashboard analyzes:

- Customer acquisition trends
- Total customers
- Total orders
- Estimated revenue
- Average order value
- Revenue by country
- Revenue by age group
- Revenue by product category
- Customer risk categories
- Fraud-flag distribution

## 📊 Power BI Dashboard

The Power BI dashboard contains KPI cards and visualizations for monitoring business performance and customer risk.

### Key KPIs

- Total Customers
- Total Orders
- Estimated Revenue
- Average Order Value

### Risk Analysis

Customers are segmented into:

- **Low Risk**
- **Medium Risk**
- **High Risk**

The risk categories are based on the available churn-risk score and are used as an analytical segmentation.

### Fraud Indicators

The dataset contains a fraud indicator field. The dashboard presents these as **flagged records**, not confirmed fraudulent transactions.

## ⚠️ Important Note

`Estimated Revenue` is calculated as:

```text
Average Order Value × Total Orders
```

Therefore, it is an **estimated revenue proxy**, not actual transaction-level revenue.

The customer risk thresholds are also analytical assumptions created for segmentation and should not be interpreted as official business risk policies.

## 🚀 Project Workflow

```text
Raw Dataset
     ↓
Data Cleaning using Python & Pandas
     ↓
Feature Engineering
     ↓
Exploratory Data Analysis
     ↓
Cleaned Dataset
     ↓
Power BI
     ↓
DAX Measures
     ↓
Interactive Business Dashboard
```

## 📌 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Business Analytics
- Customer Segmentation
- Risk Analysis
- Data Visualization
- Power BI
- DAX
- Python & Pandas
- Git & GitHub
```

### Ab Git Bash mein:

```bash
git add README.md
```

```bash
git commit -m "Add project documentation"
```

```bash
git push
```

Phir GitHub refresh karo. **README automatically repository ke front page par show hoga.** 🚀
