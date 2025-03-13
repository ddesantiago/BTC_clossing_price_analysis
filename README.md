# Bitcoin Closing Price Analysis

## Project Overview  
This project is designed to practice **data analytics skills** using Python and Tableau. I **extract, clean, visualize, and interpret** Bitcoin closing price data over a 5-year period (2020-2025). Many parts of the code include micro manipulations with detailed comment explanations to practice manipulating data and working in python. The overall goal is to gain familarity with basic python needed to: import/export data, analyze trends, identify patterns, and provide meaningful insights that could guide investment decisions or strategic planning.  

## Guiding Data Question  
**"How have Bitcoin closing prices fluctuated over the last 5 years, and what insights can we draw about its long-term trend and volatility?"**  

## Key Steps in the Project  
1. **Data Extraction**:  
   - Data is pulled from **Yahoo Finance** using the `yfinance` library.  
   - Alternative methods like CSV file loading, web scraping, or API calls are discussed.  

2. **Data Cleaning & Preparation**:  
   - The dataset is checked for missing values and anomalies.  
   - Data types are adjusted for better analysis.  

3. **Exploratory Data Analysis (EDA)**:  
   - Descriptive statistics (mean, median, standard deviation).  
   - Time-series visualization of closing prices using matplotlib and seaborn library.  

4. **Analyzing Monthly & Yearly Trends**:  
   - Manipulate data in order to fit desired chart parameters  
   - Average closing price by month over all years 2020-2025  

5. **Findings & Interpretations**:  
   General:
   - shows continued price increase over 5 years
   - High volatility
     
   Specific:
   - in many years, theres steady 3 month increase from Jan, and the year end close price was higher
   - 2025 is peculiar and significantly higher then previous years    

## Potential Actions & Recommendations
Possible recommendations could include:  
- Beginning of the year is a decent time to buy
- Expected growth if purchased early or held throughtout the year
- **For Long-Term Investors:**  
  - If the data shows a consistent upward trend, **holding Bitcoin long-term** might be a good strategy.  
  - If volatility is extreme, consider **diversifying investments** rather than going all-in on BTC.  

- **For Short-Term Traders:**  
  - Identify recurring price patterns and **trade during high volatility periods** for profit.  
  - Use **moving averages and price trends** to determine optimal entry and exit points.  
 
## Tools & Libraries Used  
- `pandas` (Data manipulation)  
- `yfinance` (Fetching financial data)  
- `matplotlib & seaborn` (Data visualization)  
- `numpy` (Numerical analysis)  

## Future Improvements  
- Larger data set inclduing longer time span
- deeper analysis on other common metrics such as moving averages, rolling averages, etc.
- Expand the analysis by **including other cryptocurrencies** to compare Bitcoin’s performance.  
- Use **machine learning models** to predict future Bitcoin prices.  
- Incorporate **macroeconomic indicators** (inflation, stock market trends) to explain Bitcoin’s price movement.  

This project serves as an **introductory data analytics case study** using cryptocurrency data. The insights can be expanded for more advanced financial modeling and investment strategy development.  
