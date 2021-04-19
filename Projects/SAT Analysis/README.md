# An Analysis of Equal Opportunity and the SAT
By **Dustin Stewart**

**This project seeks to analyze the SAT before and after its format change in 2016-2017 and provide recommendations for Universities regarding the SAT. It will primarily focus on how different socioeconomic groups are represented in SAT results.**

[Full Report](report.ipynb)

## Summary

Through the analysis in this project, it's clear that the SAT continues to discriminate against underrepresented parts of society. Graphical and statistical analysis support the idea that over time, areas with more resources will continue to improve their test results by learning to game the test, while disadvanatged areas stay stagnant, resulting in increased disparity. Increased participation has no significant bearing on this discrepancy. Universities should begin to phase the SAT out as a requirement and eventually not consider it at all. This will result in increased applications from students who are underrepresented and inevitably, more representation from those groups.  



## [Data](data):


[**SAT 2016 Results Data**](https://www.cde.ca.gov/ds/sp/ai/)


[**SAT 2017 Results Data**](https://www.cde.ca.gov/ds/sp/ai/)


[**SAT 2018 Results Data**](https://www.cde.ca.gov/ds/sp/ai/)


[**Poverty Level Data**](https://www.census.gov/programs-surveys/saipe.html)



### Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|**district**|*object*|CA SAT data 2016/2017/2018|A collection of schools within a certain geographic region|
|**number of students**|*integer*|CA SAT data 2016|12th grade enrollment| 
|**% met benchmark**|*float*|CA SAT data 2016/2017/2018|The percentage of students who met the performance benchmark|
|**combined average**|*integer*|CA SAT data 2016|The combined total of math and reading scores for 2016| 
|**participation rate**|*float*|CA SAT data 2016/2017/2018|The percentage of 12th graders who took the SAT|
|**poverty level**|*float*|CA SAT data 2016|Percentage of students aged 5-17 in poverty| 

### Other Resources Used:
https://www.washingtonpost.com/education/2019/03/19/is-it-finally-time-get-rid-sat-act-college-admissions-tests/
https://www.washingtonpost.com/education/2019/10/18/record-number-colleges-drop-satact-admissions-requirement-amid-growing-disenchantment-with-standardized-tests/
https://www.universityofcalifornia.edu/press-room/all-time-record-high-number-applicants-apply-uc-chicanolatino-students-comprising-largest#:~:text=In%20a%20nod%20to%20successful,by%2031%2C601%2C%20or%2018.4%20percent.
