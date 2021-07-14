# School_District_Analysis
Python panda and jupyter notebook analysis

## Overview of the school district analysis
We were given the task to analyze student grades from different high schools. For this challenge, our goal was to find and replace the incorrect math and reading scores for Thomas High School 9th graders while keeping the rest of the data integrity.

## Results
- *How is the district summary affected?*

By replacing ninth graders' scores in math and reading results, the district summary was affected with a decrease in the Average Math Score, % Passing Math, % Passing Reading and the % Overall Passing. 
- *How is the school summary affected?*

By replacing ninth graders' scores in math and reading results, the school summary was affected with a decrease in the Average Math Score, Average Reading Score, and most significatively on the percentage of Passing Math, Passing Reading and Overall Passing. 

- *How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?*

After replacing the ninth graders’ scores, Thomas High School remained on the second place of performance list “5 Top Schools”, the only changes were a decrease in the percentages of Passing Math, Passing Reading and Overall Passing.

- *How does replacing the ninth-grade scores affect the following:*

   -- Math and reading scores by grade
Overall, no changes reflected. We used the same code to analyze this with the understanding that the ninth grades were replaced by NaN = 0. 

   -- Scores by school spending
Overall, no changes reflected. The number of students stayed the same because the code only replaced the score of ninth graders for NaN = 0. 

   -- Scores by school size
Overall, no changes reflected. The number of students stayed the same because the code only replaced the score of ninth graders for NaN=0. 

   -- Scores by school type
Overall, no changes reflected. The number of students stayed the same because the code only replaced the score of ninth graders for NaN=0. 


## Summary: 
The most noticeable changes by replacing the grades of ninth graders of Thomas High School with NaN are:

  -- Percentage of Passing Math on School Summary changed from 93.272% to 66.911%.
  
  -- Percentage of Passing Reading on School Summary changed from 97.308% to 69.663%.
  
  -- Percentage of Overall Passing changed from 90.948% to 65.076%.
  
  -- The district summary stayed the same on Total Students and Total Schools and even though the Average Reading Score did not show any changes, the percentage of Passing reading changed from 86% to 85.7%. 

End

