# Honda-Stock-Analysis 1980-2024
 
# Description
  In this project, I perform an analysis of Honda stock data collected from 1980 to 2024. The main objective of the project is to perform basic Exploratory Data Analysis and in the process I uncover trends and make meaningful visualisations to represent the data. I will also perform correlation analysis and volatility analysis to identify patterns, trends, or anomalies in fluctuating data.

# Key findings
  Some findings from the analysis were: 
    1. Data Quality: The dataset is generally in good condition and suitable for analysis. The only column containing outlier values is the trading volume, with 521 values identified as outliers.

    2. Trading Volume Trends: The trading volume for the stock peaked in the 1980s and began to decline throughout the 1990s. This decline aligns with the stagnation of the Japanese economy during the 1990s, often referred to as the "Lost Decade." The stock trading volume did not show significant recovery until the late 2000s, followed by continuous fluctuations through to the present day.

    3. Volatility Analysis: The stock price demonstrated low volatility (as measured by the difference between daily high and low prices) up until the global economic crisis of 2007-2009. During this period, volatility spiked, with the highest volatility recorded in 2008 at approximately USD 0.84.

    4. Trading Volume in the 1980s: The highest trading volumes were recorded in the 1980s, with the peak occurring on January 1, 1985, when 69.69 million shares were traded. Trading volumes began to decrease in the 1990s, which is consistent with Japan's economic boom in the 1980s followed by a period of stagnation in the 1990s.

    5. Correlation Analysis: A correlation analysis of the price columns reveals an extremely high correlation, with all price-related columns showing values above 0.99. Scatter plots further confirm this, indicating a strong positive correlation between the price columns. 

    6. Correlation between Open and Close Prices: A scatter plot of the open and close prices reveals a strong positive correlation between the two variables. While a trend line is not explicitly shown, the data suggests that the relationship is nearly linear, with a slope close to 1. This indicates that the closing price is approximately equal to the opening price, reflecting a stable market. The absence of significant outliers and the tight clustering of points along the diagonal further support this finding, suggesting that large price fluctuations between the open and close prices are rare. The close alignment of points implies that price changes during the trading day are relatively small, with opening and closing prices being nearly identical.

    7. Correlation between Adj_Close and Close Prices: A scatter plot of the adjusted close and close prices demonstrates a strong correlation, with an R² value of 0.9669. This indicates that approximately 96.7% of the variance in the closing price can be explained by the adjacent closing price, highlighting a highly predictable relationship between consecutive closing prices. However, while the majority of data points follow this trend, there is some spread, especially at higher price levels, suggesting day-to-day fluctuations in the closing price, particularly at elevated price levels.

    8. Volume and Daily Price Change Relationship: A scatter plot of trading volume versus daily price change provides insight into the nature of the relationship. Most trades occurred at low volumes with minimal price changes, suggesting that higher trading activity does not necessarily lead to large price fluctuations for the majority of the dataset. The correlation between volume and price change is weak, with an R² value of 0.0736. While some higher-volume trades do result in noticeable price swings, this is evident in the outliers.

    9. Cumulative Return Analysis: An investigation into the cumulative return over time reveals a generally upward trend, indicating strong stock performance year over year. However, during the global financial crisis (Great Recession), the cumulative return dipped significantly, losing almost half of its value. The stock recovered towards April 2009, highlighting the impact of the economic downturn and the subsequent market recovery.

    10. Moving Averages: The 50-day moving average aligns closely with the adjusted closing price, suggesting that it reacts more quickly to price changes. The 100-day and 200-day moving averages, on the other hand, smooth the data further, lagging behind significant price movements but providing a more stable view of the overall trend.
     

# Tools used
  Jupyter Notebook: For performing the EDA and creating interactive visualizations.
  Python: Primary language used for data manipulation and analysis.

# Libraries**:
  Pandas: For data manipulation and analysis.
  Plotly & Seaborn: For data visualization.
  NumPy: For numerical calculations.
  Statsmodels: for time sereies analysis.

# Installation
  To run this project on your local machine, follow these steps:
    1. Clone the repository: git clone [https://github.com/ryanOO22/Honda-Stock-Analysis.git]
    2. Navigate to the project directory: Honda_Stock_Analysis.
    3. Create a virtual environment and activate it: 
        python -m venv venv
        source venv/bin/activate  # On Windows: venv\Scripts\activate
    4. Install the required dependencies(modules).
    5. Run the jupyter notebook and open it on your browser.

# Usage
  Once you have set up the project, you can open the notebook on your browser to explore Honda's Stock performance throughout the years. The notebook has several visualisations such as:
    1. Historical stock prices over time.
    2. Moving averages and volatility analysis.
    3. Correlation analysis on stock prices.
    4. Comparative analysis.

# Contributions
  Contributions to the project are welcome!

# License
  This project is licensed under the MIT License - see the LICENSE file for details.

# Acknowledgments
  Thank you Yahoo Finance and Kaggle for providing the data for analysis.
  Special thanks to Muhammad Hassan Saboor [https://www.kaggle.com/mhassansaboor] for the inspiration.
