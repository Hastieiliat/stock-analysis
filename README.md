## stock-analysis
Module2
# Overview of Project: Explain the purpose of this analysis.
Steve wants to find the total daily volume and yearly return for each stock. Daily volume is the total number of shares traded throughout the day; it measures how actively a stock is traded. The yearly return is the percentage difference in price from the beginning of the year to the end of the year. Steve's parents are starting to pester him about 12 stock.
# Results: Using images and examples of your code, compare the stock performance between 2017 and 2018, as well as the execution times of the original script and the refactored script.

Refactored
![image](https://user-images.githubusercontent.com/100230706/156905521-967a0cab-2cea-4b55-988b-6a67434c9867.png)
original

![VBA_Challenge_2017](https://user-images.githubusercontent.com/100230706/156905233-1dc88e00-99f4-42ac-bad8-315f0922879d.png)

original 
![VBA_Challenge_2018](https://user-images.githubusercontent.com/100230706/156905238-fd3d479e-3f8b-4fde-80d3-883aa8e4a723.png)
refactored
![image](https://user-images.githubusercontent.com/100230706/156905499-4086400b-3251-4d1d-97db-6af8170dea1d.png)


# Summary: In a summary statement, address the following questions.
## What are the advantages or disadvantages of refactoring code?
### Advantages
-Chances of Enhancement are high
If modules have chances to add new features or functionalities then make sure design and current code is good and following Open Close Principle
-Code Smell is Detected
Sometimes bad patterns like tight coupling, duplicate code, long methods, large classes, etc. are detected in the code;  the code should be refactored in this case.
-Bug Fixing
Codes are written badly in some cases, and so many bugs are raised. In this case, fixing of bugs take too much effort. So, the root cause of bugs can be code smell. So, before fixing bugs code should be refactored.
-Peer Review
Peer review is an important part of code refactoring. If the peer-reviewer finds some code smell then code should be refactored during peer review.
### Disadvantages
-Delivery Deadline is near and new development is planned.
-The cost of refactoring is higher than rewriting the code from scratch.
-Don't refactor the code if you don't have the time to test the refactored code before release. It can introduce bugs. 
-Don't do delayed refactoring because it contains a big mess and makes it very difficult to refactor. Do early refactoring.
-Stable code should not be refactored.
from(https://www.quora.com/What-are-the-pros-and-cons-of-refactoring)
## How do these pros and cons apply to refactoring the original VBA script?
Refactoring improves the Design of Existing Code - Martin Fowler.
In Traditional Engineering, design puts 15% of total effort but design puts 90% effort into Software Engineering.
Design helps to make the code good and maintainable.
Design makes code easily understandable because code is loosely coupled, restructured, and duplicate code is eliminated.
from(https://www.c-sharpcorner.com/article/pros-and-cons-of-code-refactoring/)

