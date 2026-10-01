Airbnb Pricing & Tourism Analysis in Seville
Introduction
This project analyzes Airbnb listings in Seville, Spain, to understand how different property characteristics are related to Airbnb prices.

The project focuses on four main factors: neighborhood, room type, accommodation capacity, and availability.

The main research question is:

How do location, property characteristics, and availability relate to Airbnb prices in Seville?

The results could help Airbnb hosts and property managers understand pricing patterns in the Seville market.

Data Sources
1. Inside Airbnb
The main dataset contains Airbnb listing information for Seville, including:

Neighborhood
Room type
Price
Number of guests accommodated
Availability
Source: Inside Airbnb

2. Weatherbit API
Weather data was collected using the Weatherbit API.

The dataset contains daily weather information for Seville, including:

Temperature
Maximum temperature
Minimum temperature
Precipitation
The weather data is used as an additional contextual data source for the project.

Research Questions and Hypotheses
Research Question
How do location, property characteristics, and availability relate to Airbnb prices in Seville?

Hypotheses
H1: Average Airbnb prices differ between neighborhoods.

H2: Entire homes/apartments tend to have higher prices than private or shared rooms.

H3: Listings that accommodate more guests tend to have higher prices.

H4: Airbnb prices differ according to the level of annual availability.

Methodology
The project follows these main steps:

Collect Airbnb data from Inside Airbnb.
Collect weather data using the Weatherbit API.
Inspect and clean the datasets.
Convert price values into numerical data.
Remove listings without valid prices.
Explore the main variables using descriptive statistics.
Compare average prices across neighborhoods and room types.
Analyze the relationship between accommodation capacity and price.
Compare prices across availability levels.
Create visualizations to support the analysis.
Python libraries used include:

pandas
matplotlib
requests
Data Cleaning
The Airbnb dataset was cleaned by:

Removing completely empty columns.
Converting price values into numerical values.
Removing listings with missing prices.
Checking the structure and values of the main variables.
Preparing the data for analysis.
After cleaning, 7,644 Airbnb listings with valid prices were available for the main analysis.

Main Findings
Neighborhood
Average Airbnb prices vary across Seville neighborhoods. For example, among neighborhoods with at least 10 listings, El Porvenir and Triana Oeste had relatively high average prices.

Room Type
Room type shows clear differences in average price.

Room Type	Average Price
Hotel room	€162.97
Entire home/apt	€157.95
Private room	€94.56
Shared room	€31.21
Entire homes/apartments represent the largest group in the dataset, with 6,666 listings.

Accommodation Capacity
There is a general increase in average price as the number of guests that a property can accommodate increases.

Availability
Average prices also differ between availability levels, but the pattern is not perfectly linear.

Availability	Average Price
Low	€156.72
Medium-low	€131.61
Medium-high	€148.31
High	€163.23
Conclusions
The analysis suggests that neighborhood, room type, and accommodation capacity are important factors associated with Airbnb prices in Seville.

Availability also shows differences in average price, although the relationship is less clear.

Overall, the project demonstrates how data wrangling and exploratory data analysis can be used to identify pricing patterns in the Airbnb market.

Further Questions and Next Steps
Possible extensions of the project include:

Analyze the relationship between reviews and price.
Study the effect of minimum nights on price.
Analyze price differences between property types.
Collect weather data for a longer period.
Include additional tourism or seasonal data.
Build a simple model to predict Airbnb prices.
Project Structure
data-wrangling-project/
│
├── README.md
├── notebooks/
│   └── airbnb_sevilla_analysis.ipynb
│
├── data/
│   ├── raw/
│   └── cleaned/
│
├── images/
│
└── presentation/
Links
Inside Airbnb: https://insideairbnb.com/
Weatherbit API: https://www.weatherbit.io/api
Kanban Board: [Add your Trello link here]
Presentation: [Add your presentation link here]
