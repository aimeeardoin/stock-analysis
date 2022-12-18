# Green Stock Analysys
#
#Steve and his parents are using Visual Basic to analyze stock performances by year and volume.  Previous code ran successfully, but the purpose of this project is to #attempt to speed up the code runtime to analyze of large datasets.If the code can be refactored for faster runtime, then the scope of the project is broader and Steve #can be more successful.
#
#Results of Refactoring
#Previous code, although functional, iterated through the data at least 4 times and took approximately .6 seconds to run for the provided data in years 2017 and 2018 for 12 stocks.  By changing the nesting order of the for loops, there were relational references so that the code took less time to complete.  See lines below:

Refactored Code.png

By structuring the code differently, the runtime decreased dramatically, running nearly 4 times as fast for this dataset. See screenshots below:
https://github.com/aimeeardoin/stock-analysis/blob/main/2017%20runtime.png



Summary: In a summary statement, address the following questions.
What are the advantages or disadvantages of refactoring code?
How do these pros and cons apply to refactoring the original VBA script?
