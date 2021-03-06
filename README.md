# VBA Challenge
 
## Project Overview

The purpose of this analyisis is to refractor our module 2 VBA code for Stocks Analysis to  collect the same information that we did for all our stocks and determine if our refracted code was succesfull and more effcient. In simple terms, we'll see if our VBA script ran faster while giving us the same results.

## Results

After reviewing the data for the stocks in  2017 and 2018 in Steve's workbook we can see that all stocks in 2017 had a positive return except one. On the contrary, in 2018 most of our stocks gave a negative return except those from "ENPH" and "RUN". We can conclude thar the stocks were more profitable in 2017 and if you're are going to choose a stock to invest should only be on the two that have a positive return in both years.

![image](https://user-images.githubusercontent.com/99451833/155895442-3a7ae766-f774-438b-aee5-11b65caa8f3f.png) ![image](https://user-images.githubusercontent.com/99451833/155895897-d6e96e70-2e25-477f-8e33-f8cad862b44c.png)

When we refactored the code, we created output arrays for each ticker's volume, starting price, and ending price. We then use the ticketIndex variable we created to obtain our results. (Use link below to see code)

https://github.com/gotica462/VBA_Challenge/blob/main/VBA_Challenge_Creating_Array_Outputs.png


We use the arrays so We don’t have to declare one type of variable multiple times, this helps us with organization, speed and also if our data grows we would be able to edit our code more faster and easier. As we can see, our refracted code runs almost 10x faster than our original module code. (See images below)

Original Code(Left) vs Retracted Code (Right)    
![image](https://github.com/gotica462/VBA_Challenge/blob/main/2017_runningtime_without_refraction.png) ![image](https://github.com/gotica462/VBA_Challenge/blob/main/VBA_Challenge_2017.png)

![image](https://github.com/gotica462/VBA_Challenge/blob/main/2018_runningtime_without_refraction.png) ![image](https://github.com/gotica462/VBA_Challenge/blob/main/VBA_Challenge_2018.png)

## Summary

Refactoring is a key part of the coding process. When refactoring code, you aren’t adding new functionality; you just want to make the code more efficient—by taking fewer steps, using less memory, or improving the logic of the code to make it easier for future users to read. Let's think about this in another way, suppose you are a writer writing a book, you are not going to publish your first draft, you need to revise it several times, maybe edit a few parts, trim some chapters, may add a few things here or there and after several revision and rewrites you'll publish a final and more polished products. The same applies to coding, usually your first attempt will not always be the best, and maybe if you revisit your code you can improve it by editing certaing things to make it more efficiently. 
We can see that refactoring has many advantages, However, one of the drawbacks it is that is time consumming and detailed oriented, but if you do it right you will save a lot of time in the future. so in the end, It's worth to spend more time if our code it's more cleaner and effcient.
In our particular case refactoring not only improved the speed of our code, but we also set up a framework in case we want to add more data to our Worksheets. For example, If we suddenly have more stocks to analyze, we will only have to change the lenght of our array and only set the  value of our new variables one time for each and our code would still work with the new information




    











