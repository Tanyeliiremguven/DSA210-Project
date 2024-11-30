# DSA210-Project
Step Count Analysis During Exam Periods

OBJECTIVE AND MOTIVATION

This project aims to analyze my step count and how it gets affected during my exam dates by comparing the step count on exam days, before exam days, and after exam days. Since I live on campus, I mostly go anywhere on foot. ( such as my room, faculty classes, dining hall, etc.) So, there will be specific patterns in my daily step count changes in my exam periods. The goal is to analyze my step count during my exam days and regular days and examine how stress levels and time constraints in my exam periods affect my physical activity patterns.


DATA SOURCES

In this project I will be using my steps count data and my exam dates data.

* I get my step data from the 'Health' app on my iPhone.
* I exported my data in .xml format to my computer. Then by using a Python code, I extracted my step data from my other health datas.
* After that I calculated my step data per day by using a Python code and converted my daily step count data to .csv format by using another Python code.
*  I get my exam date data manually as external data.
*  I found my 2024  spring term exam dates and 2024  fall term exam dates and wrote them to Excel and sorted them from oldest to newest. Later on, I converted this Excel document to .cvs format on my computer. When I did it, the dates of exams and the dates of steps are written in different format. To avoid any contradiction between them, I change the exam dates format according to steps dates. 


OBJECTIVES

* In this project I will combine my health data (steps data) with my exam dates data (external data).
* To combine them at first I will first clean my health data since there are other health reports. I will choose my steps data in them.
*  I will get some specific years' data from them.
*  Later on I will get my exam dates in the same format 'YYYY-MM-DD' with my steps data. I will convert my steps .xml to .csv format.
*  Also I will convert my exam dates Excel file to .csv format.
*  IF there is any missingness I will fill in the missing data and convert them into the same format '.csv'. Later on, I will visualize my steps data between the specific dates.
*  And compare the exam dates step count and regular dates step count. By looking at these I will examine the specific patterns, and if there are any drops or spikes in it.
*   Then I will be looking at the correlation between my activity and my exam days. I will be performing some statistical tests and compare my steps and exam days in a data set. I will also comment on other factors that affect my step count per day.


METHADOLOGY
