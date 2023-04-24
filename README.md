# Class_Survey_Analysis

## Dataset

### Source and Editing
* The data is collected from a class of 25 students who have reported their usage of social media apps for seven weeks.
* The data has 15 columns and 175 rows in total.
* The data is not cumulated for each student. Instead, we have considered each row as an individual data entry for better analysis.

### Data Dictionary
* Student - Name of the Student
* Week - Week start and end date
* Whatsapp - Time spent on Whatsapp per week(hrs)
* Instagram - Time spent on Instagram per week(hrs)
* Snapchat - Time spent on Snapchat per week(hrs)
* Telegram - Time spent on Telegram per week(hrs)
* Facebook/Messenger - Time spent on Facebook/Messenger per week(hrs)
* BeReal - Time spent on BeReal per week(hrs)
* TikTok - Time spent on Tiktok per week(hrs)
* Wechat - Time spent on WeChat per week(hrs)
* Twitter - Time spent on Twitter per week(hrs)
* Linkedin - Time spent on LinkedIn per week(hrs)
* Messages - Time spent on Messages per week(hrs)
* Total Social Media Screen Time - Total time spent on social media per week(hrs)
* Social Media Addiction Level - Is the person addicted to social media?
##### Times opened >= 105 - Addicted 
##### Times opened < 105 - Not Addicted 
##### Considering the 24-hour slots in a day, how many hour slots did the user open social media apps? This is for one day. 
##### Consider the above count and add the daily counts over the week and input that data

## Two Approaches
* As we have many outliers, we can analyse the data in two methods and check for any differences.
* We can consider two approaches - One considering all the Data, One considering only the columns WhatsApp, Instagram, Snapchat, LinkedIn, Total Social Media hours, and Addiction.

## QUESTIONS and HYPOTHESIS Questions
1. Based on the given variables, can we classify if the student is addicted to Social Media or not?
2. Based on the given variables, can we predict if the student is addicted to Social Media or not?

## Hypothesis
* We can predict if the student is addicted to social media based on the time they have spent on the individual social media apps.


## File Dictionary

* MVA_Class_Project_aa2569_Report.pdf file gives the brief report of the questions answered and the hypothesis results.
* Class_Survey.csv is the dataset considered for the analysis.
* The Class_Survey_aa2569.Rmd file contains the R code for the complete analysis performed, the flow of thought process, and inferences mentioned after each step.
* The Class_Survey_aa2569.html file gives the output of the Rmd file which includes the outputs of the file with visuals and inferences.


