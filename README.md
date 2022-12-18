# Green Stock Analysys
#**Overview of Project**
#Steve and his parents are using Visual Basic to analyze stock performances by year and volume.  Previous code ran successfully, but the purpose of this project is to attempt to speed up the code runtime to analyze of large datasets.If the code can be refactored for faster runtime, then the scope of the project is broader and Steve can be more successful.
#
**#Results of Refactoring**
#Previous code, although functional, iterated through the data at least 4 times and took approximately .6 seconds to run for the provided data in years 2017 and 2018 for 12 stocks.  By changing the nesting order of the for loops, there were relational references so that the code took less time to complete.  See lines below:

https://github.com/aimeeardoin/stock-analysis/blob/main/Refactored%20Code.png

By structuring the code differently, the runtime decreased dramatically, running nearly 4 times as fast for this dataset. See screenshots below:
https://github.com/aimeeardoin/stock-analysis/blob/main/2017%20runtime.png
https://github.com/aimeeardoin/stock-analysis/blob/main/2018runtime.png


**Summary**:
#Refactoring the code successfully reduced the runtime of the code from .6 seconds to .13 seconds, approximately a factor of 4.  By saving iterations through the entird set, we experienced a benefit of refactoring the code.Efficiency is important and is a clear justification for refactoring code. If Steve pulls in larger amounts of data that save runtime, that scaling the function of the code. However, refactoring is not always the answer.  Coding dependencies should be carefully considered and refactored code tested globally throughout, otherwise it could be detrimental to the program. In this case, the refactoring was all success.  Steve's going to be able to analyze more data in less time with this basic code. Time is money!

