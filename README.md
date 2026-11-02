# nyc-airbnb-recommendation
Personalized Airbnb Recommendation System for NYC

Data Sources and Price Estimation
The analysis uses 36,445 NYC listings from the February 2026 Inside Airbnb snapshot. Because the original price field is missing, an external 2024 NYC Airbnb dataset containing 20,758 records supplements the price dimension.

The historical estimation retained 20,316 records priced between $33 and $900. Listings were assigned to 12 clusters based on location, room characteristics, availability, and review-related features; each cluster’s median price was transferred to comparable 2026 listings.

These values are estimated reference prices, not observed 2026 listing prices or current booking quotes. The interactive website demonstrates preference-based ranking using budget, rating, location, and user-selected priorities.
