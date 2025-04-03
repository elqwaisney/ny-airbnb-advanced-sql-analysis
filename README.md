# NYC Airbnb Analysis

This project explores Airbnb listings data from New York City (2019) to uncover insights about market trends, pricing, demand, and host activity. The analysis aims to identify neighborhoods with high revenue potential, evaluate market concentration, and understand the dynamics influencing pricing and demand across different areas of the city.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Analysis](#analysis)
  - [Host Analysis](#host-analysis)
  - [Listing Analysis](#listing-analysis)
  - [Pricing and Demand Trends](#pricing-and-demand-trends)
- [Visualizations](#visualizations)
- [Insights](#insights)
- [Conclusion](#conclusion)
- [References](#references)

---

## Introduction
This project uses the New York City Airbnb listings dataset to perform a thorough analysis of hosts, listings, pricing strategies, and demand patterns. Key focus areas include identifying popular and underserved neighborhoods, evaluating host activity, and examining how pricing influences demand. This analysis also includes a variety of visualizations, including maps and graphs, to communicate findings effectively.
## Dataset
The dataset comprises various details about Airbnb listings in New York City, including pricing, availability, reviews, and host information. External coordinate data is leveraged for mapping purposes.
## Analysis

### Host Analysis
- **Top Hosts:** Identification of hosts with the highest number of listings.
- **Host Review Activity:** Analysis of recent reviews to identify actively managed listings.
- **Market Concentration:** Detecting neighborhoods with high listings per host.

### Listing Analysis
- **Listing Distribution:** Number of listings per borough and neighborhood.
- **Revenue Potential:** Listings with the highest revenue potential.
- **Overpriced Listings:** Recognizing listings that are priced significantly higher than the average for their neighborhood group.
  
### Pricing and Demand Trends
- **Room Type Analysis:** Price and availability trends by room type.
- **Demand Patterns:** Popular and unpopular neighborhoods based on average reviews and listing counts.
- **Price-Demand Classification:** Categorizing neighborhoods by price and demand levels.

## Visualizations
### Maps
- **Top Busy Hosts' Listing Locations:** ![Mapping of Busiest Hosts' Listing Locations](https://github.com/user-attachments/assets/3a8540da-d915-492f-9402-d958599e2cb5)

- **Neighborhood Popularity Distribution:** ![Popularity Distribution](https://github.com/user-attachments/assets/9116e8f8-4676-45c4-97f5-9083fc82d896)

![Neighborhood Popularity Mapping](https://github.com/user-attachments/assets/3e0777ea-b7ff-4dab-a01e-f5513b234ae5)

- **Price-Demand Distribution:** ![Price and demand distribution map](https://github.com/user-attachments/assets/93d44e93-89d9-4e08-9778-d9802438acd9)

  - **High Price - High Demand:** Neon Green
  - **High Price - Low Demand:** White
  - **Low Price - High Demand:** greenish-yellow 
  - **Low Price - Low Demand:** Neon Red 



## General Insights
- **Popularity Trends:** Most popular neighborhoods in New York City are centered around **Lower Manhattan**, especially areas near the Hudson River, which offer proximity to iconic landmarks like Times Square, Wall Street, and the Statue of Liberty. These locations are highly attractive to tourists and benefit from strong transportation links.
  
- **Demand and Price Analysis:** We see that **East Village**, **Lower East Side**, and **Chinatown** represent high-demand, high-price neighborhoods, making them ideal for hosts to list their properties. Conversely, some areas in **Upper Manhattan**, such as **Harlem** and **East Harlem**, display high demand despite relatively lower prices, making them affordable alternatives.

- **Overpriced Listings:** Listings that are priced more than five times the neighborhood average tend to be premium properties, such as entire apartments near major landmarks, attracting higher-paying visitors. This pricing strategy, however, risks lower booking rates if not marketed correctly.

- **Market Concentration:** A high number of listings per host in certain neighborhoods points to market concentration, where a few hosts dominate the market. This could lead to pricing inefficiencies and reduced competition, potentially limiting the diversity of available listings.

## Conclusion
This analysis provides a comprehensive overview of the Airbnb market in New York City, with actionable insights for hosts and potential areas for improvement. The findings emphasize the importance of strategic pricing and location selection for maximizing revenue potential. Furthermore, addressing market concentration could foster a more competitive environment and benefit both hosts and guests.

## References
- NYC Airbnb Dataset (Source: [Kaggle link](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data))
- External Coordinate Data for Mapping (Source: [Nominatim API link](https://nominatim.org/))

