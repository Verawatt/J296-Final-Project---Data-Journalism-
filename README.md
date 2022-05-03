# J296-Final-Project---Data-Journalism-
By Vera Watt 

### Data Analysis Process
I downloaded the data from [here](https://www.google.com/url?q=https://databank.worldbank.org/indicator/NY.GDP.MKTP.CD/1ff4a498/Popular-Indicators&sa=D&source=docs&ust=1651611829608631&usg=AOvVaw12VStu5enxiblZPvcq51A6) (countries’ GDP for 2020 the most recent year). Upload it to Google Drive, and open it with Google Sheets.
 

Also I  collect data from different resources: 
 
The following are five questions and step-by-step answers based on the data sets:
 
 
## Questions: 
 
### 1. What is the max and min GDP number (in USD) of the countries that accept refugees, and what was the average number? I was trying to determine if there was a positive correlation between a country’s wealth and the amount of refugees it would accept.
 
Sort the column "GDP” in the data sheet from A->Z
 
            Explanation: First I did this formula : =MIN(E2:E34) and =MAX(E2:E34)
            Max number: $21 (trillion) USA 
            Min Number : $12 (billion)  Moldova 
 
After I  did this formula to find the average number : =AVERAGE(E2:E34)
Average GDP number: $1,293 billion

![Screenshot for min and max GDP](/Q1.png) 

 
 ###     2. Which country had more and less refugees per 1,000 citizens that were accepted?  
        
        I use this formula to find that number. 
         =H34/J34*1000
(Column H number of refugees that left to country / Column J Population of the country )
Moldova has the most refugees
USA has least refugees  

![Screenshot that shows country with less refugees](/Q2.png)  


 
###     3. What factor, distance from Ukraine or wealth of a host country was most important in determining how many refugees would be accepted?
 
Sort the column "GDP RANK" in the data sheet from Z->A (or greatest to smallest), like so:
 
 
=RANK.AVG($E$2:$E$34,$E$2:$E$34,0)
=MIN(E2:E34)
=MAX(E2:E34)
=AVERAGE(E2:E34)
