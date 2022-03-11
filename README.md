# School District Analysis

## Overview of the School District Analysis
School district csv files, containing data of student grades and school size and budget (/Resources/), were cleaned and analyzed in jupyter notebook, using python with pandas to organize and sort data in PyCitySchools.ipynb file. The average math and reading scores, average students passing math and reading percentage, and average students passing both math and reading percentages were extracted and organized according to following subgoups:
1. The Entire School District
2. For Each School within School Distrcit
3. For Each Grade within Each School
4. Based on Budget per Student
5. Based on School Size
6. Based on School Type 

Upon reviewing the data, the school board noted inconsistencies and suspect academic dishonesty within the entire 9th grade of Thomas High School. Their scores were removed from the dataset, and the scores were re-analyzed, organized by subgroups, and compared to the original results.

### Purpose
The purpose of the initial analysis (PyCitySchools.ipynb), was to organize school district scores and observe correlations between schools, student grade, school budget, school size, and school type. A second analysis was performed (PyCitySchools_Challenge.ipynb), to compare score results when suspected outlier is removed from data.

## Results

 - How is the district summary affected?
   -  The district summary data showed marginal effect upon the removal of 9th graders from Thomas High School's grade data. The percentages of students passing math, 74.8%, showed a 0.2% reduction from the orginal percent passing math, 75.0%. The percentages of students passing reading, 85.7%, showed a 0.1% reduction from the orginal percent passing reading, 85.8%. The percentages of students passing overall, 64.9%, showed a 0.3% reduction from the orignial percent passing overall, 65.2%. <br>
<br>

 - How is the school summary affected?
   -  In the school summary, only Thomas High School was affected due to the removal of 9th grade data from Thomas High School. The exclusion of 9th grade data lowered the passing percentages from 93.3%, 97.3%, and 90.9% to 93.2%, 97.0%, and 90.6% respectively, for math, reading, and overall. Decrease in passing percentages were observed for all subject criteria with a 0.1% decrease for math and 0.3% decrease for reading and overall. <br>
<br>

 - How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
   -  Thomas High School remains the 2nd ranked school in the school district for overall passing percentage, when 9th grade data is excluded. <br>
<br>

 - How does replacing the ninth-grade scores affect the following:
   - Math and reading scores by grade
     - The 9th grade average math and reading scores for Thomas High School now read as "nan" since the scores for each 9th grader were replaced with NaN. The remaining math and reading average for each school and grade are identical to the original. 
  <br> 
  
   - Scores by school spending
     - When summarizing scores by school spending per student, the spending range $630 - $644, containing Thomas High School data, shows 0.1% decrease in percentage of students passing reading (84.3%) and percentage of students overall passing (62.8%), when compared to the original (84.4% and 62.9% respectively). However, this becomes negligible when the data is formatted to the nearest whole percent.   
  <br> 
  
  - Scores by school size
     -  When summarizing scores by number of students, the size range, "Medium (1000 - 2000)", containing Thomas High School data, shows 0.1% decrease in percentage of students passing reading (96.7%), when compared to original (96.8%). However, this becomes negligible when the data is formatted to the nearest whole percent.
  <br> 
  
  - Scores by school type
     -  When summarizing scores by number of students, there is no noticeable difference in any scores when excluding Thomas High 9th grade data. "Charter", containing Thomas High School data, shows no difference in average scores or passing percentages, when compared to original. 

## Summary
The replacement of Thomas High School's 9th graders' scores with "Not a Number" value and excluding them from the dataset altered the results in four ways:
 1. School district passing percentages for math, reading, and overall were reduced. 
 2. Thomas High School passing percentages for math, reading, and overall were reduced. 
 3. Reading and overall passing percentages for schools with a budget between $630 and $644 per student, were reduced. 
 4. Reading passing percentages for medium schools (1000 - 2000 students) were reduced.

While the changes are negligible when rounding to the nearest whole percent, the removal of data from a selected school's entire grade, showed a consistent reduction in the passing percentages when compared to the orginal analysis. 

