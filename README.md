# School_District_Analysis
## Overview
The original purpose of this analysis was to provide and overview of the following metrics across multiple levels of the school district from distric level to grade:

* Total Students
* Total Schools
* Total Budget
* Test Score Averages in both Math and Reading
* Percentage of students passing Math and passing Reading
* Percentage of students passing both Math and Reading

Also we aimed at providing an analysis of test scores when under certain conditions such as spending levels, type of school, and school size along with highlights of the top and bottom perfoming schools,

However after the analysis was completed, allegations of cheating by the Thomas High School (THS) 9th graders came to light. So, the analysis has changed to also include the effect that this might have had on the school after removing the Thomas High School 9th grade test scores. 

## Results
### District Level Results
**District Summary with Removed THS Grades**
![District Summary with Removed THS Grades](https://github.com/aKnownSaltMine/School_District_Analysis/blob/main/Resources/Tables/District_Summary_Cleaned.PNG)
**District Summary including THS Grades**
![District Summary including THS Grades](https://github.com/aKnownSaltMine/School_District_Analysis/blob/main/Resources/Tables/district_summary_w_THS.PNG)

When comparing the above tables, the effects of the cheating on a district level is marginal at most. By removing the suspected test scores, the following happened:
* The average Math score decreased by 0.1%
* The average Meading score remained unchanged
* The percentage passing math decreasing by 0.2%
* The percentage passing reading decreasing by 0.1%
* The percentage passing overall descreased by 0.3%

### School Level Results
**School Level Summary with Removed THS Grades**
![School Level Summary with Removed THS Grades](https://github.com/aKnownSaltMine/School_District_Analysis/blob/main/Resources/Tables/School_Summary_Cleaned.PNG)

**School Level Summary with THS Grades Included**
![School Level Summary with THS Grades Included](https://github.com/aKnownSaltMine/School_District_Analysis/blob/main/Resources/Tables/school_summary_w_THS.PNG)

By removing the THS 9th grade scores, only the THS overall scores were changed in the following ways:
* Average Math Score decreased by 0.07%
* Average Reading Score increased by 0.05%
* The Percentage Passing Math decreased by 0.08%
* The Percentage Passing Reading decreased by 0.29%
* The Percentage Passing Overall decreased by 0.32%

- How does replacing the ninth graders??? math and reading scores affect Thomas High School???s performance relative to the other schools?
Overall these changes were not enough to bring Thomas High School's overall passing rate out of the top 5 perfoming schools, though the differences did bring it much closer to tying for third with Griffin High School as seen below.

**Top 5 Performing Schools removed THS Grades**

![Top 5 Performing Schools removed THS Grades](https://github.com/aKnownSaltMine/School_District_Analysis/blob/main/Resources/Tables/Top_5_Performing_Schools_cleaned.PNG)

**Top 5 Performing Schools including THS Grades**

![Top 5 Performing Schools including THS Grades](https://github.com/aKnownSaltMine/School_District_Analysis/blob/main/Resources/Tables/Top_5_Performing_Schools_w_THS.PNG) 


### Test Scores by Conditions Results
By replacing the Thomas High School 9th Grade test scores with null values, the overall views of the rest of the requested tables are as follows:
#### Math and reading scores by grade
##### Math
* The Thomas High School 9th grade Math average of 83.6% was dropped leaving all other schools' grade level averages alone. 

**Math Scores by Grade Cleaned**

![Math Scores by Grade Cleaned](https://github.com/aKnownSaltMine/School_District_Analysis/blob/main/Resources/Tables/math_scores_by_grade_cleaned.PNG)

**Math Scores by Grade with THS Grades**

![Math Scores by Grade with THS Grades](https://github.com/aKnownSaltMine/School_District_Analysis/blob/main/Resources/Tables/math_scores_by_grade_w_THS.PNG)

##### Reading
* The Thomas High School 9th grade Reading average of 83.7% was dropped leaving all other schools' grade level averages alone. 

**Reading Scores by Grade Cleaned**

![Reading Scores by Grade Cleaned](https://github.com/aKnownSaltMine/School_District_Analysis/blob/main/Resources/Tables/reading_scores_by_grade_cleaned.PNG)

**Reading Scores by Grade with THS Grades**

![Reading Scores by Grade with THS Grades](https://github.com/aKnownSaltMine/School_District_Analysis/blob/main/Resources/Tables/reading_scores_by_grade_w_THS.PNG)

#### Scores by school spending
* The affect on the scores by school spending was less than 0.05% and does not show after chart formatting.

**Scores by Spending Cleaned**

![Scores by Spending Cleaned](https://github.com/aKnownSaltMine/School_District_Analysis/blob/main/Resources/Tables/scores_by_spending_cleaned.PNG)

**Scores by Spending with THS Grades**

![Scores by Spending with THS Grades](https://github.com/aKnownSaltMine/School_District_Analysis/blob/main/Resources/Tables/scores_by_spending_w_THS.PNG)

#### Scores by school size
* The affect on the scores by school size was less than 0.05% and does not show after chart formatting.

**Scores by School Size Cleaned**

![Scores by School Size Cleaned](https://github.com/aKnownSaltMine/School_District_Analysis/blob/main/Resources/Tables/scores_by_school_size_cleaned.PNG)

**Scores by School Size with THS Grades**

![Scores by School Size with THS Grades](https://github.com/aKnownSaltMine/School_District_Analysis/blob/main/Resources/Tables/scores_by_school_size_w_THS.PNG)

#### Scores by school type
* The affect on the scores by school type was less than 0.05% and does not show after chart formatting.

**Scores by School Type Cleaned**

![Scores by School Type Cleaned](https://github.com/aKnownSaltMine/School_District_Analysis/blob/main/Resources/Tables/scores_by_school_type_cleaned.PNG)

**Scores by School Type with THS Grades**

![Scores by School Type with THS Grades](https://github.com/aKnownSaltMine/School_District_Analysis/blob/main/Resources/Tables/scores_by_school_type_w_THS.PNG)

## Summary
In summary, the following are the most notable changes in placing all Thomas High School 9th grade test scores:
* The Overall Passing levels decreased the most on the District Level summary, while leaving the averages largely the same. This speaks to the Thomas High School 9th graders not having excessively high grades, but *many* of them were passing overall. 
* The Thomas High School Reading passing rate actually increased, while the rest of their averages and passing rates decreased by removing the 9th grader scores.
* While the actual positions in the top 5 schools in the district did not change, the only thing that separates position number 2 with number 5 is less than 0.1% making it a lot tighter than it was before bringing out the Thomas High School 9th graders scores.
* While there was an effect on the scores for the $630-644 spending bin, medium school size bin, and the Charter school type bin, it was less than 0.05% leading it to be obscured by chart formatting. 
