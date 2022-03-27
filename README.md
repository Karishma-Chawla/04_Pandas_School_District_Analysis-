# Purpose

The project is to aggregate and analyse data on student funding and student standardised test scores for a School district to demonstrate trends that can support strategic decision making at School Board. 
While the initial analysis has been done my Maria, Chief data scientist for a City school district, case of potential academic dishonesty by the ninth grade students of Thomas High School is suspected. So the analysis needs to be repeated excluding the scores of the 9th grade students at Thomas High School.

# Results
Removing the 9th grade scores for Thomas High school did not have any major impact on the school metrics. Below is the snapshot how various paraters have been impacted:
## How is the district summary affected?
At district level, overall passing % of i.e.students passing both math and reading decreased by 0.3%. Average Math Score is down by 0.1, Average Reading saw no change, % of students Passing Math decreased 0.2% and the percentage of students Passing Reading increased by .1%. Below are the original and revised summaries (respectively)

![image](https://user-images.githubusercontent.com/98617082/160246790-cdcc801e-2639-43ba-a3bc-c5d46b0bd232.png)
![image](https://user-images.githubusercontent.com/98617082/160245299-f8fa4a12-45b1-4649-be8f-cc59bacbe964.png)
 
## How is the school summary affected?
The revised analysis results in the overall passing % for Thomas High School falling by 0.3% to 90.6%. Average Math Score decreased by 0.06,Average Reading Score increased by .05, the % Passing Math decreased by 0.09%, the percentage of students Passing Reading decreased by 0.29%. Below are the original and revised summaries (respectively)

![image](https://user-images.githubusercontent.com/98617082/160245886-3cb56854-00f9-458c-b9a5-32ed8a6b1038.png)
![image](https://user-images.githubusercontent.com/98617082/160245889-1d557f9b-e684-49d3-88cf-4d20a5487d82.png)


## How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Removing the 9th graders' scores has not impacted the ranking of Thomas High School vis-à-vis other schools. It still ranks 2nd basis overall passing percentage. So there seems to be consistency in the scores in different grades as neither the average scores or their relative ranks is being impacted by exclusion of 9th grade.
![image](https://user-images.githubusercontent.com/98617082/160246029-adcd85f1-f54a-4342-a134-239b9a1cad45.png)

## How does replacing the ninth-grade scores affect the following:
* Math and Reading scores by grade
The data is impacted only for 9th grade math and reading score where the score is replaced by NaN, Not a Number. Rest all grades for all schools remain un impacted.

* Scores by school spending
Again the marginal change is just for $630-$644 bin under which spending for Thomas High School falls, everything else remaining same. So %Passing Reading and overall passing % decrease marginally by .1%. Initial v/s revised analysis respectively

![image](https://user-images.githubusercontent.com/98617082/160246718-58eeb805-8419-4aff-9544-e2f4cfc342b6.png)
![image](https://user-images.githubusercontent.com/98617082/160246357-6bd0fb2e-7f48-48fa-8941-c15697d8936d.png)

* Scores by school size
Thomas High School falls under the bracket (1000-2000) school size range, and the value of the percentage of the Students Passing Reading decreases by .1%. 
Scores by school type
No impact on performance date in the revised analysis. Score, pass percentages remain same for both school categories.Initial v/s revised analysis respectively


![image](https://user-images.githubusercontent.com/98617082/160246585-74fe06bd-2414-4469-9b4a-c30dbdda6e05.png)
![image](https://user-images.githubusercontent.com/98617082/160246591-ff2b046c-67ee-4c2f-a540-e5c5ba03528f.png)

* Scores by school type
No impact on performance date in the revised analysis. Score, pass percentages remain same for both school categories.Initial v/s revised analysis respectively

![image](https://user-images.githubusercontent.com/98617082/160246550-6df64c06-39a6-497a-8d06-2fd2bc9aee41.png)
![image](https://user-images.githubusercontent.com/98617082/160246573-f45139f2-ae2f-4f18-a0ab-7ff9890f5351.png)

# Summary
Removing the 9th graders test scores did not greatly affect the scores over the whole district or the school. Below are some of the more prominent changes:

*Overall passing score for district decreased by 0.3%.
*Average Math Score for district is down by 0.1
* Overall % student passing both sujects for Thomas High School fell by 0.3% to 90.6%. 
* Average Reading Score for Thomas High School increased by .05,



#Resources
•	Data Source: schools_complete.csv
•	Data Source: students_complete.csv
•	Sofware: Jupyter Notebook 
•	Library: Pandas
•	Library: Numpy
•	Language: Python 3.7.5

