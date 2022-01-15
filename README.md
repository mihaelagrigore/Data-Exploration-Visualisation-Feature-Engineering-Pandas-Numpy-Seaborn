# Thorough Data Wrangling - Pandas, Numpy, Seaborn

This repo contains one notebook where I go thoroughly through the normal Data Wrangling process performed on any new and potentially messy data. It includes analysis of missing data, uni and bivariate analysis, removal of data that is not useful and some data engineering.

In <a href='https://github.com/mihaelagrigore/Exploratory-Data-Analysis'>another notebook</a>, I do a more basic Exploratory Data Analysis procedure. For that one I used the World Happiness Report dataset, which is quite limited - too simple and it didn't give me the chance to perform more interesting operations like imputation or feature engineering.

For a more in depth pre-processing, I am using here the popular Titanic dataset. You can see a through description of the data on the link above.

The short story is that we have a list of passengers who travelled on Titanic, for each passenger we have many features (age, sex etc) and we also know which of them survived and which did not. That is, the data is labelled and it's meant to use for classification models, for predicting the survival of passengers based on information we have about them. But, as you will see, in its original form, the data is far from being ready to be fed to ML models. In this notebook I am only preparing the data for being passed on to classification models.

<b>How to use it:</b>
Open the Jupyter Notebook in this folder. You can clone it, download it or just read it here. There is also a link at the top of the Notebook which takes you to the same Notebook on Kaggle.

What this notebook contains: 

    Getting familiar with our data
    Univariate analysis
    Data engineering
    Missing data
    Bivariate visualizations
    Examining survival rates for different feature values
    Removing unnecessary data
    Encoding categorical variables
