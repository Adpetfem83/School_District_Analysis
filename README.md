# School_District_AnalysisDeliverable 3: A Written Report for the School District Analysis (25 points)
Instructions:
For this part of the Challenge, write a report that summarizes your updated analysis and compares it with the results from the module.

## Overview of the school district analysis:
A school district asked for a snapshot of several key metrics by each school campus and by the district level. The main analysis focused on the performance of math and reading scores disaggregated several ways in preparation for a board meeting. However, after the school board reviewed the data, it was determined that the data from Thomas High School's 9th grade class was suspect of cheating. The school board asked for the data to be removed and analyzed again for a comparison.

(2.) Results: Using bulleted lists and images of DataFrames as support, address the following questions.

How is the district summary affected?
![
](https://github.com/Adpetfem83/School_District_Analysis/blob/main/Screen%20Shot%202022-08-24%20at%205.51.15%20AM.png)

The testing data of 461 9th graders at Thomas High School was turned into null data, which recalculated the percentages of passing math, passing reading, and the overall passing. The total count of students did not change as that was run on the count of the student ids, which was not turned into null data.

![
](https://github.com/Adpetfem83/School_District_Analysis/blob/main/Screen%20Shot%202022-08-24%20at%205.55.21%20AM.png)
When comparing the two charts, removing less than 500 test scores had a nominal impact on the almost 40,000 student data set. The change was less than a 1% difference and the numbers would still round to the same whole number.



How is the school summary affected?

In the original analysis, Thomas High School started with a 91% overall passing rate, which was a concern to the school board as being too high. After calculating the total number of 10th - 12th grade students as the new denominator, the rest of the testing data was adjusted accordingly.

Original Analysis: 
![
](https://github.com/Adpetfem83/School_District_Analysis/blob/main/Screen%20Shot%202022-08-24%20at%206.54.04%20AM.png)

Removing the 9th grade students from the data set had a huge impact by dropping from 91% to 65% for the overall passing rate.


How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?




How does replacing the ninth-grade scores affect the following:
Math and reading scores by grade
Scores by school spending
Scores by school size
Scores by school type

(3.) Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

(a). The overall passing rate for Thomas High School changed dramatically from 91% to 65%.

(b). Thomas High School's ranking dropped from 2nd to 8th in the district of 15 campuses.

(c). Data at the grade level will now show as "NaN" in reports for the 9th grade students at Thomas High School

(d). In addition to the overall passing rate, the campus math and reading averages and passing percentages all saw shifts.

The major changes will be seen at the lower views of the disaggregated data with minor impact to the larger data views.
