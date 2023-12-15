Airbnb Data Analysis
Our goal is to discover trends, relationships, and valuable insights that could help improve Airbnb’s offerings. This includes understanding the behavior of users and hosts, informing marketing initiatives, and aiding in business decision-making.

Objectives
Price Analysis: Analyze how price is correlated with other variables such as neighbourhood, type of accommodation, to understand pricing trends and develop an optimized pricing strategy.
Neighbourhood Data: Use neighbourhood data for targeted marketing and promotional activities.
Room Type Analysis: Analyze room type data to understand customer preferences and adjust service offerings accordingly.
Geolocation Analysis: Use the geolocation data to explore how things like price and room preference change with respect to location.
Dataset Description
The dataset contains the following columns:

name: This column represents the name of the listing. It is usually a short description that hosts use to describe their space to potential guests.
host_name: This column contains the name of the host. This is the person who has listed their property on Airbnb.
neighbourhood_group: This column represents the broader area or district in which the listing is located. For example, in New York City, this could be ‘Manhattan’, ‘Brooklyn’, etc.
neighbourhood: This column represents the specific neighborhood in which the listing is located. This is a more precise location within the neighbourhood_group.
room_type: This column indicates the type of room that is being listed. The options typically include ‘Entire home/apt’, ‘Private room’, or ‘Shared room’.
id: This column represents the unique identifier of the listing. Each listing on Airbnb has a unique id.
host_id: This column contains the unique identifier of the host. Each host on Airbnb has a unique id.
latitude: This column represents the latitude coordinate of the listing’s location.
longitude: This column represents the longitude coordinate of the listing’s location.
price: This column indicates the price per night for renting the listing.
minimum_nights: This column shows the minimum number of nights a guest can book the listing.
number_of_reviews: This column represents the total number of reviews that the listing has received from guests.
reviews_per_month: This column indicates the average number of reviews the listing receives per month.
calculated_host_listings_count: This column shows the number of listings that the host has on Airbnb.
availability_365: This column represents the number of days in a year that the listing is available for booking.
Analysis Methodology
Univariate Analysis: We will use KDE plots for continuous variables, and countplots for categorical variables.
Bivariate Analysis: We will use a combination of countplot and violinplots to compare variables.
Multivariate Analysis: We will use barplots with subcategories and scatterplots for geolocational analysis.# Airbnb-Dataset-Analysis
