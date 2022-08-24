# School_District_AnalysisDeliverable 3: A Written Report for the School District Analysis (25 points)
Instructions:
For this part of the Challenge, write a report that summarizes your updated analysis and compares it with the results from the module.

## Overview of the school district analysis:
A school district asked for a snapshot of several key metrics by each school campus and by the district level. The main analysis focused on the performance of math and reading scores disaggregated several ways in preparation for a board meeting. However, after the school board reviewed the data, it was determined that the data from Thomas High School's 9th grade class was suspect of cheating. The school board asked for the data to be removed and analyzed again for a comparison.

(2.) Results: Using bulleted lists and images of DataFrames as support, address the following questions.

How is the district summary affected?

The testing data of 461 9th graders at Thomas High School was turned into null data, which recalculated the percentages of passing math, passing reading, and the overall passing. The total count of students did not change as that was run on the count of the student ids, which was not turned into null data.


![School Summary
](https://github.com/Adpetfem83/School_District_Analysis/blob/main/Screen%20Shot%202022-08-23%20at%207.49.57%20PM.png?raw=true)


How is the school summary affected?
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
