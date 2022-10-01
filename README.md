# Stock-Analysis
### Overview of the Project
   This project's purpose was to refactor code used to analyze stocks in order to make it run faster. 
  The code needs to be refractored because its purpose was originally intended to analyze a few dozen stocks but it may not be useful or may take to long to run when the entire stock market is included. 
  The original code took around an entire second to finish running and after the changes that time was cut down to around .15 seconds. 
  ### Results
   When comparing the results of the two codes there is a very clear benefit to using the new refactored code. 
   The speed of the new code is significantly faster. Where the original code took around a second to complete the new code is done within .15 seconds. This is a significant change in speed.
   When more stock data is added to the worksheet this code will be much better at handling a larger amount 
   
![2018 Speed](https://user-images.githubusercontent.com/105613428/174417492-92b73821-6fc7-4361-99e5-d59e239dac59.png)
![2017 Speed](https://user-images.githubusercontent.com/105613428/174417502-187ebd1e-3165-438d-8828-18491ed29874.png)

This increase of speed came from adding three arrays to the macro. The added arrays allow for the data to be sorted through more efficently and help speed up the process and allows for more data to be included and analyized.

![Capture](https://user-images.githubusercontent.com/105613428/174456735-109a60d0-9bcf-40aa-9790-155de8e0883d.PNG)
### Summary
The pros of refactoring code is that it can be used to make working code work even better. Efficiency is always the goal when it comes to creating and running macros so it makes sense to revise code in order to make it better. It can also be used to repurpose code to deal with larger data sets like what we did with this project. A con of refactoring code is that you could take code that you know works and break it leading to new errors and wasting time on it.
The pros of refactoring this particular code was the increase in speed. It was made significantly faster but I did break the code and had to spend alot of time fixing it and making it workable 
