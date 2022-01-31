# School Distric Analysis

## Description
The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.

## Results after repeting analysis without taking Thomas High School Ninth grade into account

### School Distric Summary
![distric summary](https://github.com/IrvingHdez/school-district-analysis/blob/main/Images/1_distric_summary.PNG)

## How is the district summary affected?
Average Scores and Passing Percentages do not increase as spending per student increases.
![school spending](https://github.com/IrvingHdez/school-district-analysis/blob/main/Images/2_school_spending.PNG)

## How is the school summary affected?
It is not possible to determine the extent of the potential academic dishonesty or identify soecific indivuals to exclude from the dataset.

## How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Relacing the ninth graders' scores with NaN caused Thomas High School's overall passing percentages and average scores to plummet. The district as a whole has also had its average math and reading scores decrease, as well as the overall passing percentage for students. Furthermore, Thomas High School lost its placement as a top five school within this District. However, after updating the total student counts to exclude the Thomas High School ninth graders and omitting their scores from the dataset, Thomas High School regained its high average scores and retained its position as the number two school in the District.

## How does replacing the ninth-grade scores affect the following:

### Math and reading scores by grade
![math scores by grade](https://github.com/IrvingHdez/school-district-analysis/blob/main/Images/7_math_scores_by_grade.PNG)

![reading scores by grade](https://github.com/IrvingHdez/school-district-analysis/blob/main/Images/8_reading_scores_by_grade.PNG)

### Scores by school spending
![school scores by spending](https://github.com/IrvingHdez/school-district-analysis/blob/main/Images/2_school_spending.PNG)
### Scores by school size
![school scores by size](https://github.com/IrvingHdez/school-district-analysis/blob/main/Images/3_schools_by_size.PNG)
### Scores by school type
![school scores by type](https://github.com/IrvingHdez/school-district-analysis/blob/main/Images/4_schools_by_type.PNG)