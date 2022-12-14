## School_District_AnalysisDeliverable 3: A Written Report for the School District Analysis (25 points)
Instructions:

# For this part of the Challenge, write a report that summarizes your updated analysis and compares it with the results from the module.

## Overview of the school district analysis:
A school district asked for a snapshot of several key metrics by each school campus and by the district level. The School District Analysis actually focused on the performance of various schools in the district area in the following subjects, math and reading in preparation for a board meeting. However, after the school board reviewed the data presented, it was noticed that the data from Thomas High School's 9th grade class was suspect of cheating. The school board asked for the data to be removed and analyzed again for a comparison.

(2.) Results: Using bulleted lists and images of DataFrames as support, address the following questions.

## How is the district summary affected?
![
](https://github.com/Adpetfem83/School_District_Analysis/blob/main/Screen%20Shot%202022-08-24%20at%205.51.15%20AM.png)

The testing data of 461 9th graders at Thomas High School was turned into null data, which recalculated the percentages of passing math, passing reading, and the overall passing. The total count of students did not change as that was run on the count of the student ids, which was not turned into null data.

![
](https://github.com/Adpetfem83/School_District_Analysis/blob/main/Screen%20Shot%202022-08-24%20at%205.55.21%20AM.png)
When comparing the two charts, removing less than 500 test scores had a nominal impact on the almost 40,000 student data set. The change was less than a 1% difference and the numbers would still round to the same whole number.




## How is the school summary affected?

In the original analysis, Thomas High School started with a 91% overall passing rate, which was a concern to the school board as being too high. After calculating the total number of 10th - 12th grade students as the new denominator, the rest of the testing data was adjusted accordingly.
 
![
](https://github.com/Adpetfem83/School_District_Analysis/blob/main/Screen%20Shot%202022-08-24%20at%206.54.04%20AM.png)






## How does replacing the ninth graders??? math and reading scores affect Thomas High School???s performance relative to the other schools?

In the original analysis, Thomas High School (THS) ranked 2nd in the district raising red flags with the school board.

Original Analysis:
![
](https://github.com/Adpetfem83/School_District_Analysis/blob/main/Screen%20Shot%202022-08-24%20at%201.46.27%20PM.png)

After adjusting the 9th grade data, Thomas High School ranked in the exact middle of 15 campuses at 8th from the bottom.

Adjusted Analysis: 
![
](https://github.com/Adpetfem83/School_District_Analysis/blob/main/Screen%20Shot%202022-08-24%20at%202.04.26%20PM.png)


## How does replacing the ninth-grade scores affect the following:
 
 The adjusted Averages using the Math and Reading Scores:
 
In the original analysis, Thomas High School (THS) had 83.6 math average and 83.7 reading average for the 9th grade tests. Now the scores have been replaced with null values and shows up in Python programming as NaN in the following charts.

Adjusted Average Math Scores------------------------------------------------------------Adjusted Average Reading Scores:
 
 ![
 ](https://github.com/Adpetfem83/School_District_Analysis/blob/main/Screen%20Shot%202022-08-24%20at%202.12.43%20PM.png)
 
# Scores by school spending
THS falls in the $630-$644/student spending range. However, the hundredths place was needed to see the nominal changes.

Original Analysis:
![
](https://github.com/Adpetfem83/School_District_Analysis/blob/main/Screen%20Shot%202022-08-24%20at%202.25.43%20PM.png)

There was very little spending impact by changing the 9th grade scores.

# Scores by school size
THS is defined as a medium sized school. The hundredths place was needed to see the nominal changes.

Original Analysis:
![
](https://github.com/Adpetfem83/School_District_Analysis/blob/main/Screen%20Shot%202022-08-24%20at%202.32.45%20PM.png)

There was very little impact by campus size due to changing the 9th grade scores.


# Scores by school type

THS is a charter school type. The hundredths place was needed to see the nominal changes.

Original Analysis:
![
](https://github.com/Adpetfem83/School_District_Analysis/blob/main/Screen%20Shot%202022-08-24%20at%202.37.20%20PM.png)

There was very little impact by school type by changing the 9th grade scores.


(3.) Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

(a). The overall passing rate for Thomas High School changed dramatically from 91% to 65%.

(b). Thomas High School's ranking dropped from 2nd to 8th in the district of 15 campuses.

(c). Data at the grade level will now show as "NaN" in reports for the 9th grade students at Thomas High School

(d). In addition to the overall passing rate, the campus math and reading averages and passing percentages all saw shifts.

The major changes will be seen at the lower views of the disaggregated data with minor impact to the larger data views.
