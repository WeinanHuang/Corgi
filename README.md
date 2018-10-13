# Dummy-Stock-Advisor
*Author: Weinan Huang*  
*Contact: ray.weinanhuang@gmail.com*  
*Last Modified Date: 2018-10-13*  

## Objective
[TEMP]Get advice on investment strategy.

## Structure
1. News Reader  
   1. **Data** Get News feed 
      - Use Reuters News API
      - Get headlines
      - Organize in a Pandas DataFrame format
   2. **Model** Score stock 
      - Need a *y*! => stock market price daily data => Alpha Vantage
   3. Get positive and negative individuals  

2. Price Reader  
   1. **Data** Get stock price in time series order  
       - Data source: Alpha Vantage  
   2. **Model** Predict stock price  
