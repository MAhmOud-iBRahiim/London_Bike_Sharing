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

The [dataset](https://www.kaggle.com/datasets/hmavrodiev/london-bike-sharing-dataset/data) we are using for this analysis is sourced from Kaggle and contains detailed information on bike-sharing activities in London. It includes variables such as the count of new bike shares, real temperature, perceived temperature, humidity, wind speed, weather conditions, and indicators for holidays, weekends, and seasons.

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

## Result
### Key Findings
#### 1. Usage Patterns:
*
*
#### 2.Weather Impact:
*
*
#### 3.Seasonal Trends:
*
*
#### 4.Correlation Analysis:
*
*
#### 5.Impact of Events:
*
*

