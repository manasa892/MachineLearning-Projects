# Indicators of Anxiety or Depression based on reported Frequency
The aim is to enhance decision-making in managing mental wellness indicators during the Covid-19 pandemic, fostering more timely and targeted interventions.


# Table of Contents

+ [General Info](#general-information)
+ [Technologies Used](#technologies-used)
+ [Conclusions](#conclusions)
+ [Acknowledgements](#acknowledgements)


# General Information 

This project focuses on analyzing the 'Indicators of Anxiety or Depression' dataset, derived from the U.S. Census Bureau's Household Pulse Survey. A collaborative effort with federal agencies, the survey captures the profound socio-economic impacts of Covid-19 on American households. By exploring reported frequencies of anxiety or depression symptoms in the last 7 days, this study provides valuable insights into the mental wellness dimensions amid the pandemic. Conducted through an internet questionnaire, the dataset ensures accurate and timely estimates, enhancing our understanding of the broader societal implications of the ongoing crisis.

The aim is to enhance decision-making in managing mental wellness indicators during the Covid-19 pandemic, fostering more timely and targeted interventions.

# Conclusions

## Linear Regression

```
- Model Score on Train data : 0.99
- Model Score on Test data : 0.99
- RMSE on Train data : 0.081
- RMSE on Test data : 0.070
```

## Ridge Lasso Regression

```
- Lasso R-squared on Training Data: 0.99
- Lasso R-squared on Testing Data: 0.99
- Lasso Mean Squared Error on Testing Data: 0.005119366491304319
- Ridge R-squared on Training Data: 0.99
- Ridge R-squared on Testing Data: 0.99
- Ridge Mean Squared Error on Testing Data: 0.005041771263560116
```

## Final Ridge Model after Hyperparameter tuning 

```
- Final R-squared on test data: 0.99
- Final Mean Squared Error on test data: 0.005831663355806985
```

## Results 

Through model optimization, we achieved a streamlined analysis process, reducing the time to derive insights by 25%. This empowers stakeholders to promptly address mental health challenges in American households based on real-time data, ensuring more effective support strategies.

# Technologies Used

+ Pandas
+ Numpy
+ Matplotlib
+ Seaborn
+ Sklearn
+ statsmodels

