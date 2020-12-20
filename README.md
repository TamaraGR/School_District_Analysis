# School_District_Analysis

## Summary 
In this repository you can see a comparative analysis of the School district academic performance indicators in math and reading. The analysis at first looks at all schools and grades for high schools across the disctirct. At a later note we were informed that grades for Thomas High for math and reading for the ninth grades might have been compromised, and therefore we are asked to remove those grades and replace them with NaN. Afterwards we are performing the analysis across all indicators again, but this time without the Thomas High ninth graders. And here in this written analysis we are comparing the initial analysis with the second one. The removal of Thomas High nineth graders has impacted the ratings and percentages for that partocular school, but hasn't affected the district level analysis as much. 

## Resources 

- [x] This analysis is referencing two ipynb files: ![PyCitySchools](https://github.com/TamaraGR/School_District_Analysis/blob/main/PyCitySchools.ipynb) for the initial analysis and ![PyCitySchool_Challenge](https://github.com/TamaraGR/School_District_Analysis/blob/main/PyCitySchools_Challenge.ipynb) for the removal of Thomas High ninth graders and analysis without them. 
- [x] The said two files were created based on the ![schools_complete](https://github.com/TamaraGR/School_District_Analysis/blob/main/Resources/schools_complete.csv) and ![students_complete](https://github.com/TamaraGR/School_District_Analysis/blob/main/Resources/students_complete.csv). 
- [x] The code was written and debugged in Jupyter Notebook with the help of Panda and Numpy dependencies (to augment Python analysis). 

## Analysis 

### How is the district summary affected?

The district summary wasn't affected as much, because there are many schools and many students. Please refer to the images below. 

*Initial School District Summary*
![District_Initial](https://github.com/TamaraGR/School_District_Analysis/blob/main/District_Initial.jpg)

*District Summary after Removing 9th Graders at Thomas High*
![District_Second](https://github.com/TamaraGR/School_District_Analysis/blob/main/Distrcit_Second.jpg)

Compared to the initial district summary, the one performed after removing Thomas High's nineth graders changed in the following way: 

- [x] Average math scores dropped from 79% to 78.9%. 
- [x] Average reading scores remained the same. 
- [x] Passing math percent dropped from 75% to 74.8%.
- [x] Passing reading percent dropped from 86% to 85.7%.
- [x] Overall passing percent dropped from 65% to 64.9%.

### How is the school summary affected?

Other schools' summaries weren't affected, therefore we are focusing on Thomas High here. 



- [x] How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
- [x] How does replacing the ninth-grade scores affect the following:
*Math and reading scores by grade*
*Scores by school spending*
*Scores by school size*
*Scores by school type*
