# Airbnb-Booking-Analysis---EDA
Exploratory Data Analysis of Airbnb NYC 2019 data

## Project Overview
This project involves the exploration and analysis of an Airbnb dataset containing approximately 49,000 observations and 16 columns. The dataset is a mix of categorical and numeric values, and the analysis aims to uncover key insights that can aid in various business decisions. These insights can be used to enhance security, guide marketing strategies, improve customer and host experiences, and support the implementation of innovative services on the platform.

## Business Context
Since its inception in 2008, Airbnb has revolutionized the way people travel, offering unique and personalized experiences around the world. With millions of listings available globally, data analysis has become a critical tool for understanding customer and host behavior, driving business decisions, and ensuring the platform's continued growth and security.

This project focuses on analyzing Airbnb listing data to uncover trends and patterns that can inform business strategies, optimize operations, and enhance the overall experience for both guests and hosts.

## Dataset Description
The dataset used in this project includes the following fields:

- **id**: Unique identifier for the listing
- **name**: Name of the listing
- **host_id**: Unique identifier for the host
- **host_name**: Name of the host
- **neighbourhood_group**: Location of the listing (broader area)
- **neighbourhood**: Specific area within the broader location
- **latitude**: Latitude coordinate of the listing
- **longitude**: Longitude coordinate of the listing
- **room_type**: Type of listing (e.g., entire home/apt, private room, shared room)
- **price**: Price of the listing per night
- **minimum_nights**: Minimum number of nights required for booking
- **number_of_reviews**: Total number of reviews received by the listing
- **last_review**: Date of the last review

## Libraries Used
The following Python libraries are used for data analysis and visualization:

- **Pandas**: For data manipulation, aggregation, and cleaning.
- **NumPy**: For efficient numerical operations and calculations.
- **Matplotlib**: For creating static visualizations of the data.
- **Seaborn**: For creating more advanced and aesthetically pleasing visualizations.

## Analysis and Visualizations
The project includes a thorough exploratory data analysis (EDA) to identify patterns, trends, and outliers within the dataset. At least five different visualizations are used to understand the distribution of data, correlations between variables, and behavior concerning the target variable (e.g., price or number of reviews). These visualizations may include:

- **Histograms**: To understand the distribution of continuous variables like price and minimum nights.
- **Bar Charts**: To analyze categorical data, such as room type and neighborhood.
- **Scatter Plots**: To explore relationships between numerical variables, like price and number of reviews.
- **Heatmaps**: To visualize correlations between multiple variables.
- **Box Plots**: To identify outliers and understand the spread of data.

## Objectives
The main objectives of this project are to:

1. Understand the key factors that influence pricing and customer behavior on Airbnb.
2. Identify popular neighborhoods and room types that are in high demand.
3. Provide actionable insights that can be used to enhance Airbnb’s marketing strategies, improve customer satisfaction, and optimize host performance.
4. Highlight any potential security concerns or risks based on the data.
