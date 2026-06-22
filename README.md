Retail Sales Intelligence & Predictive Forecasting
Project Overview
This project provides an end-to-end data analytics solution designed to transform raw retail sales data into actionable business intelligence. The project moves beyond descriptive reporting by integrating time-series forecasting, allowing stakeholders to visualize both historical performance and future revenue projections.

Key Features
Data Auditing & Cleaning: Automated pipeline to handle missing values, formatting, and data inconsistencies in large-scale retail datasets.

Exploratory Data Analysis (EDA): In-depth investigation into profit bottlenecks, regional performance, and customer segment behavior.

Time-Series Forecasting: Implemented a Prophet-based machine learning model to predict sales trends for the next 6 months with integrated confidence intervals.

Interactive BI Dashboard: A professional Power BI dashboard featuring dynamic slicers, trend analysis, and predictive overlays.

Tech Stack
Language: Python 3.x

Data Analysis: Pandas, NumPy

Forecasting: Prophet (by Meta)

Visualization: Power BI Desktop

Environment: Jupyter Notebooks

Project Structure
Plaintext
├── data/               # Raw and processed datasets
├── notebooks/          # Modularized analysis & modeling
│   ├── 01_data_audit.ipynb
│   ├── 02_exploratory_analysis.ipynb
│   └── 04_predictive_modeling.ipynb
├── dashboard.pbix      # Power BI implementation
└── reports/            # Executive summaries and findings
Visualizing Results
The dashboard provides a 360-degree view of retail health:

Executive Overview: KPI cards and regional profit distribution.

Performance Trends: Actual sales performance vs. model-predicted outcomes.

Predictive Modeling: Future revenue trends with a 95% confidence interval shaded area.

Business Insights
Furniture Bottleneck: Identified as a high-cost, low-profit category requiring shipping optimization.

Regional Variance: Central region performance highlighted as a key area for strategic adjustment.

Forecast Outlook: Provides data-driven projections to assist in inventory planning for the upcoming 6-month cycle.

How to use this repository
Clone the repo: git clone https://github.com/ayesha-tariq05/retail-sales-intelligence

Environment: Ensure you have the necessary libraries installed: pip install pandas prophet

Explore: Run the notebooks in sequential order (01 -> 02 -> 03 -> 04).