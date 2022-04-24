# PyCity School District Analysis

# Overview and Purpose
The PyCity School district requested an analysis of recent testing data to look at performance trends and patterns. These inform decisions at the school and district level. This analysis investigated student funding and test scores in the area of reading and mathematics for grades 9-12. Due to evidence of academic dishonesty for 9th graders at Thomas High School, the school board requested a review of the data. This included replacing scores for Thomas High School with Nans, while keeping the remaining data, and reporting how this change impacted the overall analysis. 

# Results
The original analysis included a variety of data as scene below:

## District Summary ##
<p align="center">
<img src="https://github.com/teachjanderson/School_District_Analysis/blob/main/images/A_District%20Summary.png" />
  
This analysis included 39,170 students in the PyCity School District. The School Board requested the values of tests for 9th graders at Thomas High School be made NaN to determine more accurate results of the overall data. Thomas High School includes 1,635 students and of those 461 are 9th graders. The impact of not including these scores can be seen below:

<p align="center">
<img src="https://github.com/teachjanderson/School_District_Analysis/blob/main/images/B_DistrictSummary.png" />

In comparing the two outputs, the removal of 461 students did not have a major impact on overall scores. When rounding to the nearest whole, the data remains intact relatively the same. Therefore, the conclusion is made the scores of 9th graders at Thomas High School does not have a significant impact on the overall scores of the district in this dataset. 
  
## School Summary ##
Adjusting the scores of the 9th graders has an impact on the overall performance of Thomas High School. In the initial analysis, as seen below, the overall scores of Thomas High School were quite high comparative to other schools. 
  
<p align="center">
<img src="https://github.com/teachjanderson/School_District_Analysis/blob/main/images/C_PerSchool.png" />
  
Once adjusted without the 9th grade scores had a dramatic change on the overall scores for Thomas High school. 
<p align="center">
<img src="https://github.com/teachjanderson/School_District_Analysis/blob/main/images/A_PerSchool.png" />
  
How is the school summary affected?
How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
How does replacing the ninth-grade scores affect the following:
Math and reading scores by grade
Scores by school spending
Scores by school size
Scores by school type
Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

Results: There is a bulleted list that addresses how each of the seven school district metrics was affected by the changes in the data (10 pt).
Summary: There is a statement summarizing four changes to the school district analysis after reading and math scores have been replaced (5 pt).
