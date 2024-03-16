# NYC Yellow Taxi Cab Trips Analysis

This project aims to analyze NYC yellow taxi cab trips using a dataset containing relevant trip information. The dataset is divided into two CSV files: `taxitripdata.csv` containing trip data and pickup/drop-off zones, and `taxizonegeo.csv` containing longitude and latitude coordinates of pickup zone areas.

## Task Description

For this assignment, we implement various functionalities and answer specific questions using NoSQL databases (MongoDB and Cassandra). Below are the tasks to be completed:

1. Remove unnecessary columns from `taxitripdata.csv`.
2. Drop rows with missing essential details.
3. Insert data into the database.
4. Calculate trip duration and add it as a new field.
5. Calculate total trip cost using relevant fare components.
6. Determine the most common payment type used per time of day.
7. Calculate the average tip amount per passenger count.
8. Identify the best 5 locations for drivers to pick up passengers.
9. Bonus: Explore the relationship between trip distance and tip amount without using correlation calculation.

## Dataset

The dataset consists of:
- `taxitripdata.csv`: Contains trip details and pickup/drop-off zones.
- `taxizonegeo.csv`: Contains polygon vertices of pickup zone areas.

## Implementation

The project involves implementing the above tasks twice, once for MongoDB and once for Cassandra.

## Results

- The results of queries (f), (g), and (h) will be displayed using visualizations.

## Contributors

- Mariam Sherif Almotawally
- Eyad Tamer Hassan
