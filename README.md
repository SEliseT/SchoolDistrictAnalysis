School District Challenge Analysis


Part 1 – Overview of Project
The purpose of this analysis is assisting our client, Maria, in discovering the overall passing percentages of the students within the school district. During the process, we found that a handful of test scores were altered from the 9th grade class at Thomas High School (THS). Due to this mishap, we filtered out all the math and reading scores from THS and replace them with “NaNs.” This allowed us to compare the overall school district test scores with and without THS data to see how large of an impact the altered data had. 
Part 2 – Results and Discussion of Findings
How is the district summary affected?
After perusing both school district test score summaries from pycityschools and pycityschools_challenge, there doesn’t appear to be a change. (Displayed Below)
PyCitySchools
 

PyCitySchools_Challenge
 
How is the school summary affected?
In PyCitySchools, the overall passing for Thomas High school was 90.94%. When the 9th grade class is factored out, the overall passing decreases by 0.3%
 
 
 
How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
It does not appear to impact either score. An investigation is currently underway, as there is reason to believe the school is not including majority of 9th grade test scores. Including all scores may run the risk of lowering the school’s overall ranking. 
How does replacing the ninth-grade scores affect the following: Math and reading scores by grade | Scores by school spending | Scores by school size | Scores by school type? 
Math & Reading scores by grade	The only difference that can be pinpointed at this time is that all test scores from 9th graders attending Thomas High School shows “NaN.”
Scores by school spending	The numbers are almost identical, as the 9th graders test scores have been eliminated from the dataset.
Scores by school size	The overall passing percentage does not change.
Scores by school type	Scores by school type are not altered at all. 

Part 3 – Conclusion:
After replacing the scores of the 9th grade students, it Is apparent that not much has changed. The values that had the potential to alter size, district, spending and overall passing percentage of the students have been nullified. 

![image](https://user-images.githubusercontent.com/94502363/161863593-9f9480ff-1838-470b-a166-da41df899215.png)
