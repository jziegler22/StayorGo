# ShouldIStayorShouldIgo
Cohort 27 Capstone Project for the Certificate of Data Science at Georgetown University School of Continuing Studies.

## Abstract
Using Machine Learning, Team Stay or Go analyzed five years of Federal Employee Viewpoint
Survey data to identify the factors that predict an employee selecting “Leave” on the annual
Intent to Leave question. After ingesting and wrangling survey data for 2016-2020, Team Stay or
Go tested a 171-feature numeric dataframe using five machine learning model families. We used
the model performances to reduce features to 17. Using Linear SVC, which had demonstrated the
best combination of predictive ability and speed, we ran a sample of 1.8M rows and identified
the top 13 features that predict an employee selecting something other than “Stay” in the FEVS
survey. The project validated the use of the Global Satisfaction Index (GSI) and a portion of the
Annual Employee Survey (AES), but not the Employee Engagement Index (EEI), to predict
federal employee Intent to Leave.

## Files
**Notebooks** contains early data analysis, data transformation for two datasets (Large and Tiny_2), machine learning models, and post-modeling data analyis</br>
**Supporting files** contains the list of survey questions, as well as the variable map with feature importances that contributed to recursive feature elimination.</br>
**Paper and Presentation** contains the final paper plus the slide deck used during the final presentation.</br>
**Data Files** Unfortunately, the data files are too large to upload to GitHub. Please contact a team member.</br>
