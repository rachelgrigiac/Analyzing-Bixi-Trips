# Analyzing Bixi Trips

This project involves an in-depth analysis of the Bixi bike-sharing system in Montreal from 2017 to 2020. The objective is to explore trip distributions, understand the impact of weather conditions on usage, and identify key patterns through clustering analysis. The findings aim to provide insights into optimizing Bixi's operations and marketing strategies.

### Objective

The Bixi bike-sharing system aims to enhance urban mobility in Montreal. This project seeks to uncover detailed insights into Bixi's trip data, examining how weather conditions affect usage patterns and identifying key customer segments to propose strategies for improved operational efficiency and targeted marketing.

### Key Questions
- How do different weather conditions (e.g., temperature, precipitation) impact Bixi trip counts and durations?
- How can Bixi users be segmented based on trip patterns, weather preferences, and other factors?
- Are there distinct clusters of users with similar behavior that can be targeted for marketing campaigns or operational improvements?

### Data & Tools

The datasets used in this project include:
- **Bixi Trip Data (2017-2020)**: Detailed information on each trip, including start and end stations, duration, user type, and timestamps.
- **Weather Data**: Daily weather data for Montreal, including temperature, precipitation, and other relevant metrics.
- **Montreal Neighborhoods**: Geographic data of Montreal neighborhoods stored in a JSON file.

The datasets for this project were obtained from the following sources:

- [Public Bike Sharing in North America](https://www.kaggle.com/datasets/jeanmidev/public-bike-sharing-in-north-america)
- [Bixi Montreal](https://www.kaggle.com/datasets/aubertsigouin/biximtl?select=limadmin.json)


Python (pandas, numpy, seaborn, matplotlib, folium, scikit-learn) was used throughout the analysis, through Jupyter Ntoebooks, as well as Tableau for the dashboard creation.
