Customer Shopping Behavior AnalysisThis project looks at customer shopping data to understand how people spend, what they buy, and how subscriptions play a role.I used Python for cleaning and analysis, SQL Server for queries, and Power BI for the dashboard.DatasetTransactional purchase data (CSV)
18 columns originally, 19 after adding purchase_frequency_days
No missing values

Includes customer details, purchase amount, category, season, discounts, shipping type, ratings, and subscription status.What I DidLoaded and cleaned the data in Python, then created a new frequency column
Moved the cleaned data into SQL Server and wrote queries for revenue, products, segments, and subscriptions
Built a Power BI dashboard with filters for gender, category, shipping, and subscription status
Put the findings into a report and presentation

Key FindingsAverage review rating: 3.75
Average purchase amount: $59.54
About 60% of customers are not subscribed, 40% are
Clothing is the top category by both revenue and number of purchases
Sales are fairly steady across seasons, with Spring and Winter a bit higher

ToolsPython (Pandas), SQL Server, Power BI, SQLAlchemy, pyodbcHow to RunInstall packages: pip install pandas sqlalchemy pyodbc
Run the notebook to clean the data
Load the data into SQL Server and run the queries
Open the Power BI file to view the dashboard

SummaryThis is a full pipeline from raw CSV to SQL analysis and a working dashboard. Clothing brings in the most revenue, and the low subscription rate looks like a good area to improve.

