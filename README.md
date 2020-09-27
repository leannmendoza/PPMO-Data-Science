# PPMPO-Data-Science
Exploratory data science and machine learning analysis of statistical project management data to optimize project planning and management

## predicting_project_survival_using_skl.ipynb
Modeled after the common machine learning project "predicting passenger survival based on titanic data," this project looks at raw project management data taken from Atlassian's Jira platform, and predicts projection of "survival." Trained on completed projects, tested on completed projects as well as active projects. We define survival as "will this project meet its anticipated end date +/- 5 days?" with the intention of the model picking up on key features such as milestone counts, staff counts, what does the project volatility like  right now. Predicting with 99.17% accuracy (although over a pessimistic, unbalanced dataset), this analysis proves that we should open up a seat at the table for ML in statistical project management. 

## LSTM_PAH12DayForecasting.ipynb
Forecasting Project Volatility: Utilizing Long Short Term Memory networks to forecast flow of project volatility with high accuracy
Modeled after predicting passengers that will fly over a series of months, this project uses historical time-series project management date and predicts the inflections and flow of product volatility over the duration of a project. At its current state, the model can accuratly predict the last 12 days of the project volatility based on historical trends. With continous enhancement, we plan to optimize the code to predict future trends. 
