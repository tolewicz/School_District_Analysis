# School_District_Analysis

## Project Overview
Conducting statistical analysis on school performance in the district
Investigate performance dependence based on budget, and size of the school

## Resources
-	Data source: schools_complete.csv , students_complete.csv
-	Software: Python 3.7.6, Visual studio code
- PyCitySchools_Challenge.ipynb program 

## Challenge overview
After initial analysis, there was request change of the supply data due to suspect of misconduct of the group of students.
The grades of the 9th graders from one Thomas Highschool were set to "nan"

Redo the analysis is based on data with "nan" correction
Assessed impact of removing 423 students from the analysis

## Results report 
Thomas High School was ranked a 2nd high school in the district before revealing misconduct. Replacing grades of 9th grades from Thomas High School will have impact on performance of the whole district and school itself. 

Details of the impact are as follows: 
* District performance impact: 
  *	Removing Thomas High School slightly lowers the performance of the whole district regarding the passing percentage
  *	Percentage of student passing math, reading and both exams is lower by 1%
  * Total number of students passing both exams decreased from 25,528 to 25,105

(Table 1)

![](/Resources/Images/Table1.PNG =250x250)

* The school summary impact:
  * Correction will lower Average Math Score, Average Reading Score, Percentage Passing Math, Percentage Passing Reading, and Overall Passing, (results in the table)
  * Total Budget and per student budget will not be affected

(Table 2)

![](/Resources/Images/Table%202.PNG)

* Thomas High School’s performance, relative to the other schools impact:
  *	Thomas fall in the following ranks: 
  * Overall passing percentage rank from 2nd to 8th position in 
  * Reading passing percentage rank from 1st to 15th position
  * Math passing rank percentage rank from 7th to 9th position

(Table 3)

![](/Resources/Images/Table%203.PNG)

* Math and Reading Scores by Grade
  *	Replacing the 9th grade scores will not affect scores of 10th, 11th and 11th grades.
  *	9th graders from Thomas High School’s will be in the bottom the student rankings
* Scores by School Spending will not be affected by correction 
*	Scores by School Size, and Scores by School Type 
  *	By school type Thomas Highschool will move from 2nd position to 6th
  *	By school size from 2nd to 5th in overall passing percentage




