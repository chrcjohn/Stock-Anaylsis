# Stock-Analysis
## Project Overview
Steve is a client who needs code that analyzes stock market results for different years to find stocks that are good investments for his parents.
He ran the data provided and wrote code to analyze 12 different stocks.The original code I wrote didn't work well with a data set of this size. So the goal of this project was to make the existing code more efficient and quickly analyze thousands of different stocks.
Creates additional variables and output arrays and formats them into the code so that only the "for loop" needs to be run to parse the results, making it run more efficiently.
These additional variables and arrays allow your code to store data and use variables to perform analysis. The original code and the refactored code have the same result, and you can see the difference in the execution time of each code when using the VBA timer function. Image of code and timer The output array was created using the following code.

## Results
The first image below shows how long it took to run the refactored code in 2017.
It may seem like a small change, but even a fraction of a second can make a big difference when running your code, especially when working with large datasets. The next image below shows the time it took to run the refactored code in 2018.
##VBA_Challenge_2018.png![VBA_Challenge_2018](https://user-images.githubusercontent.com/23088053/217998199-d2b7f001-c5bd-4126-a85a-088bc3f1a960.png)
 The original code took 1.3633 seconds to run.
##VBA_Challenge_2018.png 
![VBA_Challenge_2017](https://user-images.githubusercontent.com/23088053/217998232-7daa9983-84bc-4081-8d82-af7c73d7b2cb.png)
The original code took 1.3633 seconds to run. Again, this is a big improvement and it performs more efficiently on large data sets. 

## Conclusion 

Benefits of Refactoring As this analysis shows, good code refactoring is beneficial.
This allows this code to analyze larger data sets.
You can run your code efficiently using only one main "for loop" and storing data in variables and arrays.
Your original code worked and got the same result i.e. the client
