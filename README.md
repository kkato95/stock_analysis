# stock_analysis

## Overview of Project:

The purpose of this project is to analyze the 2017 and 2018 stock market data by building a refactored code, based on Module 2's practice code, which we will call the orginal code. The purpose of this refactored code is to achieve a faster processing speed by taking fewer steps, utilizing less memory, and improving the logic of the code. Our oringinal code analyzed the data for either the 2017 or 2018 stock market data, then built a table that included the ticker, the total daily volume of that ticker, and the percent return achieved. 

## Results: 

We begin our analysis by looping through the rows of our stock market data one time to collect all the required information. We being by setting up a Msgbox in order to indicate which data set the macro should analyze. We then created a ticker Index to acces correct indexes in the 3 output arrays:
1. tickerVolumes
2. tickerStartingPrices
3. tickerEndingPrices

We used for loops to initialize the tickerVolumes, then embedded another for loop to loop over data. Then worte if-then statements to determine if that row is the the first row and, therefore, the starting price and which was the last row to determing stop price. Increases the ticker Index if the next row doesn't matcht the previous. Finally, we loop through our arrays to gather the output for our macro.


Based on our results the refactored code ran in approximatly 1/5 of the time it took to run the original Module 2 - AllStocksAnalysisRefactored(). In 2017 and 2018, the original code took 0.859375 and 0.8515625 seconds to run, respectively. The refractored code for the 2017 data took 0.171875 seconds and for the 2018 data it took 0.1953125 seconds. In 2017, the reactored code took 80% less time than the original and in 2018, it took 77.06% less time than the original.




### 2017 Data

2017 Results Data

![VBA_Challenge_2017_table](https://user-images.githubusercontent.com/99375741/179375070-dd012da8-977d-41ed-a832-4d37a5164edd.png)



Pre-Refactored Macro Elapsed Time:

![VBA_origianl_2017](https://user-images.githubusercontent.com/99375741/179375157-c4f24dfe-f73b-481a-bfbc-050721ed9b31.png)



2017 Elaped time to Run Macro:

![VBA_Challenge_2017](https://user-images.githubusercontent.com/99375741/179375073-d0b883ec-4e88-4ce2-9bbb-1cd1ae682128.png)







### 2018 Data

2018 Results Data 

![VBA_Challenge_2018_table](https://user-images.githubusercontent.com/99375741/179375180-092c7110-170d-4efc-a966-23fa50b5bccf.png)



Pre-Refactored Macro Elapsed Time:

![VBA_origianl_2018](https://user-images.githubusercontent.com/99375741/179375174-4a839957-392f-4161-8dad-33bfdc76f50b.png)



2018 Elaped time to Run Macro:

![VBA_Challenge_2018](https://user-images.githubusercontent.com/99375741/179375186-737317b9-3169-4992-93ca-9c1f0876d53e.png)






## Summary:

1. What are the advantages or disadvantages of refactoring code?
The primary advantage of refactoring the code is that it runs nearly 5x as fast as the original code. This would be very beneficial if we were to analyze many more data points. The main disadvantage would be the amount of code and the time it requires to refactor it.

2. How do these pros and cons apply to refactorung the original VBA script?
The con seems to have an outsized influence on this decision. Because the original code ran in under 1 second for both years' datasets, the original was still very fast. The amount of time it took to refactor the code in comparison to how much speed was gained, shows the refactoring code is unnessisary.
