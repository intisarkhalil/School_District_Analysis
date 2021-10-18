# Schools District Analysis
## Overview of the school district analysis: 
The purpose of this school district project is to aggregate the data and showcases trends in school performance using variaty of data sources [Resources]. This analysis will assist the school board superintendent in making decision regarding the school budgets and priorities analyze data on student’s funding and student’s standardized test of math and reading scores, as well as varies information on their schools.  According to potential academic dishonesty among a group of students, we repeat the analysis to find the evidence that the reading and math grades for Thomas High School ninth graders changed. We use **Pyson 3.7** as a development inviroment and **Anaconda** Packadge and **Jupyter NoteBook** interface for the analysis.  
## Results: 
The findings and insights in this report are presented by comparing the results of the first full-data study and the results of the second study when we replaced the 9th grade math and reading scores from Thomas High School.

### The Effect on the District Summary:
The following two images showcases that replacing of the nine-grade student’s math and reding score from Thomas high school affected the average math and reding scores as well as the % of passing math and reading and the overall percentage of passing. We present the results to 2-decimal places to show the differences.
 
![image](https://user-images.githubusercontent.com/62036983/137657303-7e009e5d-0abd-4389-a1f3-a3c353ab87c9.png)
![image](https://user-images.githubusercontent.com/62036983/137657313-e290c002-e426-4ff4-a1c7-defd53caec80.png)

```
  o	The overall passing percentage decrease: from (65.2%) in the first study to (64.9%) in the second study.
  o	Passing Reading percentage decrease: from (85.8%) to (85.7%) in the second study
  o	Passing Math percentage decreases: from (75.0%) to (74.8%) in the second study.
  o	Average Reading Scores decrease from (81.88) to (81.86) in the second study.
  o	Average Math score decrease from (78.99) to (78.93) in the second study.
```
### The Effect on the School Summary: 
The following two image show the school summary in the two studies. The overall passing for Thomas high school decreased significantly from (90.94% to 65.07%) after declaring the 9th grade scores. Also, the % Passing Math and Reading are significantly decrease. 

![image](https://user-images.githubusercontent.com/62036983/137657350-2bd22dfd-4dcb-424c-991a-071875c1b336.png)
![image](https://user-images.githubusercontent.com/62036983/137657371-3fba516b-dfe2-4ceb-875b-b3cc24a904b3.png)

### The effect of replacing the ninth graders’ math and reading scores with NaNs on Thomas High School’s performance relative to the other schools?

Replacing the Math and Reading scores for ninth graders does not affect Thomas High School's performance compared to other schools, because Thomas School is still in second place among the top five schools. Although there was a slight decrease in its indicators, the overall percentage of success for example decreased from 90.94 to 90.63.

![image](https://user-images.githubusercontent.com/62036983/137657429-e64bd143-9034-4e8c-b301-dbfabb82312c.png)
![image](https://user-images.githubusercontent.com/62036983/137657463-27d7ebae-6d7f-465d-b4fc-20464f8b3dc4.png)
 
 
### How does replacing the ninth-grade scores affect the following:
•	Math and reading scores by grade

![image](https://user-images.githubusercontent.com/62036983/137657489-c5e6122e-73f6-4987-817a-55598faed124.png)
 
The above image show that replacing the ninth-grade scores by NaNs does not affect the other grades indicators for Thomas high school.
 
![image](https://user-images.githubusercontent.com/62036983/137657507-737628cb-bde0-42cf-94ae-14afc760e74d.png)

•	**Scores by school spending:**

The following image show that replacing the ninth-grade scores with NaNs affect the scores per school spending. The Average Scores and Passing Percentages decrease in the group of spending per student in the range ($630-644); 
```
-	% Overall Passing decrease from (%63 to %53)
-	% Passing Math: (%73 to %67)
-	% Passing Reading: (%84 to %80)
-	Average of Passing Math: (78.5 to 76.9)
-	Average of Passing Reading: (81.6 to 80.9)
```

![image](https://user-images.githubusercontent.com/62036983/137657927-005a6246-5ba3-4f61-a293-10ed177292a0.png)
![image](https://user-images.githubusercontent.com/62036983/137657951-7edfdc39-63c8-48c4-ac00-e033f86cf211.png)

•	**Scores by school size**
The following image show that replacing the ninth-grade scores with NaNs does not affect Average Scores and Passing Percentages by school size.

![image](https://user-images.githubusercontent.com/62036983/137657992-bc83eb3e-aaad-4654-bf57-2aee4e2954a0.png)

 •	**Scores by school type**
The following image show that replacing the ninth-grade scores with NaNs does not affect Average Scores and Passing Percentages by school size.
 
 ![image](https://user-images.githubusercontent.com/62036983/137658022-57283532-7204-4453-bff3-80dfbe68fce4.png)

## Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
-	Replacing of the nine-grade student’s math and reding score from Thomas high school affected district summary results; the average math and reding scores as well as the % of passing math and reading and the overall percentage of passing.
-	Replacing of the nine-grade student’s math and reding score from Thomas high school affected the school summary; The overall passing for Thomas high school decreased significantly. Also, the % Passing Math and Reading are significantly decrease.
-	Replacing the Math and Reading scores for ninth graders does not affect Thomas High School's performance compared to other schools, because Thomas School is still in second place among the top five schools. Although there was a slight decrease in its indicators.
-	Replacing the ninth-grade scores with NaNs affect the scores per school spending. The Average Scores and Passing Percentages decrease in the group of spending per student in the range ($630-644).

