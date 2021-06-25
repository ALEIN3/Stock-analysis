# Stock-analysis
Using VBA to analyze stocks' data



# Overview of Project

## The Purpose of our project (the refactoring)
The goal for this project is to provide a more efficient script than the original script, more efficient could mean faster processing time or more understandable steps.

## The Purpose of the report we are creating

The original script was created to provide an analysis for a list of 12 clean energy stocks to find the best performing stocks for the years 2017 and 2018. The performance will be defined by using two factors, the Total daily volume, and the Return.

# Results

## Analysis
### The outcomes of the original Vs. refactored  
#### 2017 

 ##### Original: the time to run the code was 0.9296875 seconds
 
 ![](https://github.com/ALEIN3/Stock-analysis/blob/main/resources/2017_original.png)
 
 ##### Refactored: the time to run the code was 0.171875 seconds
 
 ![](https://github.com/ALEIN3/Stock-analysis/blob/main/resources/2017%20refactored.png)
 
#### 2018 

 ##### Original: the time to run the code was 0.7695313 seconds
 
 ![](https://github.com/ALEIN3/Stock-analysis/blob/main/resources/2018%20original.png)
 
 ##### Refactored: the time to run the code was 0.1171875 seconds
 ![](https://github.com/ALEIN3/Stock-analysis/blob/main/resources/2018%20refactored.png)
 
### Explaining the difference between the original code Vs. refactored code

 We can find that for the data of 2017 it took the refactored code to run 18.5% of the time that was consumed to run by the original code, and for 2018 it took the refactored code to run 15.2% of the time that was consumed to run by the original code.
There is more than one adjustment that has been made to the original code. Still, the main and the most effective one that helped us to achieve those results is adjusting the nested loop function from the original code, this nested loop helps in calculating the starting price and the closing price for each ticker so that we can calculate the return, the nested loop that used in the original code will go over all the rows in the sheet many times, where is the scenario is different for the refactored code, where the code has to go over the rows one time to get the same results that we got from the original code.

#### The Original code(nested loop)

![](https://github.com/ALEIN3/Stock-analysis/blob/main/resources/original%20code(%20nested%20loop).png)

#### The refactored Loop

![](https://github.com/ALEIN3/Stock-analysis/blob/main/resources/Refactored%20code.png)

# Results
 As a summary, nowadays in the business world, the people who in charge of every project try to reach the best results in the shortest time, the most cost-efficient way, and since technology is the heart of our development, we are using more and more codes to automate tasks, so we apply more refactoring as well, and for the refactoring, we can find the advantages and disadvantages as follows:
### Advantages 
1.	Refactoring Improves the Design of Software
2.	Refactoring Makes Software Easier to Understand
3.	Refactoring Helps Finding Bugs
4.	Refactoring Helps Programming Faster

### Disadvantages

1.	Run out of money
2.	Run out of time

For our project :
### Advantages:
For both years 2017 and 2018, when we used the refactored code, we saved more than 80% of the time needed to run the original code, and the code is better to understand. 
### The disadvantages:
In realty, we created two codes to get the same result, and in many cases and in real life we don’t have that type of luxury. 
