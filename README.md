## Background

Airbnb is one of the largest accommodation platforms in the world, with thousands of listings available in major cities, including Bangkok. This city has unique characteristics because it has:
- a dense city center,
- a public transportation system that strongly affects tourist mobility (BTS, MRT),
- many popular tourist attractions such as the Grand Palace and Chatuchak Market.

For property owners, location is a key factor when deciding prices, booking potential, and listing marketing strategies. However, not all owners clearly understand how distance to the city center, public transportation, and tourist attractions actually affects their listing performance.

By understanding how location affects listing performance, property owners and future hosts can:

1. set more competitive prices,
2. optimize listing strategies,
3. increase occupancy rates,
4. and maximize revenue.

The Airbnb Listings Bangkok dataset provides an opportunity to analyze location factors and see whether location truly has a significant impact on listing performance. Performance can be measured using price, number of reviews, reviews per month, and availability level.

## Dataset Used
This dataset contains information about accommodation listings in Bangkok that are registered on Airbnb.
There are 17 columns in the Airbnb Listings Bangkok dataset:

Unnamed:0 : extra dataset index  
id : unique ID for each listing  
name : name of the listing  
host_id : unique ID of the host  
host_name : name of the host  
neighbourhood : name of the area/district where the listing is located  
latitude : latitude coordinate of the listing location  
longitude : longitude coordinate of the listing location  
room_type : type of room  
price : listing price in Baht (THB)  
minimum_nights : minimum number of nights required to book  
number_of_reviews : total number of reviews for the listing  
last_review : date of the last review  
reviews_per_month : average number of reviews per month  
calculated_host_listings_count : number of listings owned by the host  
availability_365 : number of available days in one year  
number_of_reviews_ltm : number of reviews in the last 12 months  

## Analysis Process
1. Load Data
2. Data Cleaning (drop columns, handle missing values, fix data types, correct typos)
3. Data Enrichment (calculate distance to landmarks, transport stations, and city center)
4. EDA & Descriptive Statistics
5. Outlier Handling
6. Data Visualization
7. Inferential Analysis

## Dashboard
You can see the dashboard at the link down below:
https://public.tableau.com/app/profile/rivaldo.nugradwiyanto/viz/AirbnbListingsBangkokPerformance/Dashboard1

This dashboard presents key insights on how location factors such as distance to the city center, MRT/BTS stations, and tourist attractions affect Airbnb listing performance in Bangkok, including price and demand patterns.
