# School District Analysis

## Overview of Project
### Purpose
The purpose of this project is to use Python and Jupyter Notebook to explore and clean various student data information in order to generate a school district summary for analysis. The challenge will deal with the issue of replacing certain data points and recreating the school district summary based on the results. 

## Results
In the analysis, a new school district summary was created. 
Based on this new analysis, all seven school district metrics were affected:
- District Summary: The average math score decreased
- School Summary: Thomas High School total school budget decreased, average reading and math scores slightly change, and the passing percentages slightly changed.
- Top 5 Performing Schools: No change
- Bottom 5 Performing schools:No change
- The average math score for each grade level from each school: Thomas High School 9th graders do not recieve an average math score calculation
- The average reading score for each grade level from each school: Thomas High School 9th graders do not recieve an average math score calculation
- The scores by school spending per student, by school size, and by school type: No change

Therefore, the district summary and school summary were affected, however Tomas High School's performance did not change relative to other schools, and the 9th grade scores do not affect the math and reading scores by grade, school spending, school size, or school type other than their own scores, which were replaced with NaN's.

## Summary
Based on the results above, changing the school district summary affected the total average math score for the district, decreased the total school budget for Thomas High School, slightly changed the average reading and math scores and percentages, and removed the Thomas High School from the average math and reading scores for the 9th grade level. 