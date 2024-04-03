# Project Viability and Management Optimization through Machine Learning (ProVizML)

## Project Overview

The PPMO-Data-Science project engages in exploratory data science and machine learning analysis of statistical project management data to optimize project planning and management processes. Through sophisticated modeling techniques, the project aims to provide predictive insights into project "survival" - defined as the likelihood of a project meeting its anticipated end date within a margin of +/- 5 days. This initiative seeks to harness the untapped potential of machine learning in statistical project management, offering a novel approach to project forecasting and optimization.

## Notebooks

### predicting_project_survival_using_skl.ipynb

This notebook draws inspiration from the well-known machine learning challenge of predicting passenger survival on the Titanic. However, it shifts the focus to the realm of project management, utilizing raw data from Atlassian's Jira platform. The model predicts project "survival" based on various features such as milestone counts and staff allocations, achieving an accuracy of 99.17% on a challenging dataset. This high level of precision underscores the viability of machine learning applications in project management decision-making, even if the dataset is acknowledged as pessimistic and potentially unbalanced.

### LSTM_PAH12DayForecasting.ipynb

Adapting the concept of forecasting passenger numbers for flights, this notebook employs Long Short-Term Memory (LSTM) Networks to predict project volatility over time. Utilizing PyTorch for deep learning, the model forecasts the last 12 days of project volatility with a 93% accuracy rate, based on historical data trends. The ultimate goal is to refine and enhance these predictive capabilities, integrating them into project management tools to aid in early identification of potential issues, thereby saving significant resources and improving project outcomes.

## Objectives

- To explore and apply data science and machine learning methodologies in the context of project management.
- To develop predictive models capable of forecasting project outcomes and volatility with high accuracy.
- To demonstrate the potential of integrating machine learning algorithms into project management practices for better decision-making and resource allocation.

## Potential Impact

The insights and models developed through the PPMO-Data-Science project have the potential to revolutionize project management by:
- Allowing project managers to anticipate and mitigate risks more effectively.
- Enhancing the accuracy of project planning and forecasting.
- Saving significant time and resources through the early identification of potential project roadblocks.

## Future Directions

As we continue to refine our models and methodologies, future iterations of the project will focus on:
- Expanding the dataset to include a wider range of project types and management scenarios.
- Improving the models' accuracy and reliability through advanced machine learning techniques.
- Exploring the integration of these models into existing project management software platforms.

We welcome contributions, insights, and collaborations from the data science and project management communities to further the objectives of this innovative project.
