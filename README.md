# School District Analysis

The purpose of this analysis is to look into all of the schools in a particular district and understand the relationships in math and reading testing scores to school funding, school size, and school type.

## District Summary

Our district summary only changes in terms of student count, with very minimal changes in the percentage categories of .1% to .3%

![](Resources/post_district_summary.png)

## School Summary

Prior to running the our output and removing the 9th grade test scores, the school summary remains the same.  However, after we remove the 9th graders we experience a dip in all percentage categories.  Since we removed the scores from 9th grade we need to re-calculate the scores based on grades 10 through 12.  This adjustment results in a pre-existing summary that we saw prior to the removal of the 9th grade scores.  

*Post Analysis School Summary

![](Resources/post_school_summary.png)

## Affect on Thomas High School

Ultimately Thomas High School was not affected in terms of its performance in relation to other schools.  Prior to removing the 9th grade test scores Thomas High School was still in 5 way tie for 1st place at 91% overall passing.  However, if you take into consideration the hundreths decimal place, Thomas High School ranks as the second best school in the district.

![](Resources/top_schools.png)

## How Replacing 9th Grade Scores Affected the Following Tables:

* **Math and Reading Scores by Grade**
  * Because the scores replaced were in one grade for one school, this did not affect the overall output of this table other than Thomas High Schools output before the edit.  The scores prior to the edit were 83.6% for math and 83.7% for reading in the 9th grade.  Post edit, Thomas High School was null for 9th grade.
* **Scores by School Spending**
  * The average test scores for for schools in the $630 to $644 range dropped off after Thomas High School had its 9th graders removed.  Furthermore, in the breakdown below you can see the drop in % for each category.  
  * % Passing Math decreased from 83% to 67%
  * % Passing reading decreased from 94% to 80%
  * % Passing Overall decreased from 72% to 53%
* **Scores by School Size**
  * There were two notable changes to the school size table.  All scores remained the same except for the % passing in all categories for schools under 1,700 students.  The scores changed from 103% passing math, 106% passing reading, and 99% passing overall to 93%, 97%, and 90% respectively.  

**After Thomas High School Edit**

![](Resources/post_school_size.png)

* **Scores by School Type**
  * Since Thomas High School is a charter school, the numbers in the passing percentages varied here as well.  
  
**After Thomas High Shcool Edit**
  
![](Resources/post_school_type.png)
