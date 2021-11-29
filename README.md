# School_District_Analysis
School District Analysis Repository Model 4

Deliverable 3 Instructions
For this part of the Challenge, write a report that summarizes your updated analysis and compares it with the results from the module.

The analysis should contain the following:

## Overview of the school district analysis:

The school board had notified Maria (the client) and her supervisor that the students_complete.csv data file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has requesgted to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once we have replaced the math and reading scores, Maria would like to repeat the school district analysis that we did and write up a report to describe how these changes affected the overall analysis. 

Results: Using bulleted lists and images of DataFrames as support, address the following questions.

##3 Affect on district summary -

District Summary Pre-Code refactoring - 

![District Summary Pre-code refactoring](https://github.com/ishan9220/School_District_Analysis/blob/main/Pre-Summary.png)


District Summary Post-Code refacroting - 

![](https://github.com/ishan9220/School_District_Analysis/blob/main/Post%20District_Summary.png)

As we can see the average Math score has decreased by 0.1, 
the % passing Math has dropped by 0.1, 
the % passing reading has dropped by 0.3 and 
the % Overall students passing has dropped by 0.1. 

### Affect on School Summary - 

School Summary Pre-Code refactoring - 

![](https://github.com/ishan9220/School_District_Analysis/blob/main/Pre%20Summary%20by%20Schools%20(final).png)

School Summary Post-Code refactoring - 

![](https://github.com/ishan9220/School_District_Analysis/blob/main/Post%20School%20Summary.png)

As we can see the average math score decreased by 0.1 ,
 % math score decreased by 0.1 , 
% reading score decreased by 0.1 and 
% overall passing score decreased by 0.3. 

### Thomas High School Performance Relative to other Schools and affect on  9th Grade Data

Replacing the ninth graders’ math and reading scores for Thomas High School has made very small changes to their overall performance as compared to other schools. 
The major change is a NAN value for Grade 9 Students in Thomas High School due to irregularities in their final testing. 

![](https://github.com/ishan9220/School_District_Analysis/blob/main/Pre%20Math%20Scores%20by%20Grade.png)

![](https://github.com/ishan9220/School_District_Analysis/blob/main/Post%20change%20Math%20Scores%20by%20Grade.png)


### Scores by school spending -

Pre Code Refactoring 

![](https://github.com/ishan9220/School_District_Analysis/blob/main/Pre%20Spending%20Summary.png)

Post Code Refactoring 

![](https://github.com/ishan9220/School_District_Analysis/blob/main/Post%20Spending%20Summary.png)


### Scores by school size - 

Pre Code ReFactoring 

![](https://github.com/ishan9220/School_District_Analysis/blob/main/Pre%20School%20Size%20Summary.png)


Post Code ReFactoring 

![](https://github.com/ishan9220/School_District_Analysis/blob/main/Post%20School%20Size%20Summary.png)

The changes are ver minor and have only affected Medium School Sizes. We only see an increase with average reading score after refactoring the code with the rest all showing a decrease under 0.1 percentile. 


### Scores by school type - 

Pre Code Refactoring 

![](https://github.com/ishan9220/School_District_Analysis/blob/main/Pre%20Scores%20by%20School%20Type.png)

Post Code Refactoring 

![](https://github.com/ishan9220/School_District_Analysis/blob/main/Post%20School%20Type.png)

The changes are ver minor and only affected Charter School Types. We only see a slight increase with average reading score after refactoring the code with the rest all showing a decrease under 0.1 percentile. 


## Statement 

The changes have made very minor decreases to the overall scores of Thomas High School between 0.1 and 0.3 percentage points. 

