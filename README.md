# London_Bike_Sharing
## Introduction
Welcome to the London Bike Sharing Data Analysis project! This project aims to provide insightful visualizations and analysis of bike-sharing patterns in London.By examining historical data, I aim to gain a deeper understanding of these patterns as part of my exploratory data analysis (EDA) process.

To present my findings in a clear and structured manner, I will be using the STAR method, which stands for Situation, Task, Action, and Result. This method will help break down the project into manageable sections and ensure that each part of the analysis is thoroughly explained.

Here’s what you can expect:
* Situation: I’ll describe the context and background of the bike-sharing initiative in London.
* Task: I’ll outline the specific objectives and questions I aimed to address through our analysis.
* Action: I’ll detail the steps and methodologies I employed to explore the data, including the tools and techniques used.
* Result: I’ll present the key findings and insights from my analysis, supported by visualizations.

## Situation
As you know, there's been a recent push to provide free or affordable access to bicycles for short-distance trips in urban areas. This initiative offers a sustainable alternative to motorized public transport or private vehicles, aiming to cut down on traffic congestion, noise, and air pollution.

The [dataset](https://www.kaggle.com/datasets/hmavrodiev/london-bike-sharing-dataset/data) I am using for this analysis is sourced from Kaggle and contains detailed information on bike-sharing activities in London. It includes variables such as the count of new bike shares, real temperature, perceived temperature, humidity, wind speed, weather conditions, and indicators for holidays, weekends, and seasons.

## Task
The primary objective of this project is to perform an exploratory data analysis (EDA) on the London bike-sharing dataset to uncover key trends and patterns. Specifically, we aim to address the following questions:
* Usage Patterns: What are the daily and hourly usage patterns of bike-sharing in London? How do these patterns vary across different days of the week, holidays, and weekends?
* Weather Impact: How do weather conditions, such as temperature, humidity, and wind speed, affect bike-sharing usage?
* Seasonal Trends: Are there any noticeable seasonal trends in bike-sharing usage? How does usage vary across different seasons?
* Correlation Analysis: What are the relationships between various factors (e.g., weather, time of day, holidays) and the number of bike shares?
* Impact of Events: How do special events, such as holidays, impact bike-sharing usage compared to regular days?

## Action
In this section, I'll detail the steps and methodologies used to explore and analyze the London bike-sharing dataset. My approach involved importing the dataset, understanding and manipulating the data, performing data cleaning using Python([Notebook](https://github.com/MAhmOud-iBRahiim/London_Bike_Sharing/blob/main/Bikes.ipynb)), and conducting EDA using PowerBI.
### 1. Importing the Dataset
I began by importing the dataset directly from Kaggle using the Kaggle API. This ensured I accessed the most recent and complete version of the data available.
![Kaggle](https://github.com/MAhmOud-iBRahiim/London_Bike_Sharing/blob/main/Images/Kaggle.png)
### 2. Understanding and Manipulating the Data
Once the dataset was imported, I did an initial exploration to understand its structure and contents. This involved:

* Renaming columns to ensure they were descriptive and easy to work with.
* Mapping categorical data from integers to their actual values for better readability and interpretation.
* Handling outliers to ensure the data was clean and accurate for analysis. This step was crucial for maintaining the integrity of our analysis and avoiding skewed results.

    ![IQR](https://github.com/MAhmOud-iBRahiim/London_Bike_Sharing/blob/main/Images/IQR.png)
### 3. Saving and Importing the Dataset
After cleaning and manipulating the data, I saved the updated dataset to a CSV file. This file was then imported into Power BI using "Python Script" from Get Data.
### 4. Analyzing the Dataset Using PowerBI
With the dataset loaded into Power BI, I began the analysis by creating a variety of visualizations.I focused on:
* Daily and hourly usage patterns, analyzing how bike-sharing varied across different times and days.![hourly](https://github.com/MAhmOud-iBRahiim/London_Bike_Sharing/blob/main/Images/hourly%20trend.png)![monthly](https://github.com/MAhmOud-iBRahiim/London_Bike_Sharing/blob/main/Images/Moving%20Total.png)
* The impact of weather conditions on bike-sharing usage.![Weather](https://github.com/MAhmOud-iBRahiim/London_Bike_Sharing/blob/main/Images/weather.png)
* Seasonal trends, examining how usage varies across different seasons.![Season](https://github.com/MAhmOud-iBRahiim/London_Bike_Sharing/blob/main/Images/Season.png)
* Correlations between various factors, such as temperature, Humditiy and Wind speed, and the number of bike shares(Hover over to access the scatter plot in tooltip).

    ![Temp](https://github.com/MAhmOud-iBRahiim/London_Bike_Sharing/blob/main/Images/Cor_Temp.png)
* The effect of events, like Weekends and holidays, on bike-sharing usage compared to regular days.![Holiday](https://github.com/MAhmOud-iBRahiim/London_Bike_Sharing/blob/main/Images/holidays%20rides.png)
* YoY% Growth by quarter.

     ![YOY](https://github.com/MAhmOud-iBRahiim/London_Bike_Sharing/blob/main/Images/YOY.png)

## Result
### Key Findings
#### 1. Usage Patterns:
* The usage is the highest between 7am,9am and 5-6pm. which means that people tends to cycle during the rush hours.
* Conversely in weekends and holidays usage being more evenly distributed throughout the day 12pm-6pm.
* Months like Dec, Jan and Feb have the lowest amount of booking.
#### 2. Seasonal Trends:
* People prefer better weather conditions. Usage is highest in spring and summer. While usage is very low in fall and winter.
#### 3. Weather Impact:
* Regardless of the season, Usage is highest in all seasons when the weather conditions are broken clouds, scatterd clouds and clear.
#### 4. Correlation Analysis:
* Bike usage and temperature have 39 percent positive correlation and a 48 percent negative correlation between bike usage and humidity.
* More users are renting when humidity is less, Conversely There is a uniform distribution of usage across all the temperature and wind speed.
#### 5. Impact of Events:
* It's clear that bike usage is much lower on holidays and weekends.Conversely Working days sees more usage, which tells us that going to work and coming back is one of the biggest reasons of renting!.
#### 6. Year-over-Year Growth:
* The YOY growth analysis revealed that bike-sharing usage increased significantly in Q3 and Q4 of 2016 compared to the same quarters in 2015, This indicates a growing adoption of bike-sharing services particularly in the latter half of the year.

## Recommendations
Based on our findings, we recommend the following actions to enhance the bike-sharing system in London:

1. Improve Availability During Peak Times:
    * Increase the availability of bikes and stations during morning and evening rush hours to accommodate the high demand from commuters.
2. Weather-Responsive Strategies: 
    * Implement strategies to maintain or boost bike-sharing usage during adverse weather conditions, such as offering to add a refreshement during humid weather.
3. Seasonal Promotions:
    * To encourage usage during off-peak seasons(fall and winter months), we can Launch promotional campaigns.

## Future Improvements
To further enhance the analysis process, I recommend the following future improvements:
1. Advanced Predictive Analytics:
    * Utilize machine learning models to predict bike-sharing demand based on weather forecasts, events, and historical trends.
2. User Feedback Analysis:
    * Collect and analyze user feedback to identify areas for improvement in the bike-sharing service.
3. [Dashboard](https://github.com/MAhmOud-iBRahiim/London_Bike_Sharing/blob/main/Dashborad.png) UI enhancements:
    * Work more on the dashboard design and make it more visually appealing.      
