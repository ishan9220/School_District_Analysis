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

As we can see the average Math score has decreased by 0.01, the % passing Math has dropped by 0.02, the % passing reading has dropped by 0.03 and the % Overall students passing has dropped by 0.01. 

### Affect on School Summary - 

School Summary Pre-Code refactoring - 

![](https://github.com/ishan9220/School_District_Analysis/blob/main/Pre%20Summary%20by%20Schools%20(final).png)

School Summary Post-Code refactoring - 

![](https://github.com/ishan9220/School_District_Analysis/blob/main/Post%20School%20Summary.png)

As we can see the average math score decreased by 0.01 , % math score decreased by 0.01 , % reading score decreased by 0.01 and % overall passing score decreased by 0.03. 

How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

![](https://github.com/ishan9220/School_District_Analysis/blob/main/Pre%20Math%20Scores%20by%20Grade.png)

![](https://github.com/ishan9220/School_District_Analysis/blob/main/Post%20change%20Math%20Scores%20by%20Grade.png)

The major change is a NAN value for Grade 9 Students in Thomas High School due to irregularities in their final testing. 

How  has replacing the ninth-grade scores affected the data in the following areas:
Math and reading scores by grade - No changes in any of the other School's data. The only change has been for Thomas High School where there is no data for the 9th grade for Math or reading subjects. 
Scores by school spending
Scores by school size
Scores by school type
Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.


On

## Statement 

The changes have made very minor changes to the overall scores of Thomas High School between 0.1 and 0.03 percentage points. The district data has seem negligible changes which do not show up even if looking at the data up to the 2nd decimal place. 

