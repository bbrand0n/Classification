# Classification
Machine Learning using Classification

Purpose:
In this assignment, you have to perform so some classification tasks on a given data set. Also
as part of the classification tasks, you need to perform a number of data preprocessing, PCA 
for reducting dimensions, and grid search for hypar parameter optimization. For each section, you 
must have to put the question (with question number) and an appropriate header text as a text 
cell. And after the header, you can use multiple cells for coding and explaining, and plotting.


Data Context:
A company which is active in Big Data and Data Science wants to hire data scientists among people who successfully pass some courses which conduct by the company. Many people signup for their training. Company wants to know which of these candidates are really wants to work for the company after training or looking for a new employment because it helps to reduce the cost and time as well as the quality of training or planning the courses and categorization of candidates. Information related to demographics, education, experience are in hands from candidates signup and enrollment.

 

This dataset designed to understand the factors that lead a person to leave current job for HR research too. By model(s) that uses the current credentials, demographics, experience data you will predict the probability of a candidate to look for a new job or will work for the company, as well as interpreting affected factors on employee decision.

Although the main objective of this kind of data is the build predictive model to classify a candidate to find the probability whether the candidate will work for them or not, your main goal in this assignment will be to do exploratory data analysis (We have learned various concepts of EDA in the class already in the class). During this process you will learn more about this data, missing values, outliers, correlations, distributions, filling out missing values or removing records, combining features, removing unnecessary features, etc. You will also find other issues such as whether the data set is imbalanced and if yes, how to balance it, etc.

 

In order to answer the questions, you might need to use your python and EDA knowledge from data camp courses, lecture notes, and for some python syntax and libraries, you might need to google or use python documentation and examples.

 

List of Features

enrollee_id : Unique ID for the candidate
city: City code
city_ development _index : Developement index of the city (scaled)
gender: Gender of candidate
relevent_experience: Relevant experience of candidate
enrolled_university: Type of University course enrolled if any
education_level: Education level of candidate
major_discipline :Education major discipline of candidate
experience: Candidate total experience in years
company_size: No of employees in current employer's company
company_type : Type of current employer
lastnewjob: Difference in years between previous job and current job
training_hours: training hours completed
target: 0 – Not looking for job change, 1 – Looking for a job change
