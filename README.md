# Stock-Analysis
## Overview of Project
The purpose of this analysis was to break down stock market performance across multiple years to provide the most accurate recommendation to our client Steve 

## Results
Using images and examples of your code, compare the stock performance between 2017 and 2018, as well as the execution times of the original script and the refactored script.

We can see by running our script that stock performance was much stronger in 2017 than 2018. In 2017, all but one Tickers saw great returns on Total Daily Volume (the exception being TERP at -7.2%). Additionally, four Tickers saw 100+% returns on Total Daily Volume.

![image](https://github.com/cmauch24/Stock-Analysis/blob/e96757a4383ddca0badccd7141eaafc8897fd72b/2017%20Stocks.png)

In 2018, returns were not so kind. All tickers with the exception of ENPH and RUN saw negative returns on Total Daily Volume. The majority of these saw double digit negative returns. The two bright spots were quite strong with their returns however, with ENPH and RUN returning 81.9% and 84%. With a 129.5% return in 2017 and the aforementioned 84% return in 2018, the most attractive stock ticker analyzed was ENPH.

![image](https://github.com/cmauch24/Stock-Analysis/blob/e96757a4383ddca0badccd7141eaafc8897fd72b/2018%20Stocks.png)

## Summary
Refactoring code allows us to take a script that is already written and performs well and expand it. This expansion can either be improvement of performance of our code or enabling the code to look at a broader data set. For example, here is an addition to the code added by refactoring - timing how long the analysis took and letting us know.

![image](https://github.com/cmauch24/Stock-Analysis/blob/e96757a4383ddca0badccd7141eaafc8897fd72b/VBA_Challenge_2017.png)
![image](https://github.com/cmauch24/Stock-Analysis/blob/e96757a4383ddca0badccd7141eaafc8897fd72b/VBA_Challenge_2018.png)

Refactoring the original script in this case provided a lot of advantages. Firstly, it allows the user to choose which year (2017 or 2018) that they wanted to analyze. From there, the new script provides a breakdown of Total Daily Volume performance of all stocks for the year the user selected
