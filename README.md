# Predicting Student Success in Online Courses

## 1. Introduction
The Aim is to build a predictive model  that can estimate whether a student will successfully complete a given course based on the factors such as student profile, engagement data and historical data. In this study the following tasks are carried out:
1.	Building a classification model to predict whether a student will complete the course or drop out before completion.
2.	Analysing feature importance and discuss which factors most strongly influence course completion.
3.	Suggesting how the platform could intervene early to help students at risk of dropping out.
   
## 2. Data Overview
The data includes three  main categories:
-	Student Profile Data: Age, gender, major, academic year and region.
-	Course Engagement Data: Number of logins per week, videos watched, time spent on the platform, and quiz scores.
-	Historical Data: Previous course completion rates, average quiz scores across all courses and the number of courses started but not completed.
  
The synthetic data generated based on these categories using the Faker library in python. Total 1000 student profiles generated, and classification task carried out to predict the success of a course completion or dropout from the course. As the data is unsupervised no labels are provided to predict the success of a course, to predict the completion status of the course manually a threshold is created.
