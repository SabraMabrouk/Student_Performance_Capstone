# Student_Performance_Capstone

## Context

In Portugal, the secondary education consists of 3 years of schooling and most of the students join the public and free education system. Despite the remarkable evolution in the Portuguese population's level of education over the past decade, the country's school results still leave it lagging behind the rest of Europe. These failures are mainly critical in the basic courses of mathematics and Portuguese. Decision-makers want to analyze the factors influencing student performance and develop a strategic plan to improve results.  

## Objective
Predict students' final grades based on demographics and previous academic performance.

## Content

This repository includes Jupyter Notebook files demonstrating the different steps involved in the prediction process: 

- [Data_wrangling.ipynb](https://github.com/SabraMabrouk/Student_Performance_Capstone/blob/475cfebba773112191e90a77e470a98150b7514e/Data_wrangling.ipynb), this step focuses on collecting the data, organizing it, and making sure it's well defined, the data is also explored to better understand it.
  
- [EDA.ipynb](https://github.com/SabraMabrouk/Student_Performance_Capstone/blob/475cfebba773112191e90a77e470a98150b7514e/EDA.ipynb), the goal in this step is to explore the data and understand the relationships between the different features.
  
- [pre_processing.ipynb](https://github.com/SabraMabrouk/Student_Performance_Capstone/blob/475cfebba773112191e90a77e470a98150b7514e/pre_processing.ipynb), the main work in this notebook involves scaling the data and splitting it into test and training data sets
  
- [Modeling.ipynb](https://github.com/SabraMabrouk/Student_Performance_Capstone/blob/475cfebba773112191e90a77e470a98150b7514e/Modeling.ipynb), six models are trained including linear and tree based models. Random Forest is the selected model with a test mean absolute error of 2.14 and a test root mean squared error of 2.83.
  
  
## Data source
The datasets used in this project are available [here](https://archive.ics.uci.edu/dataset/320/student+performance) from the UCI Machine Learning Repository.



## Author
Sabra Mabrouk