# School District Analysis

School District Analysis using Anaconda, Jupyter Notebook, Pandas & Python

## Overview of the Project

The purpose of this project is to analyze the Student’s standardized test scores and funding. specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards.

Here is the list of deliverables for the analysis of the school district:

•	A high-level snapshot of the district's key metrics, presented in a table format

•	An overview of the key metrics for each school, presented in a table format

•	Tables presenting each of the following metrics:

 -   Top 5 and bottom 5 performing schools, based on the overall passing rate

 -   The average math score received by students in each grade level at each school

 -   The average reading score received by students in each grade level at each school

 -   School performance based on the budget per student

 -   School performance based on the school size

 -   School performance based on the type of school Before we can begin these tasks, we need to import the datasets into Jupyter Notebook using Python.
 
## Background Analysis and Challenges

The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.

### Determine Data Types Challenge Data Background

You have been tasked with getting key metrics from the datasets. This will involve performing calculations to get sums, averages, and percentages. Before you perform these calculations, though, you should check if the numbers in these datasets are the correct data type for making those calculations, as this is considered a best practice.

Here are six common data types that we may encounter in this module and that you may come across in the future:

### Pandas Name, Data Types & Arithmetic Operators

![image](https://user-images.githubusercontent.com/90879122/138633793-55af0de0-501b-4270-ba22-8140d782a591.png)

# Deliverable 1: Replace Ninth-Grade Reading and Math Scores

### Instructions: 

Using the Pandas loc method with conditional statements and comparison and logical operators, select the ninth-grade reading and math scores for Thomas High School. Then, use the Pandas NumPy module to change the reading and math scores to NaN.

### Deliverable 1 Requirements:

•	The loc method is used to select all the reading and math scores from the ninth grade at Thomas High School. Inside the loc method, the following are completed:

- A comparison operator is used to retrieve all the rows with Thomas High School in the "school_name" column of the student_data_df.
- A comparison operator is used to retrieve all the rows with the ninth grade in the "grade" column of the student_data_df.
- Logical and comparison operators are used to retrieve all the rows with the "reading_score" column for Thomas High School ninth graders from the student_data_df.
- Logical and comparison operators are used to retrieve all the rows with the "math_score" column for Thomas High School ninth graders from the student_data_df.
- The reading and math scores for the ninth graders in Thomas High school are replaced with NaNs.

## Deliverable 1 Results with detail analysis:

### 1. A comparison operator is used to retrieve all the rows with Thomas High School in the "school_name" column of the student_data_df.

![image](https://user-images.githubusercontent.com/90879122/138634033-b23e5194-56e4-4eca-a1a9-b58d2f472428.png)

### 2. A comparison operator is used to retrieve all the rows with the ninth grade in the "grade" column of the student_data_df.

![image](https://user-images.githubusercontent.com/90879122/138634065-7fda50d4-0857-4375-b0a5-7e7918de61bc.png)

### 3. Logical and comparison operators are used to retrieve all the rows with the "reading_score" column for Thomas High School ninth graders from the student_data_df.

![image](https://user-images.githubusercontent.com/90879122/138634089-ecb4ff09-5b7e-44a6-850c-f1112ab46d4f.png)

### 4. Logical and comparison operators are used to retrieve all the rows with the "math_score" column for Thomas High School ninth graders from the student_data_df.

![image](https://user-images.githubusercontent.com/90879122/138634122-aed2ef5c-c198-4352-b3cf-53803a86fc66.png)

### 5. The reading and math scores for the ninth graders in Thomas High school are replaced with NaNs.

![image](https://user-images.githubusercontent.com/90879122/138634158-894a4194-22e8-4d93-ac94-eec20c6e72c4.png)

### Code and Image for Reading

![image](https://user-images.githubusercontent.com/90879122/138634198-b1e69c55-7070-49a3-9a1e-24135645e334.png)

![image](https://user-images.githubusercontent.com/90879122/138634212-cd944f1e-6217-40c7-aac9-5ed100864f30.png)

# Deliverable 2: Repeat the School District Analysis

Instructions: Repeat the school district analysis you did in this module, and recreate the following metrics:

•	The district summary

•	The school summary

•	The top 5 and bottom 5 performing schools, based on the overall passing rate

•	The average math score for each grade level from each school

•	The average reading score for each grade level from each school

•	The scores by school spending per student, by school size, and by school type

## Deliverable 2 Requirements:

•	The district summary DataFrame.

•	The school summary DataFrame.

•	The top 5 performing schools, based on the overall passing rate.

•	The bottom 5 performing schools, based on the overall passing rate.

•	The average math score for each grade level from each school.

•	The average reading score for each grade level from each school.

•	The scores by school spending per student.

•	The scores by school size.

•	The scores by school type.

## Deliverable 2 Results with detail analysis:

### 1. The district summary DataFrame.

![image](https://user-images.githubusercontent.com/90879122/138634415-1a662bdc-75ad-41e3-be55-21eb4443bc13.png)

### 2. The school summary DataFrame.

![image](https://user-images.githubusercontent.com/90879122/138634460-5cebdfc1-81a4-4388-b72d-40080f0e253b.png)

### 3. The top 5 performing schools, based on the overall passing rate.

![image](https://user-images.githubusercontent.com/90879122/138634497-a1e0cfab-0c74-4840-a2e6-debbdf7a99c0.png)

![image](https://user-images.githubusercontent.com/90879122/138634518-c2dd00f5-b0d1-4443-9f04-29ab51d3ae17.png)

### 4. The bottom 5 performing schools, based on the overall passing rate.

![image](https://user-images.githubusercontent.com/90879122/138634549-fd572773-b7e6-45c2-8704-c270dafd0383.png)

### 5. The average math score for each grade level from each school.

![image](https://user-images.githubusercontent.com/90879122/138634579-920e6be7-0513-4ce3-9746-f78792db8528.png)

### 6. The average reading score for each grade level from each school.

![image](https://user-images.githubusercontent.com/90879122/138634627-5da429db-62cf-4b34-9770-7cbf9cea9732.png)


### 7. The scores by school spending per student.

![image](https://user-images.githubusercontent.com/90879122/138634666-d2c11e22-410b-4649-bf9f-67ea1d7fdadf.png)


### 8. The scores by school size.

![image](https://user-images.githubusercontent.com/90879122/138634694-45519b52-18bb-468a-aa25-0b2acd6fec62.png)

### 9. The scores by school type.

![image](https://user-images.githubusercontent.com/90879122/138634730-82336e44-b92a-40c2-a167-5c09d63ae621.png)

# Deliverable 3: A Written Report for the School District Analysis


  1.	Overview of the school district analysis: Explain the purpose of this analysis.

  2.	Results: Using bulleted lists and images of DataFrames as support, address the following questions.

## How is the district summary affected?

### BEFORE DATA CLEANUP

•	Average Math Score = 79.0

•	Average Reading Score = 81.9

•	% Passing Math 75

•	% Passing Reading 86

•	% Overall Passing 65

### Before Cleanup - PyCitySchools file

![image](https://user-images.githubusercontent.com/90879122/138634862-75f1d26d-2aaa-45d3-9795-4b06d14636c8.png)

### AFTER DATA CLEANUP

•	Average Math Score = 78.9

•	Average Reading Score = 81.9

•	% Passing Math 74.8

•	% Passing Reading 85.7

•	% Overall Passing 64.9

## After Cleanup - PyCitySchools_Challenge file

![image](https://user-images.githubusercontent.com/90879122/138634937-3f4922f2-17e5-46df-9afe-3868089f3ad3.png)

### OBSERVATION: 

Slight change in Math Score, including % Passing district averages, Comparing the two dataframes above, the average show the difference when the 9th grade student Math and Reading scores from Thomas High Schools were excluded from the District Summary.

## How is the school summary affected?

### BEFORE DATA CLEANUP

•	Thomas High School's % Overall Passing was 91, placing second

### Before Cleanup - PyCitySchools file

![image](https://user-images.githubusercontent.com/90879122/138635045-b5dd1f4c-cdc3-4df6-94c7-0fad6db5eeb0.png)

### AFTER DATA CLEANUP

•	Thomas High School's % Overall Passing was 65, placing eight

### After Cleanup - PyCitySchools_Challenge file

![image](https://user-images.githubusercontent.com/90879122/138635103-41170cb8-8205-4d47-86f6-bfcb998c5343.png)

### OBSERVATION: 

Overall order change due to Thomas High School cleanup

## How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

### OBSERVATION: 

Replacing ninth graders’ math and reading scores affect Thomas High School’s performance between the other schools, Relative ranking for Thomas High School changed from 2nd place to 8th (see images above).

## How does replacing the ninth-grade scores affect the following:

•	Analysis Below:

- o	Math and reading scores by grade


--	Math and Reading Scores from Thomas High School 9th Grade set to "nan" and equivalent to 0.

--	Math and Reading Scores from Thomas High School 9th Grade means all of them failed (set to fail for analysis).

--	Doing that, the only significantly score affected was minimal in a very small in quantity.

--	Student count() Before THS Cleanup was: 1635

--	Student count() After THS Cleanup was: 1174

- o	Scores by school spending

--  Thomas HS is in the spending bucket "$630-644"

--	Math and Reading Scores from Thomas High School 9th Grade means all of them failed (set to fail for analysis).

--	Doing that, the only significantly score affected was minimal in a very small in quantity.

--	Student count() Before THS Cleanup was: 1635

--	Student count() After THS Cleanup was: 1174

### Before Cleanup - THS count()

![image](https://user-images.githubusercontent.com/90879122/138635704-b145e219-a653-441e-9ed6-9ae1edd6a5e1.png)

### After Cleanup - THS count()

![image](https://user-images.githubusercontent.com/90879122/138635721-7ee73cb7-75f5-48be-a52b-21ab9003d5f9.png)

- o	Scores by school size

--  	Removing Thomas High School 9th Grade reduces the "% Passing Math", "% Passing Reading" and "% Overall Passing" scores for size bucket.

In Addition

--  Removing Students from Thomas High School 9th Grade reduces the "% Passing Math", "% Passing Reading" and "% Overall Passing" scores for spending bucket "$630-644"

--	Thomas High School is allocated on Spending Bin "$630-644" (image below)

### School Size"

![image](https://user-images.githubusercontent.com/90879122/138635858-ebf76c4e-8b6e-4a37-943d-b5b522137e66.png)


### THS Spending Bin "$630-644"

![image](https://user-images.githubusercontent.com/90879122/138635886-294e0bdb-f553-4c63-98b8-0e0a99f3e82f.png)

![image](https://user-images.githubusercontent.com/90879122/138635898-05b8ffe2-5534-4ae1-9431-a961bb249a3b.png)

## THS Before Cleanup on Spending Rank

o	Scores by school type

--  Thomas High School is in the "CHARTER" type

--  Removing Thomas High School 9th Grade scores reduces the "% Passing Math", "% Passing Reading" and "% Overall Passing", see below.

### Before Cleanup - THS count()

![image](https://user-images.githubusercontent.com/90879122/138635981-65cd0c0a-1e40-4085-ad41-1c2e1b727b87.png)

### After Cleanup - THS count()

![image](https://user-images.githubusercontent.com/90879122/138635997-8e4bcdf0-3206-457a-b9b4-67a293d7b10d.png)

## Summary

### In this analysis we can see the comparison between the seven metrics for the school district after dropping all the scores from the Thomas High School 9th grade, the changes were minor as we can see in the images and statements above, but these are the four changes we can see for this school:

- •	A drop of 0.1% for the overall passing rate of the district

- •	No change in the ranking position of Thomas High School but with a minor change in the percentages.

- •	A minor change in the split by spending, size and type in their regarding bins with an average of a .25% drop in their percentages.

- •	As we saw in this analysis, Thomas High School dropped scores only affect in a .02% in average for their summary grades we won't see any mayor change in the metrics nor the rankings of the schools.

- •	Among the medium school size the percent passing math dropped by 4 percent.

- •	Among the medium schools the percentage passing reading dropped 5 percent.

- •	The overall passing percentages in the small and large school sizes remained the same and the medium dropped by 3 percent.

- •	Surprisingly the budget remained the same although the overall passing percentage in the charter schools dropped.








