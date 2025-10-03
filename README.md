# ML-CustomerChurn

### Introduction

This is an R machine learning project that I originally completed for my DA5030 Machine learning course. 

Insights into customer behavior and their experience may be valuable for companies to understand how they can retain their customers and keep them satisfied. The project aims to predict customer churn as the target variable in the [Iranian Churn dataset](https://archive.ics.uci.edu/dataset/563/iranian+churn+dataset) by training various different metrics of customer satisfaction on 3 different classification models:

- KNN
- Logistic Regression
- Random Forest

The final deliverables were an .Rmd file and a final knitted HTML report, both of which document the process I used to train my models and compare them. After the creation of an ensemble model, model evaluation was done through the use of confusion matrices, and various different metrics such as accuracy, precision, recall...etc.

### Technologies used 

This project was coded in Rstudio with the use of the R programming language. 

#### R libraries:
- caret  
- dplyr
- ggplot2 
-  ROSE
-  psych
-  stats

#### How to run 

If you need to only view the finished report:
1. First, download or clone this repository.
2. Open the HTML file to read or understand the finished report.

If it is necessary to reproduce my workflow for any reason or take a deeper look at my code, feel free to:
1. Navigate to the .Rmd file.
2. To execute the code, under the "Run" button in the source pane, click "Run all" if you want to execute all of the code
3. Alternatively, click on the "Knit" button in the source pane to generate your own finished HTML report. 

#### Roadmap

I am currently under the process of improving this project, here are some changes nessecary that I am going through to make this a polished product.

- [ ] Tweak and fix bugs in my Ensemble model so it works properly.
- [ ] Incorporate the use of "bagging" methods for KNN and logistic regression to improve overall model fit. 
