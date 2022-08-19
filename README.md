# Uber Data Analysis
UC Davis Data Analytics Bootcamp (March-August 2022) Final Project - Mark, Michael, Harprit, CJ
![](images/dataset-cover.jpeg)
## Presentation 
Links:

Google Slides - https://docs.google.com/presentation/d/1OSwmpJTQrGlFNN5hsci9FMY1SfDhgS8z2IwIocx5NlE/edit?usp=sharing

Tableau - [https://public.tableau.com/app/profile/mark3073](https://public.tableau.com/app/profile/mark3073/viz/Uber_Ride_2016/Dashboard2)

## Topic - Uber Analysis
Our group decided to work and analyze an Uber Driver Data. The Dataset emcompasses of different trip purposes all over the world in 2016. 

## Description
For our analysis we've decided to to detemine what places & purpose were the most popular to visit, how many miles has been driven from Start to Stop locations, how much money the driver made each trip and in total for each month or in general. 
The dataset was obtained from Kaggle.com https://www.kaggle.com/datasets/zusmani/uberdrives

## Questions We Would Like to Answer:
* What is the most productive day of the week?
* How much the most money the driver made in day, week, month, and in total?
* What is the most popular place where people order Uber the most?
* How many miles the driver drove according to the duration column? Where the most and how long it took?



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
### Additional tools were used:
 - Aws
 - PostgreSQL
 - pgAdmin

 ## Dashboard
 1. Storyboard for Dashboard
  * The location of the starting point, where the driver left from, and how many times the driver dropped off passengers around the same location        according to our data for the whole year?
  * Purpose of destination, where people had to go the most. Was it more personal or bussiness route?
  * How much did the driver made each month and what was the most profitable month of the year of 2016?
  * What is the total trips did the driver made for the whole year?

![](https://user-images.githubusercontent.com/101672943/185249302-63e812ab-2f8a-4dfb-a633-f7ac9173bd01.png)
![](https://user-images.githubusercontent.com/101672943/185249553-123e6a6f-268c-47d6-91ba-42aa9c4dc67b.png)
 
 2. The main tool used to create the final dashboard for the presentation will be Tableau. Within Tableau, we will use interactive bar charts, pie charts, maps, and tables.
 3. With our Tableau link, viewers can visit the URL and inspect on their own about specific graph, that way visitors can learn more about our Uber Data analysis.


## Encountered Issues/Solutions
* Before coding with data, salary column were added manually to excel file as: Miles multiply by $2.15 the reason for that because in 2016 NY Uber drivers got paid $2.15 per mile.
* Longitude and Latitude for Start and Stop locations were also added manually with Googleslide extension called "Geocoding with Awesome Table"

![](https://user-images.githubusercontent.com/101672943/184781711-4fd190d9-5700-4917-9485-1f756dc0fc00.png) ![](https://user-images.githubusercontent.com/101672943/184781766-1e5ff80e-c676-44bd-a1c7-1e08d31961e8.png)


Columns: Month, Day of the week, Duration, and money_regex were produced with the knowledge we learned from the modules in Jupyter Notebook.

## Team Roles (team of three)
![](https://user-images.githubusercontent.com/101672943/184782005-7eb146a1-a494-4891-98c1-680971e72bad.png)

Segment 1

[]Square (Mark)
* setting up the repository
* responsible for branches

()Circle (Michael)
* in charge of the mockup database
* SQL-based database

/\Triangle
* creating a simple machine learning model
* help team understand how a machine learning model will fit into the project

X (Harprit)
* responsible for how will the dashboard be built?
* which technology is being used where

Segment 2

[]Square 
* focus on the machine learning model
* continue to refine, train, and test the model
* Make sure to document how it ties into the project

/\Triangle (Mark)
* upscaling the project's database

() Circle (Michael)
* continue to refine the analysis
* generates images to use in the presentation and with the dashboard

X (Harprit)
* focus on the team's dashboard that will be used to display your data findings
description for each segment (who did what) 

Segment 3

[]Square (Mark)
* Finish up peer reviews and check code
* Merge in branches that are still open, or close others.
* Make sure the repository is ready for public viewing
Update the files

/\Triangle (Harprit)
* Project topic and reason it was selected
* Description of your data and where it was sourced
* Questions you intend to answer with the data
* Description of the data exploration your team conducted

()Circle (Michael)
* storyboard
* final presentation

X 
* Tester of All Things
* final round of code testing
* checks for the weaknesses and loopholes

Segment 4

[]Square (Mark)
* finalize the README in the project repository

/\Triangle 
* final touches on the dashboard and presentation
* Coordinate practices between team members and practice the presentation and dashboard

()Circle (Michael)
* ensure all applicable PRs are merged in and completed

X
* assistance with the presentation, dashboard, finishing up with the repository or an extra pair of hands.


Final Tableau - [https://public.tableau.com/app/profile/mark3073](https://public.tableau.com/app/profile/mark3073/viz/Uber_Ride_2016/Dashboard2)

https://public.tableau.com/app/profile/harprit2887/viz/Uber_ride_2016/Story1?publish=yes

https://public.tableau.com/app/profile/harprit2887/viz/Uber_Ride_2016Dashboard/Dashboard1?publish=yes

[Uber_Ride_2016.pptx](https://github.com/markpalkovskyi/Final_project/files/9306681/Uber_Ride_2016.pptx)




