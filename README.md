# Data Analytics Final Project---SuperStore-Retail-Orders
Consumer Behavior and Purchase Analysis in Retail Sales - using Python
This repository contains my Data Analytics Final Project, where I perform an Exploratory Data Analysis (EDA) on the SuperStore Retail Orders dataset (sourced from Kaggle).
The dataset contains 5,000 rows and 34 columns of historical retail orders with details such as region, product, customer, shipping, and sales performance. The primary goal of this project is to understand the dataset, clean and preprocess it, and derive meaningful insights that could support business decision-making in areas such as profitability, discount strategy, shipping optimization, and regional performance.
Data Loading & Libraries :
→ Imported essential libraries: NumPy, Pandas, Matplotlib, Seaborn.
→ Loaded dataset using pd.read_csv().
Data Overview : 
→ Checked number of rows and columns (df.shape).
→ Examined column data types (df.dtypes).
→ Viewed first and last rows (df.head(), df.tail()).
→ Generated summary statistics (df.describe()).
Data Cleaning & Preprocessing :
→ Checked for missing values (df.isnull().sum()) → no missing values found.
→ Removed duplicate rows.
Corrected datatypes:
→ Converted Order Date and Ship Date to datetime.
→ Converted categorical columns (e.g., Segment, Region, Ship Mode) to category type.
→ Ensured numerical columns (Sales, Profit, Discount) were correctly set as floats.
Performed EDA & Visualizations based on Univariate,Bivariate and Multivariate Analysis for better deep-dive analysis and developing Key insights.
