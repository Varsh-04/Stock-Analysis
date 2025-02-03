# Stock-Analysis

## Table of Contents  

- [Project Overview](#project-overview)  
- [Project Goals](#project-goals)  
- [Data Structure Overview](#data-structure-overview)  
- [Executive Summary](#executive-summary)  
- [Insights Deep Dive](#insights-deep-dive)  
  - [Performance (2020 – 2025)](#performance2020--2025) 
  - [Price Behaviour Analysis](#price-behaviour-analysis)  
  - [Correlation Analysis](#correlation-analysis)  
  - [Key Performance Indicators](#key-performance-indicators)  
    - [Daily Percentage Change](#1daily-percentage-change)  
    - [Volume Trend](#2volume-trend)  
    - [Price to Volume Ratio](#3price-to-volume-ratio)  
    - [Price Growth Rate](#4price-growth-rate)  
    - [High and Low by Year](#5high-and-low-by-year)  
- [Summary of Findings](#summary-of-findings)  




# Project Overview

In this project analyzing stock price performance from 2020 to 2025, Tesla (TSLA) saw a peak increase of over 700% in 2020, followed by a decline of 65% in 2022. Amazon (AMZN) achieved a 76% gain in 2020 but fell 50% in 2022. Apple (AAPL) peaked at a 34% increase in 2021, declining 27% in 2022. Microsoft (MSFT) rose by 50% in 2021 but decreased by 28% the following year. Google (GOOG) recorded a 65% gain in 2021, with a 39% decline in 2022. Overall, trading volumes surged in 2020, indicating strong investor confidence, while 2022 marked a period of significant volatility across all stocks, driven by economic pressures.

# Project Goals

- To analyze historical stock price data of Google, Apple, Microsoft, Tesla, and Amazon to identify trends and patterns.
-	To evaluate the performance and volatility of each stock using key financial metrics such as daily returns and cumulative returns.
-	To identify unique patterns and behaviors in the stock prices of each company.
-  To create meaningful visualizations for better interpretation of stock price movements over time.

# Data Structure Overview:

In this project, the data is organized in a tabular format where each row represents a daily record for the stocks of Google, Apple, Microsoft, Tesla, and Amazon. The key columns in the dataset include:
-	Date: The specific date for each stock price entry.
-	Open Price: The price at which the stock opened for trading.
-	Close Price: The closing price of the stock at the end of the trading day.
-	High Price: The highest price the stock reached during the day.
-	Low Price: The lowest price the stock dropped to during the day.
-	Volume: The total number of shares traded that day.

![Screenshot 2025-01-24 121758](https://github.com/user-attachments/assets/714559eb-cead-4360-a2fb-d2c0618c037a)



# Executive Summary:

The stock price analysis of Google, Apple, Amazon, Microsoft, and Tesla examines historical trends, patterns, and key metrics such as opening prices, closing prices, and trading volumes from 2020 to 2025. The study highlights significant growth in Microsoft and Tesla, with highs surpassing $1,000 and $500, respectively, while Google saw a steep upward trend. Apple and Amazon exhibited steady yet fluctuating movements, reflecting market dynamics. This analysis provides insights into stock performance.

# Insights Deep Dive:

## Performance(2020 – 2025)

This project analyses the stock price performance of Google (GOOG), Microsoft (MSFT), Apple (AAPL), Tesla (TSLA), and Amazon (AMZN) from 2020 to 2025, focusing on their best and worst-performing years.

-	Tesla had its **best** year in 2020, with a gain of over 700% due to higher electric vehicle sales and being added to the S&P 500. Its **worst** year was 2022, with a decline of nearly 65%, affected by economic conditions and increased competition.
-	Amazon performed **best** in 2020, with a 76% increase due to higher demand during the pandemic. Its **worst** year was 2022, with a 50% drop due to inflation and slowing growth.
-	Microsoft saw its **best** year in 2021, with a 50% increase driven by growth in cloud computing. Its **worst** year was 2022, with a 28% decline due to falling demand in the tech sector.
-	Apple performed **best** in 2021, with a gain of 34%, supported by strong sales of its products. Its **worst** year was 2022, with a 27% decline caused by supply chain issues.
-	Google had its **best** year in 2021, with a 65% gain from higher digital ad revenue. Its **worst** year was 2022, with a 39% decline due to reduced ad spending.
This project highlights stock trends over five years and provides clear insights into their performance and market factors.

![Screenshot 2025-01-25 112900](https://github.com/user-attachments/assets/e55f9ccc-dd0a-4f6c-84a6-b6c9b2bd6bf2)



## Price Behaviour Analysis:

From the charts, Google shows a steady upward trend, reflecting strong and consistent growth over time. Apple and Amazon have more fluctuating patterns, with overall declines suggesting recent market challenges. Microsoft shows a gradual downward trend, indicating reduced demand or performance. Tesla’s price behaviour is highly volatile, with sharp rises and falls, highlighting its sensitivity to market dynamics and investor sentiment.

![image](https://github.com/user-attachments/assets/a3c60fff-28dd-4537-ab92-983e181fe4a4)


## Correlation Analysis:

The heatmaps reveal that the Open, Close, High, and Low prices for all stocks are almost perfectly correlated, with values close to 1.00, indicating a strong linear relationship. For Google and Microsoft, the Volume has a moderate negative correlation with price metrics, around -0.46 to -0.47, suggesting higher trading volumes might slightly lower prices. Apple, Amazon, and Tesla also show a strong connection among price metrics, but their Volume correlations appear negligible. Overall, these patterns highlight consistent trends in stock price movements with slight variations in Volume dynamics across companies.

![Screenshot 2025-01-25 114936](https://github.com/user-attachments/assets/7347fbfd-0b0b-47ae-bf2a-fc01c6d08a61)



## Key Performance Indicator:

### 1.Daily Percentage Change:
 
The daily percentage changes of Google, Apple, Amazon, Microsoft, and Tesla stocks exhibit varying volatility over time. Google shows fluctuations mostly within ±5%, with occasional spikes beyond ±7.5%, reflecting its relatively stable performance. Apple and Microsoft have narrower ranges, generally within ±4%, indicating lower volatility. Amazon displays a slightly wider range, reaching ±6%, while Tesla exhibits the most volatility, with changes frequently exceeding ±10%, highlighting its high-risk, high-reward nature. These variations underline the differing risk profiles of these stocks, with Tesla being the most volatile and Apple/Microsoft the least.

![image](https://github.com/user-attachments/assets/00032121-eaa5-4f5a-bfe9-2bb44e509653)


### 2.Volume Trend:

Google’s trading volume saw a sharp rise early on, followed by a steady decline over time, reaching low levels in recent years. Apple had a big spike around 2020 but then experienced a downward trend with fluctuations. Amazon's volume has been consistently dropping, despite a slight uptick around 2022. Microsoft followed a similar pattern, with an initial decline, a brief recovery, and then a further drop. Tesla had a major peak in 2020, followed by a sharp drop, a small recovery in 2023, and then another decline.
Overall, all five stocks show a declining volume trend, indicating that trading activity has reduced over time, possibly due to market maturity, investor sentiment shifts, or reduced short-term speculation.

![image](https://github.com/user-attachments/assets/8805de09-e4d2-4d47-8ab9-641df2448b54)


### 3.Price to Volume Ratio:

Google's stock price has seen a sharp rise, crossing 150 by 2025, while its trading volume has declined below 0.2 billion. Apple's price steadily increased beyond 200, whereas its volume dropped from 150M to below 50M. Amazon showed a fluctuating trend, with the price surging past 200 in 2025, but volume falling under 50M. Microsoft’s price remained volatile, peaking near 400, while its volume hovered around 30M. Tesla’s price surged above 300 by 2025, with volume showing an inverse pattern, dipping below 100M.
Overall, stock prices for these major companies have shown upward momentum, whereas trading volumes have generally declined, suggesting a shift toward long-term holdings and reduced speculative trading.

- Blue – Price
- Purple - Volume
                                                           
![image](https://github.com/user-attachments/assets/4a02f004-51c0-45d0-a11f-4cf862f3261a)


### 4.Price Growth Rate:

The stock prices of major tech companies have shown significant growth from 2020 to 2025. Google’s price surged past 200, maintaining a steady upward trend. Apple exhibited a consistent rise, reaching approximately 200 by 2025. Amazon, despite fluctuations, crossed 200, reflecting volatility in its growth. Microsoft steadily increased, touching nearly 400, making it one of the strongest performers. Tesla experienced a dip around 2023 but recovered sharply, surpassing 400 in 2025.
Overall, all five stocks have shown a positive price trend, with Microsoft and Tesla achieving the highest growth, while Amazon displayed more volatility in its price movement.

![image](https://github.com/user-attachments/assets/e2ca9275-f382-4edf-a8d4-ce4c5339d267)


### 5.High and Low by Year:

The line charts show the yearly high and low stock prices of Google, Apple, Amazon, Microsoft, and Tesla from 2020 to 2025. Google's stock saw a steep rise, reaching over $200 by 2025. Apple's high price increased steadily, surpassing $500 in 2025. Amazon's stock fluctuated but ended near $500 in 2025. Microsoft's stock showed strong growth, with highs exceeding $1,000. Tesla's stock price also surged significantly, surpassing $500 in 2025.

![image](https://github.com/user-attachments/assets/35e09d16-2f3f-4a41-9342-d057bce14fac)


# Summary of Findings:

The stock price analysis of Google, Apple, Amazon, Microsoft, and Tesla from 2020 to 2025 reveals distinct performance trends and market behaviors. Microsoft and Tesla showed the highest price growth, with Microsoft surpassing $1,000 and Tesla exceeding $500 by 2025. Price behavior analysis indicates steady growth in Apple and Amazon, while Google experienced a sharp upward trend. Correlation analysis suggests a strong relationship between tech stocks, with synchronized movements during market fluctuations. Key performance indicators highlight that daily percentage changes were most volatile for Tesla, while Microsoft led in volume trends. The price-to-volume ratio indicated strong investor interest in Google and Apple, whereas Tesla exhibited the highest price growth rate. Highs and lows by year reflected overall market sentiment, with all five stocks reaching peak values in 2025. This study provides valuable insights into stock trends, aiding investors in strategic decision-making.



👉 [View Dashboard](https://app.powerbi.com/view?r=r=eyJrIjoiMzY3ZmNiNzQtMTE5NC00MGY4LTlkZjYtNTM3OGIxMjVlNmU2IiwidCI6IjY4ZWQyOTMyLWU2ZmQtNGViYS04NjQ1LTAwOWY3ZTc3OWRkNCJ9")



















