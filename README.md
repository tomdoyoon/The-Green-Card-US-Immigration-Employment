# The-Green-Card-US-Immigration-Employment-Project
Using statistical analysis and machine learning models to learn more about permanent immigration through employment.

Feel free to read the full report titled, The Green Card: A Pathway To Living And Working In The U.S., to further explore my methodologies, analysis, and insights.

Please use the Table of Contents, found below, to navigate the repository!

# Introduction
In this project I explore PERM (Green Card) data compiled from the U.S. Department of Labor over 2014-2021. The data can be retrieved, partioned by year, from the Performance Data section of the Foreign Labor Certification section, under Employment and Training Administration.

For ease of use, I cleaned and compiled each of the following year's PERM data:
- FY2021, FY2020, FY2019, FY2018, FY2017, FY2016, and FY2015

While data was available from FY2008, granular data on the applicant, employer, and application was only available from FY2015 to present. 

I analyze the trends found within successfull applicants, while considering the fact that all applicants have already faced "success". This is due to the nature of the data - all applicants have already impressed an employer, passed the interviews, and received a job offer all as a foreign national. To provide further insight into the candidates that are chosen for Green Card sponsorship, I analyze not only features of candidates that eventually received a "certified" case status, but also every candidate an employer submited an application for.

The objective of the report is to provide an independent study into how an immigrant can have the most successfull chance at becoming permanently employed (immigration through employment) in the United States. This is done through analyzing and interpretting the trends found within the total PERM data sets. It is important to note, however, the changing nature of immigration and employment. What was the trend over the last seven years, may not repeat itself for the next seven years.

The project is concluded with a regression deep learning model, Random Forest model, and a Linear Regression model that all have an objective to estimate a particular applicant's annual wage offered. The project also includes a classification deep learning model, Upsampled Random Forest model, Downsampled Random Forest model, SMOTE Random Forest model, and a regular Random Forest model that all have an objective to estimate if a particular applicant will be successful and receive a certified status.

# Table of Contents:
- Cleaning, EDA, and StatAnal: Analysis related to the PERM Green Card Immigration Employment data over 2014-2021.
- Machine Learning and Deep Learning: Models predicting an applicant's Green Card outcome, days taken to decide an applicant, and annual wage offered.
- The Green Card: A Pathway To Living And Working In The U.S.: A report detailing my exploratory data analysis, statistical analysis, and machine learning applications on Green Card Immigration Employment data in the United States over 2014-2021.

# Observations and Findings:
Model Evaluations:

The top performing regression model would be 
The top performing classification model would be
