Bike Sharing Assignment
This project involves building a multiple linear regression model to predict the demand for shared bikes for BoomBikes, a US bike-sharing provider.

Table of Contents
General Info

Technologies Used

Conclusions

Acknowledgements

General Information
Project Background: BoomBikes has suffered revenue dips due to the pandemic and seeks a business plan to accelerate revenue once the economy restores.

Business Problem: The objective is to identify which variables are significant in predicting bike demand and how well those variables describe the demand levels.

Dataset: The dataset day.csv contains daily records of bike rentals in the US for the years 2018 and 2019, including weather and seasonal attributes.

Conclusions
Significant Predictors: The year (yr), temperature (temp), and weather situations (specifically Light Snow or Mist) are the most significant factors affecting bike demand.

Yearly Growth: There was a substantial increase in bike rentals from 2018 to 2019, suggesting growing popularity before pandemic disruptions.

Weather Impact: Demand is negatively impacted by high humidity and wind speed, and significantly drops during adverse weather like light snow or rain.

Model Performance: The final model achieved an R-squared score of approximately 0.81 on the test set, indicating it explains 81% of the variance in bike demand.

Technologies Used
Python - Version 3.x

Pandas - For data manipulation

Seaborn & Matplotlib - For data visualization

Scikit-learn - For model building and scaling

Statsmodels - For detailed statistical analysis and VIF calculation

Acknowledgements
This project was inspired by the Linear Regression module in the AI/ML curriculum.

Data provided by BoomBikes.