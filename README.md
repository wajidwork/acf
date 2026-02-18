Data Analysis Project – From Data Cleaning to Hypothesis Testing
Project notebook:https://www.kaggle.com/code/nargessaeed/data-analysis-project-from-data-cleaning-to-hypoth
Dataset: /kaggle/input/sales-forecasting

Introduction
In this project, I analyze a sales dataset using the main stages of a data scientist’s workflow. The goal is to extract actionable insights for business decisions by applying data cleaning, visualization, and hypothesis testing.

Data Source
The dataset includes sales transactions details such as order date, ship date, product name, sales , region, and more.
(Example: Global Superstore Dataset on Kaggle)

Step 1: Data Cleaning
Checked and removed duplicate rows.
Converted date columns ('Order Date', 'Ship Date') to datetime format.
Handled missing or invalid values using appropriate pandas functions.
Standardized column names to avoid errors in analysis.
Step 2: Exploratory Data Analysis (EDA)
Analyzed sales by product to identify best sellers.
Measured total and average sales across different regions.
Visualized order trends over time using line charts.
Used bar plots and other charts to highlight important patterns.
Step 3: Hypothesis Testing
Compared sales between key regions using statistical t-tests.
Null hypothesis: No significant difference in average sales between regions.
Found significant differences (p-value < 0.05), suggesting real business trends.
Results & Insights
Region West outperformed others in total sales.
Certain products consistently ranked highest in revenue.
Statistically, region differences are not by chance.
Recommendations: invest more in top-performing regions/products and monitor periods with rising order trends.
Conclusion
This project demonstrates how structured data analysis and hypothesis testing lead to actionable insights. The workflow used here is highly relevant to many real business problems.
