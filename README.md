# stock_analysis

## Overview of Project:

The purpose of this project is to analyze the 2017 and 2018 stock market data using a refactored code for Module 2 practice to achieve a faster processing speed. We are taking steps to use fewer steps, less memory and we will improve the logic of the code.


## Results: 

We begin our analysis by looping through the rows of our stock market data one time to collect all the required information. We being by setting up a Msgbox in order to indicate which data set the macro should analyze. We then created a ticker Index to acces correct indexes in the 3 output arrays:
1. tickerVolumes
2. tickerStartingPrices
3. tickerEndingPrices

We used for loops to initialize the tickerVolumes, then embedded another for loop to loop over data. Then worte if-then statements to determine if that row is the the first row and, therefore, the starting price and which was the last row to determing stop price. Increases the ticker Index if the next row doesn't matcht the previous. Finally, we loop through our arrays to gather the output for our macro.




### 2017 Data

2017 Results Data

![VBA_Challenge_2017_table](https://user-images.githubusercontent.com/99375741/179375070-dd012da8-977d-41ed-a832-4d37a5164edd.png)

2017 Elaped time to Run Macro:

![VBA_Challenge_2017](https://user-images.githubusercontent.com/99375741/179375073-d0b883ec-4e88-4ce2-9bbb-1cd1ae682128.png)




### 2018 Data

2018 Results Data 

2018 Elaped time to Run Macro:




## Summary:

1. What are the advantages or disadvantages of refactoring code?

2. How do these pros and cons apply to refactorung the original VBA script?
