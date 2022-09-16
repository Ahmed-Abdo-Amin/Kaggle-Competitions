# Spaceship Titanic

This Project is compitition of Spaceship Titanic to Predict which passengers are transported to an alternate dimension.

## Description
Welcome to the year 2912, where your data science skills are needed to solve a cosmic mystery. We've received a transmission from four lightyears away and things aren't looking good.
  The Spaceship Titanic was an interstellar passenger liner launched a month ago. 
  With almost 13,000 passengers on board, the vessel set out on its maiden voyage transporting emigrants 
  from our solar system to three newly habitable exoplanets orbiting nearby stars. 
  While rounding Alpha Centauri en route to its first destination—the torrid 55 Cancri E—the unwary Spaceship Titanic 
  collided with a spacetime anomaly hidden within a dust cloud. Sadly, it met a similar fate as its namesake from 1000 years before. 
  Though the ship stayed intact, almost half of the passengers were transported to an alternate dimension!


## Installation

Use the package manager [pip]


```bash
pip install seaborn
pip install sklearn
pip install matplotlib
pip install tensorflow
```



##  Solution (SpaceshipTitanic.ipynb)
### This contains a series of steps to predict which passengers are transported to an alternate dimension:
       1. Load data set from this link: https://www.kaggle.com/competitions/spaceship-titanic/data
       2. Extract some information and check missing values
       3. Clean this data (Check column names, handle missing values)
        4. Use Exploratory Data Analysis (EDA) visualization to describe the data by means of statistical and visualization techniques 
           in order to bring important aspects of that data into focus for further analysis.
        5. Use feature Engineering and feature selection to do preprocessing to data.
        6. Split training data into train set and test set:
            - train set is data that are used to train the model.
            - test set is data thatare used to evaluate trained model.
        7. Use Scaling on data by applying StandardScaler() function.
        8. Train and evalute the model on this data by applying Multi-Layer Perceptron Neural Network(MLP)
        9. predict test data on the trained model
        10. Put these predictions in 'sample_submission.csv' file

## Thank You
Ahmed Abdo Amin Abdo