# Vehicle Dataset Analysis

## Project Overview

This project focuses on data cleaning, feature engineering, and exploratory data analysis (EDA) for a vehicle dataset. The goal is to identify key insights about vehicle pricing, fuel efficiency, and performance based on various attributes such as engine horsepower, market category, and drivetrain type.

## Dataset Information

The dataset includes the following key columns:

Make, Model, Year – Basic vehicle details

Engine HP, Engine Cylinders – Performance metrics

Driven Wheels, Transmission Type – Vehicle drivetrain information

Market Category, Vehicle Size, Vehicle Style – Classification of vehicles

City MPG, Highway MPG – Fuel efficiency metrics

MSRP – Manufacturer’s suggested retail price

Popularity – Popularity score of the vehicle

## Data Processing Steps

### Data Cleaning

Handled missing values by filling them with appropriate values (e.g., median for numerical columns, mode for categorical columns).

Converted data types to ensure consistency.

Filtered the dataset to only include vehicles from 1995 and later.

Standardized text entries to lowercase for consistency.

### Feature Engineering

Created Total MPG as the average of city mpg and highway MPG.

Calculated Price per HP as MSRP / Engine HP.

### Exploratory Data Analysis (EDA)

Descriptive statistics: Mean, median, and standard deviation for key numerical columns.

Grouping analysis: Computed average MSRP and Popularity based on Driven Wheels, Vehicle Size, and Engine Cylinders.

#### Visualizations:

Histogram for city MPG distribution.

Bar chart showing average MSRP by Vehicle Size.

Scatter plot for Engine HP vs. MSRP.

Boxplot illustrating MSRP distribution by Driven Wheels.

Line plot showing trends in fuel efficiency across Transmission Types.

Correlation analysis: Investigated relationships between Engine HP, MSRP, Popularity, city MPG, and highway MPG.

## Key Insights & Findings

Vehicles with higher Engine HP generally have higher MSRP, confirming a positive correlation.

AWD and 4WD vehicles tend to have a higher median price compared to FWD and RWD models.

Manual transmissions tend to offer slightly better fuel efficiency compared to automatics.

There is a moderate negative correlation between Engine HP and fuel efficiency (MPG), indicating that more powerful vehicles consume more fuel.
