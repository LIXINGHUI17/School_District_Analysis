# School_District_Analysis
[PyCitySchools_Challenge](PyCitySchools_Challenge.ipynb)

## Overview of the school district analysis: Explain the purpose of this analysis.
### The purpose of this project is to find overall passing percentages of the students and see if there is any correlations with the budget per student, school size and school type. Might due to the potential academic dishonesty for grade 9 student at Thomas High School, we did second analysis through replacing NaN to those students 

## Results:

### How is the district summary affected?
#### The average math score dropped 0.1%, the average reading score stayed same. The percentage of passing math dropped 0.2%, and the percentage of passing reading dropped 0.3%. The percentage of overall passing dropped 0.1%.

#### Old District Summary
![Old_district_summary](/Resources/Old_district_summary.png)
#### New Didtrict Summary
![New_district_summary](/Resources/New_district_summary.png)

### How is the school summary affected?
#### There is no changes for other schools. Only change exist for Thomas High School as below pictures show. For average grade for math and reading, both are similar, however, for percentage of passing math and reading, there are 30% different, since we replaced the grade for grade 9 at Thomas High School. The numerator becomes smaller and the denominator remains unchanged. So the results dropped around 30%.

#### Old School Summary
![Old_School_Summary](/Resources/Old_School_Summary.png)
#### New School Summary
![New_School_Summary](/Resources/New_School_Summary.png)

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
#### There is no effects relative to the other schools.

### How does replacing the ninth-grade scores affect the following:
#### Math and reading scores by grade
##### Only Grade for Grade 9 at Thomas High School changed to NaN, as below pictures show:

##### Old Math Score
![Old_Math_Score_by_Grades](/Resources/Old_Math_Score_by_Grades.png)
##### New Math Score
![New_Math_Score_by_Grades](/Resources/New_Math_Score_by_Grades.png)
##### Old Reading Score
![Old_Reading_Score_by_Grades](/Resources/Old_Reading_Score_by_Grades.png)
##### New Reading Score
![New_Reading_Score_by_Grades](/Resources/New_Reading_Score_by_Grades.png)

#### Scores by school spending

##### Both results are same. However, we found more spending on each student, less overall passing rate.

##### Old School Spending
![Old_Spending_Summary](/Resources/Old_Spending_Summary.png)
##### New School Spending
![New_Spending_Summary](/Resources/New_Spending_Summary.png)

#### Scores by school size

##### Both results are same. However, we found large size school has the lowest overall passing rate, which more than 30% different.

##### Old School Size
![Old_School_Size_Summary](/Resources/Old_School_Size_Summary.png)
#### New School Size
![New_School_Size_Summary](/Resources/New_School_Size_Summary.png)

#### Scores by school type

##### Both results are same. However, Charter Schools have much higher overall passing rate than District Schools.

##### Old School Type
![Old_School_Type_Summary](/Resources/Old_School_Type_Summary.png)
##### New School Type
![New_School_Type_Summary](/Resources/New_School_Type_Summary.png)

## Summary: 
### After replacing the socres of the 9th grade student at Thomas High School, we found not much has changed. However, Thomas High School lost its placement as a top five school within this District when we did this second analysis.
