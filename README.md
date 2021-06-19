# Stock Analysis using VBA

## Overview of Project
To perform data analysis on stock data to determine which stock is better for investment.

### Purpose
To analyze different stocks data throughout multiple years to see which stocks performed better.To achieve this purpose, yearly volume is calculated for each stock along with yearly return.The original code is then refactored to check efficiency.

## Results
### Refactored script
Refactoring is a coding process to make the code more efficient—by taking fewer steps, using less memory, or improving the logic of the code to make it easier to read.
TickerIndex variable is created to access the correct index across four different arrays: ticker array, tickerVolumes,tickerStartingprice and tickerEndingprice, iterating over all the rows.

#### Refactored code

![image](https://user-images.githubusercontent.com/84524153/122627964-1f55b000-d081-11eb-8ce5-3781c1fbbec5.png)
![refactoredcode2](https://user-images.githubusercontent.com/84524153/122627971-372d3400-d081-11eb-89e8-e66ff9897168.png)

The refactored code execution time is less for year 2017 and 2018 than original code run time for 2017 and 2018.
##### Refactored code Runtime
![VBA_Challenge_2017 png](https://user-images.githubusercontent.com/84524153/122628070-ee29af80-d081-11eb-9dad-9e33d449e2e4.png)
![VBA_Challenge_2018 png](https://user-images.githubusercontent.com/84524153/122628072-f255cd00-d081-11eb-9c20-73553567e52c.png)
##### Original code Runtime
![original code(runtime)-2017](https://user-images.githubusercontent.com/84524153/122628252-1665de00-d083-11eb-8a56-277a85b6f184.png)
![original code(runtime)-2018](https://user-images.githubusercontent.com/84524153/122628082-0d284180-d082-11eb-8adb-ab1e53ba51be.png)

##### The stocks performed better in 2017 than in 2018

![2017-stocks](https://user-images.githubusercontent.com/84524153/122628397-c9ced280-d083-11eb-8502-4041c1c32fd9.png)
![2018-stocks](https://user-images.githubusercontent.com/84524153/122628399-ce938680-d083-11eb-8562-e1ad868144c8.png)

## Summary
###### 1-What are the advantages or disadvantages of refactoring code?

Advantages: Refactoring is good  to maintain the code. It makes the code clean and organized.

Disadvantages: It's risky when the application is big and  when the existing code doesn't have proper test and understanding.

###### 2-How do these pros and cons apply to refactoring the original VBA script?

The refactored code executed faster than the original code but if the orginal code isn't fully understood, it will create errors.
