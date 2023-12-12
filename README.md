
# Project: NoSQL | Eat Safe, Love - UK Food Establishments Analysis

## Overview

In this project, I took on the task of analyzing data from the UK Food Standards Agency's food hygiene ratings for various establishments. My goal was to assist the food magazine, "Eat Safe, Love," in identifying key areas of interest for future articles about food establishments.

## Project Structure

The project was organized into three main parts:

### Part 1: Database and Jupyter Notebook Set Up

-   I used `NoSQL_setup_starter.ipynb` for the initial database and Jupyter notebook setup.
-   I imported `establishments.json` into a MongoDB database named `uk_food`.
-   Python libraries such as PyMongo and Pretty Print were utilized for database operations.
-   I ensured the successful creation of the database and the proper loading of data.

### Part 2: Update the Database

-   I added a new halal restaurant named "Penang Flavours," located in Greenwich, to the `establishments` collection in the database.
-   I updated the `BusinessTypeID` of the new restaurant to align it with existing data standards.
-   At the request of the magazine, I removed establishments located in the Dover Local Authority area.
-   I converted data fields like latitude, longitude, and `RatingValue` to their appropriate data types for consistency and accuracy.

### Part 3: Exploratory Analysis

-   I conducted exploratory data analysis on the `uk_food` database to answer specific inquiries from the magazine.
-   Methods like `count_documents` for counting, `pprint` for displaying documents, and conversion of results into Pandas DataFrames were employed.
-   I focused on queries like identifying establishments with specific hygiene scores, analyzing establishments in London with high rating values, finding top establishments in proximity to "Penang Flavours," and evaluating hygiene scores across different local authorities.

## Key Insights and Findings

-   I identified establishments with hygiene scores equal to 20.
-   I analyzed establishments in London with a `RatingValue` of 4 or higher.
-   I located top-rated establishments near "Penang Flavours," focusing on hygiene scores and proximity.
-   I compiled data on local authorities with the highest number of establishments having a hygiene score of 0.

## Tools and Technologies

-   MongoDB for database management.
-   Python, Pandas, and Jupyter Notebook for data processing and analysis.
-   PyMongo for interacting with MongoDB.
-   Pretty Print (pprint) for a more readable display of query results.

## Conclusion

This project enabled me to effectively utilize an ETL pipeline for data extraction, transformation, and loading into a relational database. I successfully transformed the raw data into insightful information, aiding "Eat Safe, Love" magazine in focusing their journalistic efforts on relevant and interesting food establishments.
