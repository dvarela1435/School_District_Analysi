# School_District_Analysis

## Overview of the school district analysis:
There were some concerns of academic dishonesty; specifically, reading and math scores for Thomas High Shool ninth grade. Since the school board does not know the full extent of the dishonesty, we were asked to remove the grades of the concern grade and high school and replace it with null values.



## Impact on district summary:

Very Minimal

* Average Math Score    --> dropped from 79 to 78.9 a difference of -.10
* Average Reading Score --> no changes
* % Passing Math 	--> dropped from 75 to 74.8 a difference of -.20
* % passing reading	--> dropped from 86 to 85.7 a difference of -.30
* % overall passing	--> dropped from 65 to 64.9 a difference of -.10

![Old_district_summary](/Resources/z01_district_summary.png)
![New_district_summary](/Resources/01-district_summary.png)


## Impact on school summary:

Very Minimal

* Average Math Score 	dropped from 83.42 to 83.35 a difference of -.067
* Average Reading Score 	improved from 83.85 to 83.90 a differnce of +.047
* % Passing Math		dropped from a 93.27%  to 93.19% a difference of -.086
* % passing reading	Dropped from a 97.31%  to 97.02% a difference of -.290
* % overall passing	dropped from a 90.95%  to 90.63% a difference of  -0.318

![Old_school_summary](/Resources/z02-per_school_summary.png)
![New_school_summary](/Resources/03_per_school_summary_adj.png)

## Thomas High School’s performance relative to the other schools:
  
When replacing the school the ninth grades with a null value, puts Thomas High School's performances in line with the other schools. It will still make Thomas High School the second highest with overall passing percentages.

![Top_5_Schools](/Resources/04_top_5_schools.png)

## Impact on other summaries:

The following made such a small difference, when getting the average did not change enough to impact the rounding. 
* Math and reading scores by grade
* Scores by school spending - no change

![Spending Summary](/Resources/08_scores_by_school_spending.png)
* Scores by school size - no change

![School_Size](/Resources/09_scores_by_school_size.png)
* Scores by school type - no change

![Schoo_Type](/Resources/10_Scores_by_school_type.png)


## Summary: 

Dropping the ninth graders from the average did not impact as much as expected. The average was only including those who actually scored. 461 students scores were not counted, which reduced the amount of students that could have been counted. Removing them improved the mean of the scores

Of the 5 different areas of the summary was impacted by the replacing the ninth grades scores
* Average Math Score
* % Passing Math
* % passing reading
* % overall passing
    
No changes were made to the Average Reading Score
