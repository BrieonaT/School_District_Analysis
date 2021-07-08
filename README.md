 ## Overview of the school district analysis:
In this module, we were tasked with formatting and analyzing data from a city school district. Our original goal was to learn insights on data from a number of high school's reading and math test scores, and find trends in which schools were performing well, along with which schools needed more help in order to do so. We looked and analyzed 15 different high schools and took a look at things such as their test scores for reading and math across grades, as well with funding within the schools and taking in account whether the school was a district school or a charter school. After reviewing the data, we learned that there was tampering with the grades specifically of Thomas High School's 9th grade students. In order to get a better read on statistics across these high schools, we were asked to omit the grades for Thomas High School's 9th grade students and re-do our analysis.
 
## Results:
The results of re-doing the district analysis without the Thomas High School 9th grade class were as follows.
 
Before the Thomas High School 9th grade class were taken out, the results showed the following:
- Average Math Score was 79.0
- Average Reading Score was 81.9
- % Passing Math was 75%
- % Passing Reading was 86%
- % Overall Passing was 65%.


After the Thomas High School 9th grade class were taken out, the results showed the following:


- Average Math Score was 78.9
- Average Reading Score was 81.9
- % Passing Math was 74.8%
- % Passing Reading was 85.7%
- % Overall Passing was 64.9%.
 
![Original District Analysis Summary](https://github.com/BrieonaT/School_District_Analysis/blob/main/Resources/Original_Analysis_District_Summary.png)
![2ND Analysis District Summary](https://github.com/BrieonaT/School_District_Analysis/blob/main/Resources/Second_Analysis_District_Summary.png)
 
 
 
 
Not only did the score change show that the district summary was affected, it also meant that Thomas High School's statistics were also affected.
 
Before the second analysis, the results were as follows:
- Average Math Score was 83.4
- Average Reading Score was 83.8
- % Passing Math was 93.2%
- % Passing Reading was 97.3%
- % Overall Passing was 90.9%.



After the second analysis, the results were as follows:


- Average Math Score was 83.3
- Average Reading Score was 83.8
- % Passing Math was 93.1%
- % Passing Reading was 97.0%
- % Overall Passing was 90.6%.
 
![Original Analysis Thomas High School Overview](https://github.com/BrieonaT/School_District_Analysis/blob/main/Resources/Original_Analysis_THS_Overview.png)
![2nd Analysis Thomas High School Overview](https://github.com/BrieonaT/School_District_Analysis/blob/main/Resources/Second_Analysis_THS_Overview.png)
 
Naturally, with the change in data, one might wonder if there is an effect on Thomas High School's performance in relation to other schools in the area. However, a peak at the top schools shows that it's position has not changed with this change. This is shown in the two images shown below; the first image is the original analysis, and the second image is the redone analysis.
 
![Original Analysis Top 5 Schools](https://github.com/BrieonaT/School_District_Analysis/blob/main/Resources/Original_Analysis_Top5.png)
![2nd Analysis Top 5 Schools](https://github.com/BrieonaT/School_District_Analysis/blob/main/Resources/Second_Analysis_Top5.png)
 
 
Replacing the Thomas High School's 9th grader's scores has the following effects:
-Math and reading scores by grade: The only difference now is that the Thomas High School's ninth grade scores have been changed to NaN.
-Scores by school spending: The school spending has not changed.
-Scores by school size: The scores by school size has not changed.
-Scores by school type: The scores by school type have not changed.
 
In conclusion, the difference between the analysis shows that changing the Thomas High School's contaminated data has an effect on the analysis. This is observed first and foremost in the district's overall data. The average math score for the whole district went down a point after removing the scores. In addition, this caused the percentage passing math in the district summary to go down along with the overall passing. Not only was the district as a whole affected, but Thomas High School's individual statistics were altered. This is shown again with the math scores. The average reading score changed from 83.4 to 83.3, going down 0.1. As with the district as a whole, this affects both the percentage who passed reading along with the overall passing scores. It doesn't appear that things such as the top performing schools have changed, however it is vital to take in account the contaminated data to provide a better snapshot of the analysis.
