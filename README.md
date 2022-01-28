# School_District_Analysis

## Purpose and Objectives

The objective of this project was to analyze standardized test performance and find trends on school and district level. The csv files can be found in the "Resources" folder. "PyCitySchools.ipynb" was the main analysis using the complete data in the .csv files. On the other hand, "PyCitySchools_Challenge.ipynb" analysis had a similar process but the test scores for 9th grade students in Thomas High School were changed to null values due to suspected academic dishonesty.

## Results

For each subsection, the first image will be from "PyCitySchools.ipynb" while the second one will be from "PyCitySchools_Challenge.ipynb".

### District summary

<img width="983" alt="PyPoll_district_summary" src="https://user-images.githubusercontent.com/92544151/151626580-67cea3db-0d7d-44e7-8766-882826f45b3c.png">
<img width="977" alt="Challenge_district_summary" src="https://user-images.githubusercontent.com/92544151/151626587-9aacbf29-df2b-4f9d-b448-c575eee937c7.png">

As the results above show, the district summary for the challenge shows a slight decrease across %Passing Math, %Passing Reading and %Overall Passing. This is due to the null values for 9th grade students from Thomas High School. 

### School summary

<img width="1193" alt="PyPoll_school_summary" src="https://user-images.githubusercontent.com/92544151/151627816-e4e644c7-35ae-4765-8e9e-2fdbcfd27c72.png">
<img width="1197" alt="Challenge_school_summary" src="https://user-images.githubusercontent.com/92544151/151627972-6d01bd69-e367-4f8c-99b2-9e69ba095a71.png">

For this part of the analysis, "Thomas High School" is the only one with different results. The %Passing Math went down from 93.2% to 66.9%. Similar decreases for %Passing Reading (97.3% to 69.7%) and %Overall Passing (90.9% to 65.1%) were observed. A decrease was expected as the scores for 9th grade students in the school were changed to null. 

### Top 5 schools

<img width="1196" alt="PyPoll_Top_5" src="https://user-images.githubusercontent.com/92544151/151628726-bd6519d1-5c61-4a15-b225-8405c9f71bf4.png">
<img width="1182" alt="Top_5_Challenge" src="https://user-images.githubusercontent.com/92544151/151628757-fe6b846a-f335-44ce-a6d4-8029a54d908f.png">

Thomas High School is still the second best performing school as the results show.

### Bottom 5 schools 

<img width="1194" alt="CitySchools_ Bottom 5" src="https://user-images.githubusercontent.com/92544151/151629146-6d270271-cb3a-4414-afb9-c81c2a6401f2.png">
<img width="1180" alt="Bottom_5_Challenge" src="https://user-images.githubusercontent.com/92544151/151629153-288d4a6e-0e10-4e85-834c-3ba30055a492.png">

No major changes were observed here, as expected. 

### Math scores by grade 

<img width="312" alt="PyPoll_math_bygrade" src="https://user-images.githubusercontent.com/92544151/151629853-79ff16b9-e888-41a2-a1d6-94b392b77ec9.png">
<img width="316" alt="Challenge_math_bygrade" src="https://user-images.githubusercontent.com/92544151/151629866-d9dd3d7d-d0ef-4850-ac08-1f6de0d1a14c.png">

This shows and confirms that the results for the Thomas High School 9th grade were changed to "nan".

### Reading scores by grade 

<img width="314" alt="PyPoll_reading_bygrade" src="https://user-images.githubusercontent.com/92544151/151629976-c292ba34-d738-44cc-ae91-97b2022b3b52.png">
<img width="321" alt="Challenge_reading_bygrade" src="https://user-images.githubusercontent.com/92544151/151629990-8466afe8-987e-4269-b817-d2df5f75180d.png">

Again, values for Thomas High School 9th grade students are "nan".

### Grouped by school spending 

<img width="865" alt="PyPoll_score_byschoolspending" src="https://user-images.githubusercontent.com/92544151/151630185-1d1d0f37-d39d-4c7e-829d-c8522cc8bc0b.png">
<img width="859" alt="Challenge_score_byschoolspending" src="https://user-images.githubusercontent.com/92544151/151630192-b82c70eb-ab9b-4549-b4bb-c153b4819085.png">

Thomas High School falls in the third section ($630 to 644 per student), so this is the only group with slightly different results.

%Passing Math : 73.48% to 73.46%

%Passing Reading : 84.39% to 84.32% 

%Overall Passing : 62.86% to 62.78%

### Grouped by school size 

<img width="809" alt="PyPoll_score_byschoolsize" src="https://user-images.githubusercontent.com/92544151/151630232-b0239863-ce35-4611-8e4e-748e32747536.png">
<img width="809" alt="Challenge_score_byschoolsize" src="https://user-images.githubusercontent.com/92544151/151630245-b852351f-820d-4fe1-9a4b-052118a3a0ce.png">

Thomas High Score has medium school size, so the following minor changes were observed in the results.

%Passing Math : 93.60% to 93.58%

%Passing Reading : 96.79% to 96.73%

%Overall Passing : 90.62% to 90.56% 

When formatted to 1 decimal place, only %Passing Reading has a 0.1% difference in values. 

### Grouped by school type 

<img width="755" alt="PyPoll_score_byschooltype" src="https://user-images.githubusercontent.com/92544151/151630274-85d58b11-be66-49a1-85da-5f63b85621b9.png">
<img width="754" alt="Challenge_score_byschooltype" src="https://user-images.githubusercontent.com/92544151/151630287-13d7c685-f5a4-4274-93c4-ea122a285c25.png">

In this case, Thomas High School is a Charter school, so we observe the folling differences in that row. 

%Passing Math : 93.62% to 93.61%

%Passing Reading : 96.59% to 96.55%

%Passing Overall : 90.43% to 90.39%

Again, the differences are minor. 

## Summary 






