# School_District_Analysis
## Overview of the school district analysis: Explain the purpose of this analysis.
The main purpose of this analysis is the comparison. Maria was being told that suspiciously the grades of the 9th grade at Thomas High School have been potentially altered. We´ve been told to remove all the "NaN" grades from this grades at THS and do the summary all over again. Finally, we will compare how these changes affected the previous analysis.

## Results

### How is the district summary affected?
In order to answer this questions we have to compare and analyze both DataFrames of the work.  
**Before Clean Up**  
![Before district summary](https://github.com/ManuelRuizF/School_District_Analysis/blob/main/resources/DistrictSum_before.PNG)  
**After Clean Up**
![After district summary](https://github.com/ManuelRuizF/School_District_Analysis/blob/main/resources/DistrictSum_After.PNG)  
As we can see, the district was barely or null affected by these changes.
### How is the school summary affected?  
For this analysis we will talk about the 5 top schools according to their overall passing percentage. We are not going to talk about the bottom ones since in the top 5 is the THS, which we are interested about.  
**Before Clean Up**   
![School_Sum](https://github.com/ManuelRuizF/School_District_Analysis/blob/main/resources/SchoolSum_Before.PNG)  
**After Clean Up**  
![SchoolSum_After](https://github.com/ManuelRuizF/School_District_Analysis/blob/main/resources/SchoolSum_After.PNG)  
Small, but there´s actually a change in the performance of the overall passing rate at THS. It´s actually so small that doesn´t really affect our general analysis. Their performance drop **0.29%** after cleaning the data.  


### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?  
It barely affected it. It did drop but not enough to be a big change in our analysis.  
## How does replacing the ninth-grade scores affect the following:  
### Math and reading scores by grade  
**Before**  
![grades_before](https://github.com/ManuelRuizF/School_District_Analysis/blob/main/resources/Before_grades.PNG)  
**After**  
![grades_after](https://github.com/ManuelRuizF/School_District_Analysis/blob/main/resources/After_grades.PNG)  

It didn´t affect other schools at all.  

### Scores by school spending
**Before** 
![spendingbefore](https://github.com/ManuelRuizF/School_District_Analysis/blob/main/resources/spendingbefore.PNG)
**After**  
![spendingafter](https://github.com/ManuelRuizF/School_District_Analysis/blob/main/resources/spendingafter.PNG)  

There were barely changes.  

### Scores by school size  
**Before**  
![sizebefore](https://github.com/ManuelRuizF/School_District_Analysis/blob/main/resources/schoolsizebefore.PNG)
**After**  
![sizeafter](https://github.com/ManuelRuizF/School_District_Analysis/blob/main/resources/schoolsizeafter.PNG)  
There were no changes at all.   

### Scores by school type  
**Before**  
![typebefore](https://github.com/ManuelRuizF/School_District_Analysis/blob/main/resources/schooltypebefore.PNG)
**After**  
![typeafter](https://github.com/ManuelRuizF/School_District_Analysis/blob/main/resources/schooltypeafter.PNG)  

There were no changes at all.
## Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.  
The general conclusion for this work and in general wih any work with this type of modification is that when you work with big data and you change a little most of times it wont represent a change in the results. For this case we move certain grades from a certain school grade from a certain school in our big data. So, to wrap it up these little changes didn´t affect our analysis at all. If we go through just the THS data we will find out that there was changes in fact, but those changes we are little. Creating NaN values for some student´s grades just increased a little their passing percentage. This change was so little so there´s a few reasons to belive there was dishonesty at this school. 
