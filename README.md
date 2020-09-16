<!--
*** Thanks for checking out this README Template. If you have a suggestion that would
*** make this better, please fork the repo and create a pull request or simply open
*** an issue with the tag "enhancement".
*** Thanks again! Now go create something AMAZING! :D
-->





<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->




<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="images/Coursera.png" alt="Coursera" width="400" height="102">
  </a>

  <h2 align="center">Capstone Project</h2>

  <p align="center">
    A Data Science project which explains the severity of Car Accidents and possible predictions to reduce the accidents.  
    <br />
    <a href="https://github.com/SivaPadala/Coursera_Capstone"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    
  </p>
</p>



<!-- TABLE OF CONTENTS -->
## Table of Contents

* [Introduction](#introduction)
  * [Advanced Algorithms](#advanced-algorithms)
  * [Beneficiaries](#beneficiaries)
* [Description of Data](#description-of-data)
  * [Attribute Selection](#attribute-selection)
* [Model Development](#model-development)
  * [Data Description](#data-description)
  * [Data Cleansing](#data-cleansing)
  * [Exploratory Data Analysis](#exploratory-data-analysis)
  * [Accident Severity Prediction](#accident-severity-prediction)
    * [Random Forest](#random-forest)
    * [Logistic Regression](#logistic-regression)
    * [k-Nearest Neighbours](#k-nearest-neighbours)
    * [Support Vector Machine](#support-vector-machine)
* [Results](#results)



<!-- INTRODUCTION -->
## Introduction

[![Product Name Screen Shot][product-screenshot]](https://example.com)

Road traffic accidents have always been a serious issue in modern society. According to statistical results, more than 90% of accidents have been caused by a driver’s mistake and/or fatigue. Such accidents result in loss of life and material. These are caused by the carelessness of drivers and their ignorance and negligence of traffic rules.
Approximately 1.35 million people die each year as a result of road traffic crashes.

Some of the reasons for Road Accidents:
* Over Speeding.
* Drunken Driving.
* Distractions to Driver.
* Red Light Jumping.
* Avoiding Safety Gears like Seat belts and Helmets.
* Non-adherence to lane driving and overtaking in a wrong manner.

**Road accidents are one of the most relevant causes of injuries and death worldwide, and therefore, they constitute a significant field of research on the use of advanced algorithms and techniques to analyze and predict traffic accidents and determine the most relevant elements that contribute to road accidents.**

### Advanced-algorithms
Machine Learning is the ability to train machines for the required model out put using the algorithms which function on the mathematical and statistical background.Machine learning focuses on the development of computer programs that can access data and use it learn for themselves and automates the process. Some of the important Machine Learning Algorithms.
* <a href="https://careerfoundry.com/en/blog/data-analytics/what-is-logistic-regression/" target="_blank">Logistic Regression </a>
* <a href="https://www.analyticsvidhya.com/blog/2018/03/introduction-k-neighbours-algorithm-clustering/" target="_blank">k-Nearest Neighbours</a>
* <a href="https://www.geeksforgeeks.org/decision-tree/" target="_blank">Decision Tree</a>
* <a href="https://towardsdatascience.com/support-vector-machine-introduction-to-machine-learning-algorithms-934a444fca47" target="_blank">Support Vector Machine</a>
### Beneficiaries
This project is mainly useful for people who travel by cars and other means of transport. It explains about weather and road conditions which indicates the probability of getting into accidents. So the normal people and also the Government can use this project to reduce road accidents.


<!-- DESCRIPTION OF DATA -->
## Description of Data

The data is collected from [kaggle.com](https://www.kaggle.com/ahmedlahlou/accidents-in-france-from-2005-to-2016) which contains dataset of 'Accidents in France from 2005 to 2016'. It has a total of 839986 rows which contain information about Accident details in clear format and its charecteristics. The kaggle datasets contain an extended descriptions of different aspect of the accidents, thus I've selected the most relevant and useful data for my analysis.

### Attribute Selection

The capstone project consists of [Notebook File]() which consists of information about the data attributes which are taken into consideration and the ones which are dropped from the data as they are of no use. It contains all the steps and transformations I made to the data which include data cleansing, removal of duplicate values and unwanted data. 



<!-- USAGE EXAMPLES -->
## Model Development

The data that might contribute to determining the likeliness of a potential accident occurring might include information on previous accidents such as road conditions, weather conditions, exact time and place of the accident, type of vehicles involved in the accident, information on the users involved in the accident and ofcourse the severity of the accident. This projects aims to forecast the severity of accidents with previous information that could be given by a witness informing the emergency services.

### Data Description
The dataset that resulted from the feature selection consisted in 839,985 samples, each one describing an accident and 29 different features.
These features where the following:
From the characteristics dataset: lighting, localisation, type of intersection, atmospheric conditions, type of collisions, department, time and the coordinates which are described in the Kaggle dataset here. In addition, two new features were crafted, date to perform a seasonality analysis of the accident severity and weekend indicating if the accident occurred during the weekend or not.
### Data Cleansing
The data cleaning is the process of giving a proper format to the data for its further analysis. The first step was to deal with missing values and outliers. Initially the latitude, longitude and road number were dropped form the data frame as more than a 50% of its values where NaN or 0 which is an outlier in this case.
### Exploratory Data Analysis
First, the distribution of the target's values was visualized. The plot confirmed that it is a balanced labeled dataset as the samples are divided 56-54 with more cases of lower severity. Then a seasonality analysis was performed, visualizing the global trend of daily accidents as well as the amount of accidents grouped by years, month of the year, and day of the week.
### Accident Severity Prediction
Different classification algorithms have been tuned and built for the prediction of the level of accident severity. These algorithms provided a supervised learning approach predicting with certain accuracy and computational time. These two properties have been compared in order to determine the best suited algorithm for his specific problem.

#### Random Forest
10 decision trees, maximum depth of 12 features and maximum of 8 features compared for the split.
#### Logistic Regression
c=0.001.
#### k-Nearest Neighbours
k=16
#### Support Vector Machine
size of the training set= 75,000 samples.


<!-- RESULTS -->
## Results

<!-- CONTACT -->
## Contact

Your Name - [Siva Padala](https://www.linkedin.com/in/siva-rama-reddy-padala-2ab1283) - sivapsrr1993@gmail.com

Project Link: [https://github.com/SivaPadala/Coursera_Capstone](https://github.com/SivaPadala/Coursera_Capstone)








<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=flat-square
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=flat-square
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=flat-square
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=flat-square
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=flat-square
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
