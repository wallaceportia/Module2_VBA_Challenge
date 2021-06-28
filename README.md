# Module2_VBA_Challenge

###Project Purpose

The purpose of this project is to understand how VBS can help us with a complex task such as analysing the viablilty of stocks by evaluating the performance of a stock based on the yearly return which is the percentage differene between price at the beginning of the year and the end of the year.  The excercise goes futher to help us understand how using a process of refactoring can make our codes more effiecient for the end user to recieve the information in real time

##Results

We were able to determine from the analysis that the only two stocks were viable ENPH that had a return of 81.9% and RUN which had a return of 84.0%. DQ turns out to be not a viable invest and perhaps one of the least viable with a loss of 62.6 percent.

![]DABC-CU.resources.VBA_Challenge_2017.png


##Advantages and Disadvantages of refactoring code 

Three advantages of refactoring a code is that, firstly, it makes the code easier and more logical to read for the next user, secondly it allows for fewer steps to be taken thereby saving time and thirdly it uses less memory and therefore produces results much faster. However there might be disadvantages such as because steps are now more condensed it might be more difficult to find bugs. Removing some steps can also mean that someone else may have a harder time following the logic of the code.

For this project using the original there were more steps and I felt that it was easier to follow in terms of the fact that we used two different iterators for differnt purposes.  We used the iterator (i) to loop throught the tickers and we used the iterator j to loop through the entire sheet.  Therefore if an error was made in one area of this code it was easier to find.  However the code took longer to run, in 2017 it took 78262.96 seconds to run and in 2018 it took 78300.4 seconds to run.

When the code was refactored there was less steps, my personal experience was that it was more difficult to debug. However the code was definately more effiecient in running and this was evident in that in 2017 it took only 0.0859375 seconds to return the value and in 2018 it took 0.09375 seconds the value. It can therefore be concluded that the refactoring is causing the code to use  
