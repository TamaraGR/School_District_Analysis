# School_District_Analysis

## Summary 
In this repository you can see a comparative analysis of the School district academic performance indicators in math and reading. The analysis at first looks at all schools and grades for high schools across the disctirct. At a later note we were informed that grades for Thomas High for math and reading for the ninth grades might have been compromised, and therefore we are asked to remove those grades and replace them with NaN. Afterwards we are performing the analysis across all indicators again, but this time without the Thomas High ninth graders. And here in this written analysis we are comparing the initial analysis with the second one. The removal of Thomas High ninth graders has impacted the ratings and percentages for that partocular school, but hasn't affected the district level analysis as much. The image below depics a brief overview of schools that we will be looking into. 

![overall](https://github.com/TamaraGR/School_District_Analysis/blob/main/overall.jpg)

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

Compared to the initial district summary, the one performed after removing Thomas High's ninth graders changed in the following way: 

- [x] Average math scores dropped from 79% to 78.9%. 
- [x] Average reading scores remained the same. 
- [x] Passing math percent dropped from 75% to 74.8%.
- [x] Passing reading percent dropped from 86% to 85.7%.
- [x] Overall passing percent dropped from 65% to 64.9%.

### How is the school summary affected?

Other schools' summaries weren't affected, and the summary of the grade levels wasn't affected either, therefore we are focusing on Thomas High. Thomas High's summary was affected, as you can see from the images below. 

*Thomas High Summary before removing the ninth graders*

![THS_before](https://github.com/TamaraGR/School_District_Analysis/blob/main/THS_before.jpg)

*Thomas High Summary after removing the ninth graders*

![THS_after](https://github.com/TamaraGR/School_District_Analysis/blob/main/THS_after.jpg)

As you can see from the images, after removing the 9th graders, the average math score at Thomas High has dropped from 83.418349% to 83.350937%; the average reading score went from 83.848930% to 83.896082. These are very insignificant changes. However, when you look at the more complicated calculations, such as the ones of the percentages, the changes are more drastic: the percentage of passing math dropped from 93.272171% to 66.911315%, the percentage of passing reading from 97.308869% to 69.663609% and the overall passage percentage from 90.948012% to 65.076453%. 

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Thomas High School's performance in comparison to other schools doesn't change much because of replacing ninth graders' grades with NaN when it comes to the grade by grade performance. The only change that occures is related to the ninth graders' grades being removed and replaced with NaN. However, if we measure by the percentages of passing math, reading and, most, importantly, the overall passing percentage, Thomas High in the beginning ranks as number two school in the dictrict because its overall passing score is above 90%, and after the removal of the ninth graders' grades, this school's overall passing drops significantly, and so does its rating. Please refer to the images of the top schools before and after below. 

*Top Schools Before Ninth Graders Removal*

![top1](https://github.com/TamaraGR/School_District_Analysis/blob/main/top1.jpg)

*Top Schools After Ninth Graders Removal*

![top2](https://github.com/TamaraGR/School_District_Analysis/blob/main/top2.jpg)

However, it must be noted, that if we remove the ninth graders at Thomas High completely, this school's ratings will not drop so drastically, and we would still see Thomas High in the top five schools of the district. Therefore, it is up to the board how to decide regarding the school's performance. 

### How does replacing the ninth-grade scores affect the following:
- [ ] Math and reading scores by grade

As mentioned earleir, the replacing of the ninth grade scores doesn't affect the math and reading scores by grade. The only change that happens is that the Thomas High ninth grade scores show as NaN. 

- [ ] Scores by school spending

Below is an image that shows all the schools of the district and where they are in terms of the spending bins, including Thomas High. 

![ths_spending](https://github.com/TamaraGR/School_District_Analysis/blob/main/ths_spending.jpg)

And if you look at the screenshots below, you will notice that the changes are minimal for Thomas High after the correction. 

*Spending Bins Before the Correction*

![before_correction](https://github.com/TamaraGR/School_District_Analysis/blob/main/before_correction.jpg)

*Spending Bins After the Correction*

![after_correction](https://github.com/TamaraGR/School_District_Analysis/blob/main/before_correction.jpg)

- [ ] *Scores by school size*

Thomas High School is a medium-size school, so we are looking at the changes that happened to the medium-size schools. The changes are minimail, please refer to the images below. 

*Before the Change*

![size1](https://github.com/TamaraGR/School_District_Analysis/blob/main/size1.jpg)

*After the Change*

![size2](https://github.com/TamaraGR/School_District_Analysis/blob/main/size2.jpg)

- [ ] *Scores by school type*

Thomas High School is a Charter school. The changes based on school type are minimal as well, please see the images below. 

*Before the Change*

![change1](https://github.com/TamaraGR/School_District_Analysis/blob/main/change1.jpg)

*After the Change*

![chnage2](https://github.com/TamaraGR/School_District_Analysis/blob/main/chnage2.jpg)

## Analysis Conclusion 

The analysis has shown that removing the ninth graders's scores at Thomas High with NaNs didn't result in drastic changes mostly. However, the school analysis has revealed some of the other interesting data about performance. Some of the findings about schools' performance are below: 

- [x] Schools' performace doesn't usually depend on the funding.
- [x] Schools' performance can depend on the size. Smaller schools tend to perform better. 
- [x] Charter schools perform better. 
