# Airbnb Investment Analysis Dashboard (Tableau)

## Project Overview

This project focuses on building a Tableau dashboard to support an investment decision for a potential Airbnb host. The stakeholder’s goal is to determine which locations are the most profitable areas to purchase property and operate an Airbnb business.

Using Airbnb listing and calendar data, the dashboard visualizes pricing, seasonality, property size, and market competition to help identify high-revenue opportunities.

## Objective

The objective of this project is to answer the following business questions:

- Which areas have the most expensive Airbnb listings?
- When is the best time of year to rent out a property?
- How does the number of bedrooms affect pricing?
- How much competition exists in each area?

These insights help investors decide where to buy a property and how to maximize profit from short-term rentals.

## Tools Used
- Tableau – Data visualization and dashboard creation  
- Airbnb Dataset

## Data Visualizations

### 1. Average Price by Zipcode
The first visualization identifies which areas have the highest listing prices.

A bar chart and map were created using:

- `Zipcode`
- `Average Price of Listings`

The visualization is color coded by zipcode, making it easier to identify the most expensive neighborhoods and potential high-revenue locations.


### 2. Revenue Trend by Week
This visualization helps determine **the best time of year to list a property on Airbnb** rather than occupying it as the owner.

Fields used:

- `Week`
- `SUM(Price)` from the calendar dataset

Because the dataset only contains data from 2016, a filter was applied to include data up to 31-12-2016. After the 2nd of January, the data drops because there is no additional data available for 2017.

This visualization highlights seasonal demand trends.

### 3. Number of Bedrooms vs Listings
This chart shows the distribution of listings by number of bedrooms.

This is important because:

- The number of bedrooms affects the property purchase price.
- Larger properties often generate higher nightly rental prices.

The visualization helps investors understand which property sizes are most common and potentially profitable.

### 4. Competition by Area
This visualization analyzes the number of listings in each zipcode, which represents the level of market competition.

Areas with:

- High listings → higher competition
- Lower listings but high prices → potential investment opportunities

## Dashboard
All visualizations are combined into a single interactive Tableau dashboard that allows stakeholders to quickly explore:

- Pricing by location  
- Seasonal revenue trends  
- Property size distribution  
- Market competition  

The dashboard provides a data-driven overview to support Airbnb investment decisions.


## Key Insights
From the analysis:

- Certain zipcodes consistently show higher average listing prices.
- Seasonality affects revenue, meaning some weeks generate higher income than others.
- Properties with more bedrooms tend to command higher nightly prices.
- Some areas show high competition, while others may present better opportunities for new listings.

