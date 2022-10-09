# Exploratory Data Analysis

**By**: Ensun Pak, Stephen Louie and Abhradeep Mukherjee

![1*0rbJLYbPrY7s0M0m86sV3Q](https://user-images.githubusercontent.com/109040294/194748553-7c3d737c-53fa-4b71-84c0-9f8177c993ca.png)

## Introduction
This repository contains our final group presentation for our MSDS 610: Communication for Analytics course, where we are explaining EDA. Along the way we'll realize how important EDA is and why Data Scientists should spend a good amount of time in EDA. For a shorter version you can alsp check out this [repository](https://github.com/Abhradeep1994/msds610-EDApresentation) 

## Objective 
The objective of this presentation is to show the importance of Exploratory Data Analysis with a real life scenario. We'll also cover certain key concepts of EDA on the way.

## Importance of EDA
Exploratory Data Analysis helps us to –
· To give insight into a data set.
· Understand the underlying structure.
· Extract important parameters and relationships that hold between them.
· Test underlying assumption

The figure below shows the process flow from data collection to decision making which is generally done in any data oriented work:

<img width="1440" alt="Screen Shot 2022-10-09 at 1 00 04 AM" src="https://user-images.githubusercontent.com/109040294/194744960-7665d214-4ff1-473f-97a4-781bd6fc690a.png">

## Type of EDA
Generally, EDA falls into two categories:
- **univariate analysis** involves analyzing one feature, such as summarizing and finding the feature patterns.
- **multivariate analysis** technique shows the relationship between two or more features using cross-tabulation or statistic

<img width="1307" alt="Screen Shot 2022-10-09 at 1 04 47 AM" src="https://user-images.githubusercontent.com/109040294/194745214-b52b5b1c-587e-41a3-a9f2-53ab00773231.png">

## Important Definitions
Before we delve into the intricacies of EDA there are a few things that we should be aware of. This document will give you enough information to get your hands dirty with data. 

### Data Types 
![8UUywzzaMhY2ZGHrWE7VkA_b](https://user-images.githubusercontent.com/109040294/194746289-ac2ba7cc-3752-4c0c-9cee-ebc31d075a19.png)
Having a good understanding of the different data types, also called measurement scales, is a crucial prerequisite for doing EDA, since you can use certain statistical analysis only for specific data types. We also need to know which data type we are dealing with to choose the right visualization method. 

### Data Visualization 
![1*-YU12wkvW90UYQteYx9LxA](https://user-images.githubusercontent.com/109040294/194748141-c1937f94-10f7-493f-bf92-ec9b8815fbea.png)
Data visualization is the practice of translating information into a visual context, such as a map or graph, to make data easier for the human brain to understand and pull insights from. Data visualization provides a quick and effective way to communicate information in a universal manner using visual information.

Below are the most important data visualizations that every data science professional must know:
- Bar Chart - Bar charts are used to represent categorical data with rectangular bars where the height or length of each bar is directly proportional to the value it represents.
- Histograms - Histograms are used to visualize the distribution of the data. 
- Heatmaps - Heatmaps are one of the best data visualizations used to understand the correlation between characteristics of a dataset. 
- Scatter Plot - Scatter plots are one of the most common ways to analyze multidimensional data. A scatter plot is very commonly used to analyze the relationships between two entities. 
- Line Plot - A line plot is a graph that displays data using a number line

### Important Statistical Measures
In descriptive statistics, summary statistics are used to summarize a set of observations, in order to communicate the largest amount of information as simply as possible. Statisticians commonly try to describe the observations in

- a measure of location, or central tendency, such as the arithmetic mean
- a measure of statistical dispersion like the standard mean absolute deviation
- a measure of the shape of the distribution like skewness or kurtosis
- if more than one variable is measured, a measure of statistical dependence such as a correlation coefficient
![250705 image0](https://user-images.githubusercontent.com/109040294/194747157-4ebd2250-e1cb-43f1-8af9-1c9e73f3d8ef.jpeg)

## Important Steps for EDA

### Missing Values
Missing values in our dataset can cause major roadblocks in reaching our end goal. Therefore we should identify them and treat them so that we have a uniform dataset which can be used for the next steps:
The standard ways of treating missing values are:
- Either filling up the missing values with a statistical measure(depends on the scenario)
- If they are less in number, drop them

### Identifying and converting to the right data types
Since data-types of columns determine the kind of analysis and plots we can do, it's a crucial step to make sure we convert and have the right data types for our data. 

### Calculating Summary Statistics
Using the statistical measures we have defined above we can calculate the summary statistics which will give us a better understanding of our data. We can also understand if our statistical measures are impacted by the presence of outliers. (** Outliers** : They are those data points which are not following the general rule or pattern that we see in our data) 

### Creating plots for visualization
Finally we create plots using the data we have prepared to visualize and draw better insights for the next steps(modelling, reporting, etc)

## Technical Specifications
Now that we have fair bit of idea, let's get to know how we can incorporate the above steps in our data. We will be using Python(3.9) as our primary language but we can also other languages like R to get these details:

### Important Python Libraries
- **Pandas** - Pandas is used for everything related to data-cleaning and data wrangling
- **Numpy** - Numpy is used for performing all numerical  operations on our data
- **Matplotlib** - Matplotlib is a visualization library which we use to create plots and charts. There are other libraries as well like **Plotly** and **seaborn** but both use matplotlib as their base library.

To use this notebook you need to run the following command:
```
git clone https://github.com/Abhradeep1994/msds610-EDAfinalpresentation.git
```
