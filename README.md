# Customer-Shopping-Behavior-Analysis
End-to-end analysis of customer shopping behavior using Python, SQL Server, and Power BI to uncover spending patterns, top categories, and subscription trends.

Customer Shopping Behavior AnalysisOverviewEnd-to-end analytics project analyzing customer purchase data to uncover spending patterns, product preferences, segments, and subscription behavior.Pipeline: Python (cleaning & EDA) → SQL Server (T-SQL analysis) → Power BI (dashboard) → Report & presentationDatasetSource: Transactional purchase data (CSV)  
Columns: 18 original → 19 after feature engineering  
Missing values: None

Key fields: Customer demographics, purchase details (amount, category, season), discounts, shipping, ratings, subscription statusStepsPython — Load data, clean, EDA, engineer purchase_frequency_days  
SQL Server — Load cleaned data and run business queries  
Power BI — Build interactive dashboard with filters  
Reporting — Project report and presentation

Key ResultsMetric
Finding
Avg. review rating
3.75
Avg. purchase amount
$59.54
Subscription split
~60% non-subscribed / ~40% subscribed
Top category
Clothing (highest revenue & volume)
Seasonality
Even across seasons; Spring & Winter slightly higher

ToolsPython (Pandas) · SQL Server (T-SQL) · Power BI · SQLAlchemy / pyodbcHow to RunInstall dependencies: pip install pandas sqlalchemy pyodbc  
Run the Python notebook for cleaning and EDA  
Load data into SQL Server and execute queries  
Open the Power BI file and refresh visuals

ConclusionComplete analytics pipeline from raw data to dashboard and report. Clothing drives the most revenue; the ~40% subscription rate highlights a clear growth opportunity.

