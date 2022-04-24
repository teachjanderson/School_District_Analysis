# PyCity School District Analysis

# Overview and Purpose
The PyCity School district requested an analysis of recent testing data to look at performance trends and patterns. These inform decisions at the school and district level. This analysis investigated student funding and test scores in the area of reading and mathematics for grades 9-12. Due to evidence of academic dishonesty for 9th graders at Thomas High School, the school board requested a review of the data. This included replacing scores for Thomas High School with Nans, while keeping the remaining data, and reporting how this change impacted the overall analysis. 

# Results
The original analysis included the total students, budget, average scores, and percent passing for an overall passing score:

## District Summary ##
<p align="center">
<img src="https://github.com/teachjanderson/School_District_Analysis/blob/main/images/A_District%20Summary.png" />
  
This analysis included 39,170 students in the PyCity School District. The School Board requested the values of tests for 9th graders at Thomas High School be made NaN to determine more accurate results of the overall data. Thomas High School includes 1,635 students, and 461 of those are 9th graders. The impact of not including these scores can be seen below:

<p align="center">
<img src="https://github.com/teachjanderson/School_District_Analysis/blob/main/images/B_DistrictSummary.png" />

In comparing the two outputs, the removal of 461 students did not have a major impact on overall scores. When rounding to the nearest whole, the data remains relatively the same. Therefore, the conclusion is made the scores of 9th graders at Thomas High School does not significantly impact the overall scores of the district.
  
## School Summary ##
The 9th graders at Thomas High School each had math and reading scores replaced with NaN. Adjusting the scores of the 9th graders impacts the overall performance of Thomas High School. In the initial analysis, as seen below, the overall scores of Thomas High School place them as the second best performing school with an overall passing score of 90.9%
  
<p align="center">
<img src="https://github.com/teachjanderson/School_District_Analysis/blob/main/images/A_Adjust_PerSchool.png" />
  
Once adjusted, the change in the 9th grade scores had a dramatic change on the overall scores for Thomas High school with an overall passing score of 65%. 

<p align="center">
<img src="https://github.com/teachjanderson/School_District_Analysis/blob/main/images/A_PerSchool.png" />
  
To obtain a more accurate representation of passing scores at Thomas High School, the numbers were reconfigured to just include the scores of students in 10th-12th grade. Recalculating using the 10th-12th grade scores returns Thomas High School closer to it's initial set of scores and makes minimal impact on the overall scores of the district. This is in large part to the small set of data (461 students) out of the nearly 40,000 students overall. In relation to other shcools, replacing the 9th grade scores puts Thomas High School in a more competitive range with scores being very high in the district. More on this subset of data is below. 
  
  <p align="center">
<img src="https://github.com/teachjanderson/School_District_Analysis/blob/main/Adjust_PerSchool.png" />
  
## Adjustments and Scores by Type ##

**Scores by Grade Level**
    
After adjustment for the ninth grade scores and replacement with NaN, the overall caclulations by school and grade can be seen below. Thomas High Schools falls similar in range (~75%-85%) to the other schools when analyzed by grade level percentages in math and reading. 
  
<p align="center">
<img src="https://github.com/teachjanderson/School_District_Analysis/blob/main/images/Screen%20Shot%202022-04-23%20at%2010.02.51%20PM.png" width="600" />

**Scores by School Spending**
  
Based on school spending, a pattern does emerge that a certain spending amounts could correlate with higher scores. Per student spending of $629 or less reveals high passing percentages. This could prove worth greater analysis. However, making adjustments for the scores of the 9th graders had no impact on the metrics in the charts below. This is potentially due to the small sample size (461) compared to the overall student population (nearly 40,000). 
  
<p align="center">
<img src="https://github.com/teachjanderson/School_District_Analysis/blob/main/images/Money.png" />
    
**Scores by School Size and Type**
  
Similar to school spending, the size and type of the school shows differences in student test performance as illusrated in the outputs below. The smaller to medium schools (Less than 2000) outperformed those with larger attendance (2000 or greater) in all metrics. Character schools also outperformed the district scores. These areas merit further review. 
  
<p align="center">
<img src="https://github.com/teachjanderson/School_District_Analysis/blob/main/images/Size.png" />

<p align="center">
<img src="https://github.com/teachjanderson/School_District_Analysis/blob/main/images/Charter:Public.png" />
      
## Closing Summary ##
  
Four take aways are worth noting in the final, adjusted analysis. 
  1 First, this set of data will now show NaN for all 9th grade scores at Thomas High School. 
  2 Second, the overall passing rate for Thomas High School changed dramtically once the 9th grade scores were removed, but evaluating them based on the 10th-12th grade students returned the schools numbers similar to before the change. Thomas High School is now ranked similar or better than many schools in the district. 
  3 Third, while Thomas High did see changes in performance, many of its metrics did not significantly change and its overall scores in math and reading (10th-12th grades) were well above the 70% threshold. 
  4 Finally, removal of the 9th grade scores at Thomas High School did not alter the overall district data to a substantial amount (less than 1% in the key indicators). This should provide confidence for the district in the overall fidelity of its data. 
