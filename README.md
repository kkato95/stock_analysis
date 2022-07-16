# stock_analysis

## Overview of Project:

The purpose of this project is to analyze the 2017 and 2018 stock market data using a refactored code for Module 2 practice to achieve a faster processing speed. We are taking steps to use fewer steps, less memory and we will improve the logic of the code.


## Results: 

We begin our analysis by looping through the rows of our stock market data one time to collect all the required information. We being by setting up a Msgbox in order to indicate which data set the macro should analyze. We then created a ticker Index to acces correct indexes in the 3 output arrays:
1. tickerVolumes
2. tickerStartingPrices
3. tickerEndingPrices

We used for loops to initialize the tickerVolumes, then embedded another for loop to loop over data. Then worte if-then statements to determine if that row is the the first row and, therefore, the starting price and which was the last row to determing stop price. Increases the ticker Index if the next row doesn't matcht the previous. Finally, we loop through our arrays to gather the output for our macro.


Based on our results the refactored code ran in approximatly 1/5 of the time it took to run the original Module 2 - AllStocksAnalysisRefactored(). In 2017 and 2018, the original code took 0.859375 and 0.8515625 seconds to run, respectively. The refractored code for the 2017 data took 0.171875 seconds and for the 2018 data it took 0.1953125 seconds. In 2017, the reactored code took 80% less time than the original and in 2018, it took 77.06% less time than the original.


### 2017 Data

Pre-Refactored Macro Elapsed Time:

![VBA_origianl_2017](https://user-images.githubusercontent.com/99375741/179375157-c4f24dfe-f73b-481a-bfbc-050721ed9b31.png)



2017 Results Data

![VBA_Challenge_2017_table](https://user-images.githubusercontent.com/99375741/179375070-dd012da8-977d-41ed-a832-4d37a5164edd.png)



2017 Elaped time to Run Macro:

![VBA_Challenge_2017](https://user-images.githubusercontent.com/99375741/179375073-d0b883ec-4e88-4ce2-9bbb-1cd1ae682128.png)




### 2018 Data

Pre-Refactored Macro Elapsed Time:

![VBA_origianl_2018](https://user-images.githubusercontent.com/99375741/179375174-4a839957-392f-4161-8dad-33bfdc76f50b.png)



2018 Results Data 

![VBA_Challenge_2018_table](https://user-images.githubusercontent.com/99375741/179375180-092c7110-170d-4efc-a966-23fa50b5bccf.png)



2018 Elaped time to Run Macro:

![VBA_Challenge_2018](https://user-images.githubusercontent.com/99375741/179375186-737317b9-3169-4992-93ca-9c1f0876d53e.png)




## Summary:

1. What are the advantages or disadvantages of refactoring code?

2. How do these pros and cons apply to refactorung the original VBA script?
