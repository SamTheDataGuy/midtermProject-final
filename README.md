# Mid-term Project-Competitor Analysis with Open Data
LHL DS May 29th Cohort Midterm Project (Mehzabeen, Nasser, Sam)

There are several hotels around the city of Toronto. By using the Yelp API, we have gathered information about these hotels and at the same time all the restaurants that are found within a 200m radius around those hotels. Our goal is to see whether these restaurants are a contributing factor for profitability for any new business seeking to enter the industry in the city of Toronto.

## Question
- How do nearby Points of Interests - (Restaurants) affect the popularity, price, and ratings of hotels in the city of Toronto?

## Method
- Use data from Yelp APIs 

    
    (We have also extracted data through Google Places, Hotels.com, and Trip Advisor API's but we did not get the information we wanted and decided to use the Yelp API instead)

## Steps
- Pull hotel data from Yelp API.

-   Use python to create a function that pulls  all nearby ammenities for each hotel by using longitude and latitude. (Points of Interest within 200m)
- Test function with 1 or 2 hotels
- Once we're getting the data we want, run the function with all the hotels
- Use Pandas and data visualizations to perform EDA to see if we can gain some preliminary insights on the data, and confirm what data needs to be cleaned
- Clean data 
- Perform further analysis 
- Apply appropriate statistical models to identify relevant trends and patterns in data

- Build a regression model to highlight anomalies, make meaningful conclusions, and support strategic business decisions

- Use Tableau to create multiple data visualizations based on the data we have gathered

- Use those visualizations to answer the question whether Points of Interests are in fact a determining factor for new businesses wanting to settle in the area

- Create a dashboard to present our findings

Result


Challenges

- We have tried a couple of APIs. Some were easily accessible, others required a website like the walkscore API. We also had the limit constraint but we managed to pull a sample data to start an anlysis and from there we gathered more data.

- 