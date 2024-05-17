# Python.Airbnb-Mallorca-Analysis
The goals for this project were sourcing my own dataset and explore relationships within the data in Python. After the initial steps in the exploratory analysis I created the following hypothesis:
- If the review scores rating is higher, then the review scores of the location are also higher.

I used the results that I created in Python to build a business case in Tableau.

I chose the dataset of Airbnb Mallorca because I live there partly and because the data is of high quality. 

# Research Questions
The questions that are explored in several analysis steps in Python are:
- Are the listings spread over the Island? Do most listings fall into a specific geographical category, for example next to the beach or in the mountains?
- What are the numbers of guests that book Airbnb a lot in Mallorca, Mostly duo’s, big groups, in between the two or more or all sizes?
- What are the differences in prices and are listings of certain prices mostly booked?
- Does being a superhost have a lot of influence on bookings?
- The highest possible score of reviews is 5. Do reviews with a score lower than 3 have a lot of influence on the popularity of the listing?
- What is the relationship between property location and guest satisfaction?

The questions ultimately used for the full analysis in Tableau:
- What is the relationship between property location and guest satisfaction?
- Do listings that are close to the beach or have mountain view have influence on the location review scores?

# Data
The dataset contains information about all the Airbnb listings of Mallorca that have received reviews
in the past. There are almost 12000 listings and next to basic information such as id, name, url and 
location it has information about the host, the property, price and availability and information on 
the reviews of the listings.

The Inside Airbnb website shows that the data of Mallorca has been last updated the 23rd of March 
2024 and that in general it is updated every quarter. The data therefore stays up to date.

For the time series analysis I have used Zillow Housing data via Nasdaq.

# Tools
For this project I used Tableau and Python with the following libraries:
- pandas & numpy - for data analysis
- seaborn, matplotlib, sklearn, and folium - for data visualization
- json and geojson - for spatial analysis

# Sources
The dataset comes from Inside Airbnb, the database website from Airbnb. Given the fact that the 
source is from the company, the dataset is trustworthy.

The website of Nasdaq offers a wide variety in financial data from different companies and can therefore be seen as trustworthy. To use the data in Pyhon I imported the API key lniked to my created profile.

# Visualizations
The business case with extra visualizations for this project were created in Tableau Public. It can be found here: [Airbnb Mallorca Business Case](https://public.tableau.com/app/profile/simone.van.der.graaf/viz/ProjectAirbnbMallorca-CareerFoundry/Story1?publish=yes)  
