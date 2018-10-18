# Echocardiogram
This data set used in this project contains measures of structure and function of the heart taken by echocardiogram post-heart attack. The code that you see in this repository was created by Madelyn Matura. 


## Overview of the Project ##

This project aims to identify a logistic model for predicting the probability of being alive after having a heart attack. 

HHOME's mission is to present Denison University with suggestions for how it can improve its efforts to move toward carbon neutrality. One part of our project entails modeling the extent to which scope 3 emissions contribute to Denison's annual carbon calculation. The second is to predict what changes in sustainability behavior can and will do the future of the university's annual carbon footprint. 

### Getting Started ###

##Prerequisites##

R, Rstudio, and Excell need to be installed to run this project. 

## Instalment ##

Download echocardiogram.csv file on to local machine. Open up echo
cardiogram.Rmd file using Rstudio. Set working directory in Rstudio to where the echocardiogram.csv file is located on your local machine. 

## Running the tests##

Run the R markdown file by clicking Run in the console. 

glm test: fits a logistic regression to the variables I have chosen to predit alive or dead

shapiro test and qqnorm plot: Check the normality of the data 





### Data ###
Echocardiograms are taken using high frequency sound waves in order to obtain a picture of the structure and function of a patient's heart. The data set that I used for my project was obtained from kaggle.com based on echocardiogram measurements of the structure and function of patients hearts after having a heart attack. Age and other demographic information was also recorded for each patient. Each row in the data set represents a patient. I decided to focus on specific variables in order to make a model for predicting the probability of being alive after having a heart attack. 

This data was provided by:
kaggle.com
UCI Machine Learning Reposity
Dua, D. and Karra Taniskidou, E. (2017). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science.

https://archive.ics.uci.edu/ml/datasets/echocardiogram



### Built With ###
Rstudio


### Authors ###
Madelyn Matura



### License ###
This project is licensed under MIT license. 


