# Stock Analysis

## Overview
This project uses stock market data to perform analysis for Steve to determine if investing in green stocks is a good option. This project uses VBA scripts to automate the analysis and then refactors the code for performance optimization.

## Results
### Stock Analysis
This project used an extract of 2017 and 2018 stock data for 12 green stocks. For 2017, all the stocks performrd well except for "TERP", which had a negative return. "DQ" stock had the highest return for 2017. In 2018, most of the stocks performed badly. Only two stocks "ENPH" and "RUN" had positive returns.

### Performance Analysis
The initial code that was built had for loops that looped through the entire data for each stock. This caused the analysis to run for a longer time, approximately 24 seconds for each year. The refactored code does not loop through all the data for each ticker and uses indexes to perform the analysis. This reduced the processing time considerably as shown in the below images.

![2017 Refactored](https://github.com/ssathyanath/stock-analysis/blob/master/Resources/VBA_Challenge_2017.PNG)

![2018 Refactored](https://github.com/ssathyanath/stock-analysis/blob/master/Resources/VBA_Challenge_2018.png)


## Summary
### Advantages and Disadvantages of Refactoring
Refactoring a code has a lot of advantages. Refactoring often reduces the processing time and optimizes the code performance. It also often reduces the number of lines in a code and reuses existing code. A disadvantage of refactoring is that, the code becomes complex and might not be easy to understand.

### Advantages and Disadvantages of the original and refactored VBA script
The refactored code took lesser time to process when compared to the original code. Incase, we need to scale the analysis to include many more stock tickers, the processing time would not increase considerably with the refactored code. An disadvantage is that, the code is a little more complex now compared the original code and might be hard to follow.

