# Uber Data Analysis
UC Davis Data Analytics Bootcamp Final Project
![](images/dataset-cover.jpeg)
## Presentation 
link to the Google Slides & Tableau

## Topic - Uber Analysis
Our group decided to work and analyze an Uber Driver Data. The Dataset emcompasses of different trip purposes all over the world in 2016. 

## Discription
For our analysis we've decided to to detemine what places & purpose were the most popular to visit, how many miles has been driven from Start to Stop locations, how much money the driver made each trip and in total for each month or in general. 
The dataset was obtained from Kaggle.com https://www.kaggle.com/datasets/zusmani/uberdrives

## Questions We Would Like to Answer:
* What is the most productive day of the week?
* How much the most money the driver made in day, week, month, and in total?
* What is the most popular place where people order Uber the most?
* How many miles the driver drove according to the duration column? Where the most and how long it took?
*
To answer the questions above we've decided to use Tableau for graph visualization.


## Description of the data exploration phase of the project
In order to understand what statistics were available within the dataset, as well as identifying which values would be ideal for the Machine Learning model. After the dataset was downloaded from our source, the team used Excel initially, to skim through the dataset and identify which characteristics of the dataset were preferred as well as locating null values to clean up the data, it was done through Jupyter Notebook. 
At first the dataset were contains only columns below:
7 columns and around 1000+ rows
* Start Date
* End Date
* Category
* Start 
* Stop
* Miles
* Purpose
![](https://user-images.githubusercontent.com/101672943/184781586-aacfd40a-d975-4afc-a7f2-07e0ec2bd5f4.png)

## Description of the analysis phase of the project
Final dataset encompassed  16 columns 571 rows 
The remaining columns are:
* Start Date
* End Date
* Category
* Start
* Latitude
* longitude
* Stop
* Latitutude
* Longitude
* Miles 
* Purpose
* $Salary$
* Month
* Day of the week
* Duration
* money - regex
![](https://user-images.githubusercontent.com/101672943/184781603-4beb716d-05ca-4438-82f2-8f7d34102eaa.png)


## Technologies Used
### Source Control
 Git Hub will be as the main code hoting platform, where we contributed with our work, store final files, share the work, and submit the work for all 4 segments in the final for the grading team. 
### Analysis and Clean up
 Excel will be used as an overview of the data, the first step of our analyzing phase, and also in the conclusive context of our analysis. Pandas will be used to clean our data and perform the analysis by our team. Jupyter Notebook and Python plays a very important role in our analysis, because the further work will conduct our analysis and coding to obtain our goal.
### Dashboard
 The final visualization and presentation will integrate by Tableau public for for a fully functioning interactive understanding for the analysis with interactive story and dashboard. In conclusion, Google Slides will be used for presentation in class.
### Additional helpful tools were used:
 - Aws
 - PostgreSQL
 - pgAdmin


 ## Machine Learning Model ?


## Encountered Issues/Solutions
* Before coding with data, salary column were added manually to excel file as: Miles multiply by $2.15 the reason for that because in 2016 NY Uber drivers got paid $2.15 per mile.
* Longitude and Latitude for Start and Stop locations were also added manually with Googleslide extension called "Geocoding with Awesome Table"

![](https://user-images.githubusercontent.com/101672943/184781711-4fd190d9-5700-4917-9485-1f756dc0fc00.png) ![](https://user-images.githubusercontent.com/101672943/184781766-1e5ff80e-c676-44bd-a1c7-1e08d31961e8.png)


Columns: Month, Day of the week, Duration, and money_regex were produced with the knowledge we learned from the modules in Jupyter Notebook.

## Team Roles (in our case #team of three)
![](https://user-images.githubusercontent.com/101672943/184782005-7eb146a1-a494-4891-98c1-680971e72bad.png)

* Square
* Triangle 
* Circle
* X
description for each segment (who did what) 

Update the files
https://public.tableau.com/app/profile/harprit2887/viz/Uber_ride_2016/Story1?publish=yes

https://public.tableau.com/app/profile/harprit2887/viz/Uber_Ride_2016Dashboard/Dashboard1?publish=yes

[Uber_Ride_2016.pptx](https://github.com/markpalkovskyi/Final_project/files/9306681/Uber_Ride_2016.pptx)


# Analysis Result:
can be a finish part of the readme file. 

