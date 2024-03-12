# TravelFoodSeries

## Career Coach 4.0 Data Engineer Internship Assessment (TAY HAN)

## Overview

Steven, a travel blogger, wants to create a travel food series using data from Zomato for inspiration. Your task involves processing the data provided by Steven and extracting relevant information to assist him in finding restaurants with good user ratings and interesting past events.

### Task 1:

1. **Extract Fields and Store Data**: Extract specific fields from the provided data and store them in the `restaurants.csv` file.
   - Fields to extract:
     - Restaurant Id
     - Restaurant Name
     - Country
     - City
     - User Rating Votes
     - User Aggregate Rating (in float)
     - Cuisines

2. **Extract Restaurants with Past Events**: Extract restaurants that had events in April 2019 and store the data in the `restaurant_events.csv` file.
   - Fields to extract:
     - Event Id
     - Restaurant Id
     - Restaurant Name
     - Photo URL
     - Event Title
     - Event Start Date
     - Event End Date
   - Populate empty values with "NA".

3. **Determine Rating Thresholds**: Determine the threshold for different rating text based on aggregate rating from the `restaurant_data.json` dataset.
   - Ratings to determine thresholds for:
     - Excellent
     - Very Good
     - Good
     - Average
     - Poor

## Requirements

- `pandas`
- `numpy`
- `requests`

## Getting Started
These are the following dependencies required to run the file. Install before running the Notebook

```
pip install requirements.txt
```

This is a GovTech Take Home Assessment for the Data Engineering Role

