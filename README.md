# Economic-data-analysis

ECONOMIC DATA ANALYSIS FOR BUSINESS AND MARKET INSIGHT

PROJECT OVERVIEW

This project focuses on analyzing a comprehensive sales dataset to uncover trends in revenue, profit, customer behavior, and product performance. It also integrates economic indicators like GDP, inflation, interest rates, and unemployment for time series forecasting and macroeconomic analysis. The project combines financial, economic, and sales-level data to support informed decision-making for pricing, marketing, and strategic planning.

OBJECTIVES

Understand trends in customer purchasing behavior based on age, gender, and region.
Analyze monthly revenue and cost patterns to evaluate profitability.
Measure and compare product performance across categories and countries.
Perform time series forecasting using macroeconomic data such as GDP.
Develop insights that help forecast future performance and improve business strategies.

TOOLS AND TECHNOLOGIES USED

Python (Pandas, NumPy, Matplotlib, Seaborn, Plotly, Statsmodels, Scikit-learn)
Excel for data preview
SQL (optional for backend data joins)
Google Drive for data source integration
Jupyter Notebook for step-by-step implementation

DATA SOURCES

Primary sales data containing customer age, gender, product categories, quantities, prices, and revenue
Macroeconomic data including GDP, unemployment, inflation, and interest rates from World Bank and FRED

KEY FEATURES OF SALES DATA

Includes year, month, customer age, gender, country, state, product category and subcategory
Each transaction records quantity, unit cost, unit price, total cost, revenue, profit, and profit margin
Supports monthly trend analysis and segmentation by customer demographics and geography

DATA CLEANING AND TRANSFORMATION

Null values were removed or replaced.
String-based numeric fields like quantity, unit cost, and revenue were converted to proper numeric formats.
Dates were converted to datetime type and used to extract year and year-month for grouping.
Profit and profit margin were calculated for each transaction.
Unnecessary columns such as placeholders were dropped.
Categorical values were standardized for consistency in grouping and visualization.

SALES AND PROFIT ANALYSIS

Monthly revenue and cost were aggregated and visualized using line plots. Revenue showed strong growth from early 2015 to late 2015, peaked in December 2015, and dropped in July 2016. Cost followed a similar trend, though it exceeded revenue in some early months, resulting in negative profit. Profit margins improved significantly in late 2015 and throughout 2016. Profit trend by subcategory showed Road Bikes and Mountain Bikes generated high revenue but had low profit margins.

PRODUCT ANALYSIS BY CATEGORY

Tires and Tubes were the highest selling subcategory in terms of quantity. Bike Racks had the highest average profit margin, while Mountain Bikes and Road Bikes had the lowest margins. Subcategories like Helmets, Gloves, and Shorts showed both healthy sales and solid profit margins.

CUSTOMER DEMOGRAPHICS ANALYSIS

Most purchases came from customers aged between 30 and 45. Younger age groups showed interest in accessories and apparel, while older customers tended to purchase bikes. Subcategory analysis revealed that products like Helmets, Bottles and Tubes, and Shorts were popular across most age segments.

COUNTRY-WISE PERFORMANCE

France, Germany, United States, and United Kingdom were the main markets. The highest profits were recorded in Germany and the United States. Tires and Tubes were the top-selling subcategory in all countries.

MACROECONOMIC ANALYSIS AND FORECASTING

Macroeconomic indicators were downloaded from external sources (FRED, World Bank). The data was cleaned, merged, and visualized to study trends and correlations between GDP, unemployment, inflation, and interest rates. Time series analysis was performed on GDP using seasonal decomposition and ARIMA modeling. A forecast was generated for the next 12 months using ARIMA, and the model's performance was measured using Mean Squared Error.

INSIGHTS

Sales peaked in December 2015 and reached their lowest point in July 2016.
Cost and revenue follow similar trends, but high cost months often led to losses.
Product-level profitability varies significantly—high-selling products do not always generate high profits.
Younger customers prefer accessories, while middle-aged customers tend to buy bikes.
All four countries shared the same top-selling product subcategory: Tires and Tubes.
Profit margins vary by subcategory and region, emphasizing the need for strategic pricing.
Macroeconomic indicators are correlated—unemployment and interest rates tend to inversely track GDP.
Forecasting GDP using ARIMA gave acceptable accuracy and identified potential turning points.

CONCLUSION

This project successfully blends business transaction data and macroeconomic indicators to deliver both operational and strategic insights. Sales and profitability were analyzed across time, product lines, customer demographics, and geography. In parallel, time series modeling on economic indicators provided future outlooks. These findings can support executive decisions in pricing, marketing, resource allocation, and expansion planning. This analysis can be expanded further with advanced machine learning models, dashboards, or integrated business intelligence platforms.
