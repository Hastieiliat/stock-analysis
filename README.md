## stock-analysis
Module2
### 1. Overview of Project: Explain the purpose of this analysis.
Steve wants to find the total daily volume and yearly return for each stock. Daily volume is the total number of shares traded throughout the day; it measures how actively a stock is traded. The yearly return is the percentage difference in price from the beginning of the year to the end of the year. Steve's parents are starting to pester him about 12 stock.
### 2. Results: Using images and examples of your code, compare the stock performance between 2017 and 2018, as well as the execution times of the original script and the refactored script.

### Refactored
These two pictures are from refactored run which shows it needs less time to finish the run.
## 2017
![VBA_Challenge_2017_Refactored](https://user-images.githubusercontent.com/100230706/156911127-67ed7802-01f1-49b8-b8df-0935bb426724.png)
## 2018
![VBA_Challenge_2018_Refactored](https://user-images.githubusercontent.com/100230706/156911133-0c0ff6dd-6570-47cc-921e-1ed0f62a802d.png)
### Original 
The run time is more and since they are three individual subs ( we need to run all of them)
## 2017
![VBA_Challenge_2017_Original](https://user-images.githubusercontent.com/100230706/156911141-b3c75411-3d8b-4ef0-8fc1-67ebffbe21ae.png)
## 2018
![VBA_Challenge_2018_Original](https://user-images.githubusercontent.com/100230706/156911147-ad1688d2-bdea-4746-8f4b-33d3d54fdd29.png)

### Here is the refactored code 
[refactored code for stock analysis.txt](https://github.com/Hastieiliat/stock-analysis/files/8192037/refactored.code.for.stock.analysis.txt)
![image](https://user-images.githubusercontent.com/100230706/156911473-2249c51b-955b-464a-864e-fe30136c408a.png)
![image](https://user-images.githubusercontent.com/100230706/156911502-2b4213cf-f7b4-44c1-b02c-9b8d7b46845d.png)
![image](https://user-images.githubusercontent.com/100230706/156911511-62b5f612-f5cc-4853-9151-49cd7135b46e.png)


### 3. Summary: In a summary statement, address the following questions.
#### 1.What are the advantages or disadvantages of refactoring code?
#### Advantages
-Chances of Enhancement are high
If modules have chances to add new features or functionalities then make sure design and current code is good and following Open Close Principle
-Code Smell is Detected
Sometimes bad patterns like tight coupling, duplicate code, long methods, large classes, etc. are detected in the code;  the code should be refactored in this case.
-Bug Fixing
Codes are written badly in some cases, and so many bugs are raised. In this case, fixing of bugs take too much effort. So, the root cause of bugs can be code smell. So, before fixing bugs code should be refactored.
-Peer Review
Peer review is an important part of code refactoring. If the peer-reviewer finds some code smell then code should be refactored during peer review.
#### Disadvantages
-Delivery Deadline is near and new development is planned.
-The cost of refactoring is higher than rewriting the code from scratch.
-Don't refactor the code if you don't have the time to test the refactored code before release. It can introduce bugs. 
-Don't do delayed refactoring because it contains a big mess and makes it very difficult to refactor. Do early refactoring.
-Stable code should not be refactored.
from(https://www.quora.com/What-are-the-pros-and-cons-of-refactoring)
### 2. How do these pros and cons apply to refactoring the original VBA script?
Refactoring improves the Design of Existing Code - Martin Fowler.
In Traditional Engineering, design puts 15% of total effort but design puts 90% effort into Software Engineering.
Design helps to make the code good and maintainable.
Design makes code easily understandable because code is loosely coupled, restructured, and duplicate code is eliminated.
from(https://www.c-sharpcorner.com/article/pros-and-cons-of-code-refactoring/)

