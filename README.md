# Project Summary -
Since 2008, guests and hosts have used Airbnb to expand on traveling possibilities and present a unique, individualized way of passing the world. Airbnb is of a kind service that's used and honored by the whole world. Data analysis on millions of rosters handed through Airbnb is a pivotal factor for the company. These millions of rosters induce a lot of data that can be anatomized and used for security, business opinions, understanding of guests and providers(hosts)and performance on the platform, guiding marketing enterprise, perpetration of innovative fresh services, and much further.

1. Airbnb is considered to be an online marketplace where people are able to connect with each other, as the people who want to rent out their property look for people, who are looking for accommodation in specific areas.
2. The goal of the project - The purpose of the project is to gather information and analyze the detailed information of the different bookings in the neighborhood groups in order to provide insights about the bookings in a particular area as per your preference, type of rooms, and price accordingly.
3. We have tried discovering relationships among different columns and found meaningful insights to decipher business impacts.
4. Here we have the datset of around 49,000 observations with 16 columns and it is a combination of categorical and numeric values.

# Problem Statement
1. What is the count of properties of each room type?
2. Name the top 10 hosts who are the busiest in terms of the number of reviews.
3. What is the average price for each neighborhood group?
4. Show the distribution of properties in a particular neighborhood group.
5. Name the top 10 hosts in terms of their average price.
6. Find the relationship between all the columns with each other and one another.

# Define Your Business Objective.
1. The objective of my analysis is to provide insights about different AirBnbs and their properties.
2. Finds the key factors responsible for a particular preference for room type by people.
3. Studied the detailed information given about each Airbnb
4. Analyze the behavior of the host, the pattern of change in preference of people in terms of different room types, unequal distribution of properties in each neighborhood group, etc.

# What did you know about your dataset?
As per the above information, we can see the columns host_name, neighbourhood_group, neighborhood, room_type, and reviews_per_month are all object types. Others are either int or float type.
The following are the counts for null values:

name - 16
host_name - 21
last_review - 10052
reviews_per_month - 10052
The following columns are listed in the DataFrame-

1. ID - ID of the person who booked the Airbnb.
2. Name - Name of the person who booked accommodation.
3. host_id - ID of the person who rents out the property.
4. Host_name - Name of the person who rents out their property.
5. neighbourhood_group- It indicates the region that includes several small neighborhoods (i.e. like a broader group having smaller units of neighborhood).
6. Neighborhood - It indicates the geographically smaller areas within a city or region having their own local identity and characteristics.
7. Latitude - Shows the measurement of the distance from the north or south pole of an equator of that particular property.
8. Longitude - Shows the measurement of distance from the east or west prime meridian of that particular property.
9. room_type - Indicates the type of the room i.e. private room, Entire home/apt, or shared room.
10. price - This indicates the value at which the property is rented in bucks.
11. minimum_nights - This shows the minimum nights offered by the host (i.e. a person can't book for less than this set number of nights)
12. number_of_reviews - This indicates the number of reviews received by a particular property.
13. last_review - Shows the last date of the review given
14. reviews_per_month - It indicates the number of reviews given in a particular month.
15. calculated_host_listings_count- It shows the count of listings per host.
16. availability_365 - It indicates how many days the Airbnb is available in a year.

# Solution to Business Objective
1. As per the current scenario, people usually prefer to go for an entire home / apt because they prefer to put their privacy above the price of the property. So we should try investing more in renting big properties.
2. Also, we can say that for most of the neighborhood group, private and shared room types have somewhat similar average prices so it may be the case that people would prefer to stay in the private room category than the shared one so we should either try reducing the price of the shared room or increase the price of private room types.
3. We also got to know that some neighborhood groups were dense with properties whereas some had few properties i.e. were scattered which in turn led to a limit of choices for people to make before booking in a particular area, so we should also focus on including more properties there.
4. Through this type of analysis, we can help ourselves to make the decision wisely which is helpful to us in terms of quality and user-friendly experience.

# Conclusion
Throughout our analysis, we have gained a deeper understanding of various aspects of Airbnb, including pricing dynamics, geographical distribution, property types, and number of reviews. One of the key takeaways from our analysis is the importance of location in determining Airbnb rental prices. We found that certain neighborhoods and cities command higher prices, reflecting the influence of demand, local amenities, and tourist attractions. Hosts can use this information to optimize their pricing strategies, while travelers can make more informed choices based on their budget and preferences. In conclusion, our Airbnb EDA project has illuminated the complex landscape of Airbnb rentals, providing valuable insights for both hosts and travelers. By harnessing the power of Python and data analysis, we have unlocked the potential to make more informed decisions, ultimately enhancing the Airbnb experience for all parties involved. This project serves as a testament to the importance of data-driven decision-making in the modern world of hospitality and travel.
