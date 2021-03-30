# Smartphone Activity Recognition
> Machine learning approach to classification of human activities and postural transitions based on smartphone accelerometer and gyroscope data. 

## Table of contents
* [General info](#general-info)
* [Screenshots](#screenshots)
* [Technologies](#technologies)
* [Setup](#setup)
* [Features](#features)
* [Status](#status)
* [Inspiration](#inspiration)
* [Contact](#contact)

## General info
The goal of this project is to classify the static postures and dynamic activities of people performing basic activities using smartphone accelerometer and gyroscope data.  The static postures include standing, sitting and lying while the dynamic activities include walking, walking upstairs and walking downstairs.  There are also postural transitions between the static postures

## Screenshots
![Bagged Trees Results](./img/BaggedTrees_results.png)
![KNNR Results](./img/KNNR_results.png)
![Random Forests Results](./img/RandomForests_results.png)
![Sales Outlet Location](./img/Sales_OutletLocationType.png)
![Sales Outlet Size](./img/Sales_OutletSize.png)
![Sales Outlet Type](./img/Sales_OutletType.png)
![Feature Correlation](./img/feature_corr.png)


## Technologies
* Python 3.9.0 as development language
* Sci-Kit Learn 0.23.2 for modeling
* Models - K Nearest Neighbors Regressor, Bagged Trees Regressor, Random Forests Regressor

## Setup
Setup environment by importing pandas, numpy and the sci-kit learn models mentioned in the Technologies section

## Code Examples
See project1-partX notebooks

## Features
Regression Models predict item outlet sales with approximately $800 mean absolute error
* KNNR MAE: $787
* Bagged Trees MAE: $801
* Random Forests MAE: $802  
  
Features that most affect Item Outlet Sales
* Item MRP
* Outlet Type
* Outlet Size 
* Outlet Location Type

To-do list:
* Make charts and graphics ready for print
* tune model hyperparameters if desired

## Status
Project is: _finished_, Moving onto the next project.

## Inspiration
As always, the good people in my coding community who provide guidance and wisdom as I take on more projects to develop my skillset.

## Contact
Created by Kenny Bundy - feel free to contact me!