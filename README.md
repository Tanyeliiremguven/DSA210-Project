# DSA210-Project
Step Count Analysis During Exam Periods

MOTIVATION

This project aims to analyze my step count and how it gets affected during my exam dates by comparing the step count on exam days, before exam days, and after exam days. 

Since I live on campus, I mostly go anywhere on foot. (such as my room, faculty classes, dining hall, etc.) So, there will be specific patterns in my daily step count changes in my exam periods since my physical activities decline in that period. The goal is to analyze my step count during my exam days and regular days and examine how stress levels and time constraints in my exam periods affect my physical activity patterns.


DATA SOURCES

In this project I will be using my steps count data and my exam dates data.

- Steps Data:
  
  * Source: Extracted from the 'Health' app on my iphone.
 
  *  Process:
    * Exported all the health data in .xml format to my computer.
    * Step count data extracted from other health metrics by using Python.
    * Daily step counts calculated day by day and converted to .csv format to analyze easily.
 
- Exam Dates Data:

  * Source: Manually colected external data based on my university's exam schedule.
 
  * Process:
    * Recorded 2024 spring and fall terms exam dates in an Excel file and arrange them chronologically (oldest to newest). 
    * Converted the Excel file to .csv format.
    * Exam dates format was changed to YYYY-MM-DD to correspond with the steps data format.


OBJECTIVES

- Analyze daily step count data to determine how exam dates affect levels of physical activity.
- Compare the step counts; before, during, after exam days, and regular days (days that are not associated with exam periods).
- Determine patterns or trends in physical activity during exam periods.
- Analyze stress levels and time constraints impacts on daily physical activity.
- Establish if there is any correlation between exam dates and activity levels.


METHADOLOGY

- Data Collection:
  
  * Export step count data in .xml format from the' Health' app.
  * Manually compile and organize exam dates in .csv format.

- Data Cleaning:
  
  * Eliminate any irrelevant health indicators and address any missing data.
  * Ensure date formats are 'YYYY-MM-DD' for both steps and exam dates datas.
 
- Data Integration:
  
  * Construct a single dataset for analysis by combining exam dates and step data.
  * Label days as; before exam days, exam days, after exam days, and regular days.
 
- Exploratory Data Analysis (EDA):
  
  * Bar Charts: Display the average step counts before, during, and after exams.
  * Time-Series Plots:  Indicate exam dates and show step count trends over time.
  * Compare step counts between exam-related days and regular days.
 
- Statistical Analysis:
  
  * To assess the significance of observed patterns, run statistical tests (such as ANOVA and t-tests).
  * Examine if there are any correlations between exam schedules and step counts.
 
- Interpretation and Insights:
  
  * Identify patterns such as declines in physical activity on exam days or recovery trends after exams.
  * Provide practical recommendations on how to maintain balanced physical activity under stressful periods.
    
