# PhonePe Digital Payments Analytics | Python & Power BI

**An End-to-End Data Analytics Project | Exploratory Data Analysis | Statistical Analysis | Business Intelligence**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat-square)

---

## 1. Project Overview

Digital payments have transformed India's financial ecosystem, creating an increasing need to understand transaction behaviour, customer adoption, regional performance, and user engagement.

This project focuses on analyzing **PhonePe's digital payment ecosystem across Indian states and districts** to uncover meaningful patterns in transaction activity, user adoption, device preferences, and demographic characteristics.

Using Python for data cleaning, exploratory data analysis, statistical analysis, and data visualization, followed by Microsoft Power BI for interactive business intelligence, the project transforms multiple raw datasets into actionable insights.

The analysis covers quarterly data from **Q1 2018 to Q2 2021**, providing a historical perspective on the evolution of digital payment activity across India.

Rather than limiting the analysis to transaction counts, the project investigates the relationships between transaction volume, transaction value, registered users, app engagement, device usage, and regional demographics.

**The primary objective is to demonstrate how data analytics can support business understanding, identify regional growth opportunities, and facilitate data-driven decision-making.**

## 2. Business Problem

A digital payment platform operates across diverse geographical markets, each with different population characteristics, customer adoption levels, device preferences, and transaction behaviours.

Understanding these differences is essential for identifying growth opportunities and improving platform engagement.

This project addresses the following business questions:

- How has digital payment activity evolved over time?
- Which states and districts contribute the most to transaction volume and transaction value?
- Which transaction categories dominate payment activity?
- How does registered-user adoption vary across geographical regions?
- Which mobile device brands account for the largest share of registered users?
- Is population density associated with digital transaction activity?
- How does app engagement relate to transaction performance?
- Which geographical markets offer opportunities for further user adoption?
- Are state-level transaction figures consistent with aggregated district-level figures?

The analysis aims to answer these questions through structured data exploration, statistical techniques, and interactive visualizations.

## 3. Project Objectives

- Perform data cleaning, preprocessing, and quality validation across multiple datasets.
- Conduct exploratory data analysis to identify transaction patterns and trends.
- Analyze state-wise and district-wise transaction performance.
- Evaluate transaction categories and average transaction values.
- Examine registered-user growth and device-brand distribution.
- Investigate demographic relationships with transaction activity.
- Perform correlation analysis to understand relationships between key variables.
- Develop an interactive Power BI dashboard for business performance monitoring.
- Translate analytical findings into actionable business recommendations.

## 4. Technology Stack

| Technology | Application |
|---|---|
| Python | Data analysis and preprocessing |
| Pandas | Data manipulation, aggregation, and merging |
| NumPy | Numerical computations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Jupyter Notebook | Interactive analysis |
| Microsoft Excel | Dataset storage and inspection |
| Power BI Desktop | Interactive dashboards and business intelligence |

## 5. Dataset Description

The project uses a multi-sheet Excel workbook containing transaction, user, device, and demographic information.

**Source file:** `PHONE PAY DATA.xlsx`

| Dataset | Records | Description |
|---|---:|---|
| State_Txn and Users | 504 | State-level transactions, transaction value, registered users, and app opens |
| State_TxnSplit | 2,514 | Transaction categories and their respective transaction metrics |
| State_DeviceData | 5,544 | Registered users distributed across device brands |
| District_Txn and Users | 10,248 | District-level transaction and user metrics |
| District Demographics | 742 | District population, area, density, and geographical information |
| Admin | 42 | Administrative information |

**Underlying transactional data coverage:** Q1 2018 – Q2 2021.

### Key Analytical Variables

- **Transactions:** Total number of transactions.
- **Amount (INR):** Total transaction value in Indian Rupees.
- **ATV (INR):** Average transaction value.
- **Registered Users:** Number of registered users.
- **App Opens:** Number of application opens.
- **Population:** Population of the respective geographical region.
- **Density:** Population per square kilometre.
- **Brand:** Mobile device brand associated with registered users.

## 6. Analytical Approach and Methodology

The project follows a structured analytical workflow.

### Phase 1: Data Loading and Exploration

- Imported multiple Excel sheets using Pandas.
- Examined dataset dimensions, structures, and column information.
- Reviewed numerical distributions using descriptive statistics.
- Identified missing values and calculated missing-value percentages.
- Examined unique states, districts, and other categorical variables.

### Phase 2: Data Cleaning and Quality Validation

Performed data quality checks to improve the reliability of the analysis.

Key activities included:

- Missing-value identification and investigation.
- Data type validation.
- Standardization of categorical and text columns.
- Duplicate record investigation.
- Validation of numerical fields.
- Investigation of missing transaction amounts and ATV values.
- District name and district code mapping.
- Comparison of state-level and district-level aggregated metrics.

Particular attention was given to discrepancies between state-level and district-level transaction figures.

### Phase 3: Exploratory Data Analysis (EDA)

Conducted detailed analysis across three major dimensions.

**A. Transaction Analysis**

- State-wise transaction volume and transaction value.
- Top and bottom performing states.
- Most frequent transaction categories by state and quarter.
- Average transaction value across states.
- Transaction volume versus transaction value.
- Quarterly transaction growth patterns.

**B. User and Device Analysis**

- Registered-user growth over time.
- App opens across states and quarters.
- Device-brand distribution.
- Most popular device brands across geographical regions.
- State-wise user adoption patterns.

**C. Demographic Analysis**

- District-wise population comparisons.
- Most populated districts in each state.
- Registered users relative to population.
- Population density versus transaction volume.
- Geographical distribution of transaction activity.

### Phase 4: Data Integration and Advanced Analysis

Combined relevant datasets to investigate relationships across transaction, user, device, and demographic dimensions.

| Analysis | Purpose |
|---|---|
| User-to-Population Ratio | Examine registered-user penetration relative to population |
| Population Density Correlation | Investigate the relationship between population density and transaction volume |
| Average Transaction Amount per User | Compare transaction value against registered-user counts |
| Device Brand Usage Ratio | Evaluate device-brand distribution relative to registered users |
| State-District Reconciliation | Validate consistency between geographical aggregation levels |

### Phase 5: Statistical Analysis

Used correlation analysis to explore relationships between demographic and transactional variables.

Variables examined included:

- Transactions
- Transaction Amount
- Registered Users
- App Opens
- Population
- Population Density

Pearson correlation was used to identify the direction and strength of linear relationships.

Correlation results were interpreted as statistical associations rather than evidence of causation.

### Phase 6: Business Intelligence and Dashboard Development

Translated analytical results into a multi-page Power BI dashboard featuring:

- KPI cards.
- Quarterly trend analysis.
- Growth-rate comparisons.
- Cumulative performance metrics.
- State and district rankings.
- Device-brand distribution.
- Geographical visualizations.
- Interactive filters.
- Business insights and recommendations.

---

## 7. Power BI Dashboard

The Power BI report consists of five analytical pages and a dedicated business insights page.

### Page 1: Overview

Provides a consolidated snapshot of digital payment performance.

**Key Performance Indicators:**

| Metric | Dashboard Value |
|---|---:|
| Total Transactions | 20.53 Billion |
| Total Transaction Value | ₹35.63 Trillion |
| Average Transaction Value | ₹1,735 |
| Registered Users | 305.26 Million |

**Visualizations:**
- Transaction volume trend.
- Transaction value trend.
- Top 10 states by transactions.
- Transaction type distribution.
- State-wise transaction map.

![PhonePe Overview](./Phone%20Pe%20-Digital-Payments-Analytics/images/1_overview.png)

### Page 2: Transaction Trends

Examines quarterly transaction performance and growth patterns.

**Analysis includes:**
- Quarterly transaction volume and value.
- Transaction growth rate.
- Transaction value growth rate.
- Cumulative transactions.
- Cumulative transaction value.

This page helps understand the pace of digital payment adoption and identify changes in transaction activity over time.

![Transaction Trends](./Phone%20Pe%20-Digital-Payments-Analytics/images/2_transaction-trends.png)

### Page 3: User and Device Analysis

Examines registered-user adoption and mobile device preferences.

**Analysis includes:**
- Registered-user growth.
- App opens over time.
- Device-brand distribution.
- Top device brands.
- Top states by registered users.

This analysis provides insights into the geographical distribution of the user base and the device brands contributing to platform adoption.

![User and Device Analysis](./Phone%20Pe%20-Digital-Payments-Analytics/images/3_user-device-analysis.png)

### Page 4: State and District Performance

Provides a geographical comparison of transaction performance.

**Analysis includes:**
- Top states by transaction value.
- Top districts by transaction value.
- Top states by transaction volume.
- Top districts by transaction volume.
- Detailed state and district performance table.

This page helps identify leading geographical markets and compare transaction activity at different administrative levels.

![State and District Performance](./Phone%20Pe%20-Digital-Payments-Analytics/images/4_state-district-performance.png)

### Page 5: User and Device Insights

Investigates regional differences in transaction contribution and user engagement.

**Analysis includes:**
- State contribution to total transactions.
- Transaction volume versus transaction value.
- Transactions per app open by state.
- Comparative geographical performance.

This page helps distinguish between markets with high transaction volumes and markets showing relatively stronger transaction activity per app open.

![User and Device Insights](./Phone%20Pe%20-Digital-Payments-Analytics/images/5_user-device-insights.png)

### Page 6: Business Insights and Recommendations

Summarizes the analytical findings and translates them into business-oriented recommendations.

Eight major insight areas are presented:

1. High Transaction Volume States.
2. Transaction Value Leaders.
3. Volume versus Value Gap.
4. Transactions per App Open.
5. State Contribution to Total Transactions.
6. Device Brand Insights.
7. Lower Share States.
8. Emerging Opportunities.

![Business Insights](./Phone%20Pe%20-Digital-Payments-Analytics/images/6_business-insights.png)

---

## 8. Key Findings and Business Insights

The following findings are derived from the Python analysis and Power BI dashboard.

### 1. Growth in Digital Payment Activity

- Transaction volume and transaction value increased substantially between 2018 and 2021.
- A temporary decline was observed in Q2 2020.
- Transaction activity recovered in subsequent quarters.
- Q2 2021 recorded the highest quarterly transaction activity within the analyzed period.

**Business Interpretation:** The historical trend demonstrates substantial growth in digital payment activity, highlighting the importance of maintaining reliable payment infrastructure and improving customer engagement.

### 2. Geographical Concentration of Transactions

Karnataka, Maharashtra, and Telangana emerged as leading states in transaction volume.

| State | Approx. Transaction Volume |
|---|---:|
| Karnataka | 2.98 Billion |
| Maharashtra | 2.83 Billion |
| Telangana | 2.35 Billion |

Telangana, Karnataka, and Maharashtra also lead the transaction-value comparison.

**Business Interpretation:** High-performing states can serve as benchmarks for understanding successful adoption patterns and regional transaction behaviour.

### 3. Transaction Category Preferences

Peer-to-peer payments represent a major component of the transaction-value distribution in the dashboard.

Recharge and bill payments, merchant payments, and other categories provide additional dimensions for understanding payment preferences.

**Business Interpretation:** Understanding category-level preferences can help identify opportunities to strengthen merchant payments and expand the adoption of different payment services.

### 4. Device Brand Distribution

The device analysis identified Xiaomi, Samsung, and Vivo as prominent brands in the registered-user metrics.

The dashboard reports approximately:
- Xiaomi: 616 Million
- Samsung: 481 Million
- Vivo: 411 Million

**Business Interpretation:** Device distribution can help prioritize application compatibility, performance optimization, and user experience improvements across commonly used devices.

### 5. Population Density and Transaction Volume

The Python correlation analysis produced a coefficient of approximately **0.19** between population density and transaction volume.

This indicates a **weak positive linear relationship.**

**Business Interpretation:** Population density alone is insufficient to explain transaction demand. Other factors, such as registered-user adoption, merchant availability, and economic activity, should also be investigated.

### 6. Relationship Between User Engagement and Transactions

The correlation analysis produced the following results:

| Variables | Correlation |
|---|---:|
| Transactions vs Transaction Amount | 0.98 |
| Transactions vs App Opens | 0.84 |
| Transaction Amount vs App Opens | 0.84 |
| Transactions vs Registered Users | 0.80 |
| App Opens vs Registered Users | 0.86 |
| Population vs Registered Users | 0.66 |
| Population vs Transactions | 0.36 |
| Population vs Transaction Amount | 0.35 |

**Business Interpretation:** Transaction activity shows stronger positive associations with registered users and app engagement than with population alone.
These relationships are exploratory and should not be interpreted as causal effects.

### 7. Regional Growth Opportunities

The dashboard identifies states and union territories with relatively smaller contributions to overall transaction activity.
The analysis identifies opportunities to investigate regional adoption barriers and understand why certain markets have lower transaction activity.

**Business Interpretation:** Expansion strategies should consider population, registered-user penetration, merchant availability, and transaction activity together.


## 9. Business Recommendations

Based on the findings, the following recommendations can be considered:

| Area | Recommendation |
|---|---|
| Market Expansion | Investigate regions with large populations and relatively low registered-user penetration. |
| Customer Engagement | Develop strategies to encourage repeat transactions and improve app engagement. |
| Merchant Adoption | Investigate geographical markets with opportunities for greater merchant payment adoption. |
| Device Optimization | Prioritize compatibility and performance across widely used device brands. |
| Regional Strategy | Study high-performing states to identify adoption patterns that could be replicated elsewhere. |
| Performance Monitoring | Track transaction growth, registered users, app opens, and transaction-category distribution. |
| Data Quality | Strengthen reconciliation between state-level and district-level reporting. |

---


## 10. Repository Structure

```text
PhonePe-Digital-Payments-Analytics/
│
├── README.md
│
├── data/
│   └── PHONE PAY DATA.xlsx
│
├── notebooks/
│   └── Phone pay data analysis.ipynb
│
├── powerbi/
│   ├── phonpe 2 dashboard.pbix
│   └── phonpe 2 dashboard.pdf
│
├── images/
│   ├── 1_overview.png
│   ├── 2_transaction-trends.png
│   ├── 3_user-device-analysis.png
│   ├── 4_state-district-performance.png
│   ├── 5_user-device-insights.png
│   └── 6_business-insights.png
│
└── requirements.txt
```

---

## 11. Key Skills Demonstrated

**Technical Skills**

- Python
- Pandas and NumPy
- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Statistical and Correlation Analysis
- Data Visualization
- Power BI and DAX
- KPI Development and Dashboard Design
- Microsoft Excel

**Analytical and Business Skills**

- Business Problem Understanding
- Data Quality Validation
- Data Integration and Transformation
- Trend and Performance Analysis
- Geographical and Demographic Analysis
- Data Storytelling
- Business Insights and Recommendations
- Data-Driven Decision Making

---

## 12. Author

**Vedant Arora**

B.Tech Student | Aspiring Data Analyst

Technical Interests: Python, SQL, Power BI, Data Analytics and Business Intelligence.

- GitHub: [Vedant-Ar](https://github.com/Vedant-Ar)

---

## 13. Acknowledgement

This project uses PhonePe Pulse data for educational and analytical purposes.

The analysis demonstrates the practical application of Python and Power BI in transforming raw digital payment data into meaningful insights, interactive visualizations, and business-oriented recommendations.

If you find this project useful, feel free to ⭐ the repository!
