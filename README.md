# Should I Stay or Should I Go?
Cohort 27 Capstone Project for the Certificate of Data Science at Georgetown University School of Continuing Studies.

## Team Stay or Go
Joy Wu</br>
Jennifer Ziegler

## Should I Stay or Should I Go? Applying Machine Learning to the FEVS to Predict Federal Employee Intent to Leave

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
**Notebooks** contains notebooks for early data analysis, data transformation for two datasets (Large and Tiny_2), machine learning model evaluation, final Linear SVC machine learning model, and post-modeling data analyis.</br>
**Supporting files** contains the list of survey questions, as well as the variable map with feature importances that contributed to recursive feature elimination.</br>
**Paper and Presentation** contains the final paper plus the slide deck used during the final presentation.</br>
**Data Files** contains instructions on how to access the data files referenced in the Notebooks.</br>
