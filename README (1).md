
# ☕ Coffee Vending Machine Sales Analysis
This project focuses on the in-depth analysis and forecasting of coffee vending machine sales data. Through this study, we aim to extract insights on customer behavior, product popularity, time-based sales patterns, and ultimately, develop forecasting models that can aid in operational and strategic decision-making for vending businesses.

📦 About the Dataset
Overview
This dataset contains transaction-level data collected from a coffee vending machine. Each record captures a sale made by the machine, detailing the product type, timestamp, and other relevant attributes. The dataset was created and shared by a contributor dedicated to open data initiatives, aiming to facilitate research and practical analysis in consumer behavior and retail analytics.

Dataset Characteristics
Although the exact fields will vary, typical attributes may include:

Timestamp of Purchase: Date and time the transaction occurred

Product Name: Type of coffee (e.g., espresso, cappuccino, latte)

Price: Cost of the product

Quantity Sold: Number of units purchased

Location Identifier (if applicable): Machine or area of installation

This data is ideal for identifying purchasing habits, peak usage hours, and seasonal consumption trends.

🎯 Project Objectives
The main goals of this project are:

To understand and visualize sales patterns over various time periods (daily, weekly, monthly)

To identify the most and least popular coffee products

To detect time-of-day preferences among consumers (e.g., morning vs. evening purchases)

To explore correlations between product categories and time-based demand

To develop forecasting models that predict future product sales

To provide actionable insights that can optimize product stock levels, pricing strategies, and machine placement

🔬 Methodology
1. Data Loading and Inspection
Read the dataset using Python's pandas library

Explore data dimensions, column types, and overall structure

2. Data Cleaning and Preprocessing
Handle missing values and inconsistent entries

Standardize date/time formats and create derived features (e.g., day of week, hour of purchase)

Aggregate data at different time intervals for analysis (e.g., daily sales totals)

3. Exploratory Data Analysis (EDA)
Use descriptive statistics to summarize overall trends

Visualize sales using time series plots, bar charts, and heatmaps

Analyze:

Product-wise sales volume

Hourly and weekly demand patterns

Price distribution and purchase frequency

4. Time Series Forecasting
Apply the SARIMAX model to account for seasonality and trends in time-dependent sales

Evaluate model performance and visualize future forecasts

5. Machine Learning Modeling
Implement Linear Regression for trend prediction and benchmarking

Compare results with statistical models to validate assumptions

6. Insight Generation
Interpret patterns observed from EDA and modeling

Derive business insights such as:

Best times for machine refill

Optimal pricing strategies

Preferred coffee products per customer segment

📈 Key Findings (Expected or Example-Based)
Morning and mid-day peaks in coffee consumption, especially on weekdays

Espresso and cappuccino identified as top-performing products

Sales may decline during holidays or weekends depending on machine location (e.g., office premises)

SARIMAX offers more accurate forecasts than basic linear regression due to its ability to model seasonality

🛠️ Tools and Technologies
Python: Programming language used for the entire workflow

pandas: Data manipulation and cleaning

matplotlib & seaborn: Visualization

statsmodels: SARIMAX time series modeling

scikit-learn: Machine learning and regression analysis

Jupyter Notebook: Interactive development and analysis environment

🔮 Future Work
Dashboard Creation: Develop an interactive dashboard using Tableau, Power BI, or Plotly Dash

Anomaly Detection: Spot unexpected drops or spikes in sales

Customer Profiling: If data permits, segment users based on frequency or product preference

Price Sensitivity Analysis: Understand how pricing affects buying decisions

Expansion to Multiple Machines: Compare performance across different locations

📌 Limitations
Dataset appears limited to one machine; results may not generalize

Lack of customer demographic data restricts personalized analysis

Seasonality effects may need longer-term data to model accurately

📃 License & Attribution
This project uses an open-source dataset provided for public use and is intended for educational, research, and non-commercial purposes. Proper attribution is given to the original dataset creator.

🙌 Acknowledgments
Special thanks to the dataset provider for contributing valuable data to the open community. This project also relies on various open-source Python libraries and the data science ecosystem that supports reproducible research and analytics.


