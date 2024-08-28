# Bike Sharing Case Study

## Table of Contents
* [General Info](#general-information)
* [Libraries Used](#libraries-used)
* [Reading and Understanding the Data](#reading-and-understading-data)
* [Data Cleaning](#data-cleaning)
* [Standardizing Data](#standardizing-data)
* [Visualizing Data](#visualizing-data)
* [Data Preparation](#data-preparation)
* [Model Building](#model-building)
* [Residual Analysis](#residual-analysis)
* [Model Evaluation](#model-evaluation)
* [Conclusion](#conclusion)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
<b>Problem Statement:</b> <br>
A US bike-sharing provider **BoomBikes** has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. <br><br>
In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

<b>Goal of this project</b> <br>
Goal of this project is to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations.

## Libraries Used                                                                                                                  
* NumPy: For numerical computations.
* Pandas: For data manipulation and analysis.
* Matplotlib: For creating visualizations.
* Seaborn: For statistical data visualization.
* Calendar: For date functions
* Warnings: To suppress warning messages.
* sklearn: Multiple functions to building model using liner regression
* statsmodels: For statistical computations.

## Reading and Understanding the Data
* Read data set 'day.csv' into a dataframe named 'bikes'

## Data cleaning
* Drop irrelevant columns
* Check for outliers

## Standardizing Data
* Rename columns to improve readability
* Replace categorical data values based on dictionary provided

## Visualizing Data
* Visualizing Numerical & Continuous Data
* Visualizing Categorical Data

## Data Preparation
* Dummy Variables
* Correlation Analysis

## Model Building
* Splitting the Data into Training and Testing Sets
* Dividing into X and y sets for model building
* Feature selection (using RFE)
* Building model using statsmodel, for the detailed statistics
* Multicollinearity checks

## Residual Analysis
* Predict using model built
* Error Terms
* Train Vs Predicated
* R2 for train

## Model Evaluation
* Predict using model built
* Error Terms
* Test Vs Predicated
* R2 for test



## Conclusion

* **Model built with <span style="color: BlueViolet;">Train R²</span> <span style="color: blue;">83.1%</span> and <span style="color: BlueViolet;">Test R² </span><span style="color: blue;">79.4%</span>**
<br><br>
* **<span style="color: BlueViolet;">Most favorable factors</span> for bike demand       : <span style="color: blue;">Year, Temperature, Summer Seaon, Winter Seaon, September Month, Sunny weather </span>**
<br><br>
* **<span style="color: BlueViolet;">Not so favorable factors</span> for bike demand : <span style="color: blue;">Holiday, Windspeed, Rainy weather </span>**

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Contact
Created by [@SomasekharGangarapu] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->