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


## Results

 - How is the district summary affected?
   -  The district summary data showed marginal effect upon the removal of 9th graders from Thomas High School's grade data. The percentages of students passing math and overall decreased by 0.2%, and the percentages of students passing reading decreased by 0.1%. <br>
<br> - How is the school summary affected?
   -  In the school summary, only Thomas High School was affected due to the removal of 9th grade data from Thomas High School. The passing percentages for Thomas High decreased observably. Excluding the 9th graders data, the percentage passing rates were 66.9%, 69.7%, and 65.1% respectively for math, reading, and overall. In the original school summary dataset that includes the scores from 9th graders, Thomas High School showed passing percentages of 93.3%, 97.3%, and 90.9%, respectively for math, reading, and overall. <br>
<br> - How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
   -  Thomas High School overall passing percentages ranked number 2 in the school district, with the inclusion of ninth graders data. Excluding the 9th graders data, Thomas High School ranks number 8 out of the 15 schools in the district for overall passing percentages. <br>
<br> - How does replacing the ninth-grade scores affect the following:
   - Math and reading scores by grade
     -  <br>
  <br> - Scores by school spending
     -  <br>
  <br> - Scores by school size
     -  <br>
  <br> - Scores by school type
     -  <br>

## Summary
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs
