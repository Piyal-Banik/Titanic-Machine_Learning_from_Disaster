
# Titanic-Machine_Learning_from_Disaster

Use machine learning to create a model that predicts which passengers survived the Titanic shipwreck.



## Author

- [Piyal Banik](https://twitter.com/PiyalBanik)

  Created on 24th July, 2021
## Acknowledgements

 - [Competition on Kaggle](https://www.kaggle.com/c/titanic/overview)
 - [Data Science Methodology](https://www.coursera.org/learn/data-science-methodology)

## Project Pipeline

- Business Understanding
- Analytical Approach
- Data requirements
- Data collection
- Data Understanding
- Data Preparation
- Modeling
- Evaluation


  
## Libraries used

- Numpy
- Pandas
- Seaborn
- Sickit-Learn 

```bash
  pip install numpy, pandas, seaborn, sklearn
```
    

## Business Understanding

The sinking of the Titanic is one of the most infamous shipwrecks in history.

On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.

While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

The challenge here is - Given a passenger's information, how can we predict whether he/she survived the Titanic disaster?

## Analytical Approach

Our target variable is categorical (survived / not survived), and hence we need classification models for this task.


## Data requirements

We would require onboard passengers information which might include name, age, fare, gender, class.


## Data collection

We are given two datasets both of which are CSV files, one for training our model named as train.csv and the other test.csv to test if our model can determine survival based on observations, not having the survival info. 

## Data Understanding

This step is part of Exploratory Data Analysis

We started off finding out the