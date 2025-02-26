# Python-API-Challenge
Weather Analysis and Vacation Planning

This repository contains the solution for a challenge that involves analyzing weather data, specifically focusing on weather conditions such as humidity, temperature, wind speed, and location. The analysis then branched into identifying areas with higher humidity values and mapping those locations. Additionally, the analysis was used to filter vacation destinations based on specific weather criteria and identify nearby hotels.

Overview
In this project, the main objective was to analyze weather data and filter locations based on specific weather conditions suitable for a vacation. Here's a breakdown of the steps followed:

1. Weather Data Analysis:
The initial part of the analysis involved examining weather data such as humidity, temperature, wind speed, and location.
Focused on identifying different humidity values across locations.
2. Humidity Analysis:
After determining the humidity levels, the analysis shifted toward identifying areas with higher humidity values and plotting those areas on a map.
3. Vacation Destination Selection:
Using the filtered weather data, I set criteria for a vacation destination:
Temperature: Cooler than 100°F, warmer than 50°F.
Wind Speed: Less than 10 mph.
Humidity: Low humidity.
After filtering locations that met these conditions, I used the Geoapify API to find hotels located within 10,000 meters of the city locations that met the criteria.
4. Hotel Identification and Plotting:
After using Geoapify to identify hotels near the filtered cities, I plotted the locations of these hotels on a map.

Tools and Resources Used

Python for data analysis and manipulation.
Pandas for working with the weather data.
Matplotlib/Plotly for graphing and visualizing data.
Geoapify API for finding hotels near the city locations.
ChatGPT, Stack Overflow, API documentation, and Peers for troubleshooting and clarifications.

Key Observations

The weather data provided valuable insights into the relationship between temperature, wind speed, and humidity in different regions.
After filtering based on vacation criteria, the Geoapify API successfully helped identify hotels within the proximity of the cities that met the weather conditions.
The final output was a map of vacation destinations with corresponding hotel locations, ensuring that the weather conditions would make for an ideal vacation.

How to Use

Clone the repository to your local machine.
Install the required dependencies (e.g., Pandas, Matplotlib, Geoapify).
Use the provided Jupyter notebooks or Python scripts to replicate the weather analysis, filtering, and hotel identification.
Make sure to insert your Geoapify API key to run the hotel-finding query.
Review the generated graphs and maps to visualize filtered vacation locations and hotel data.

Conclusion

This project was a great learning experience in analyzing weather data, filtering it based on specific criteria, and leveraging APIs like Geoapify to find hotels. By combining multiple data sources and tools, I was able to find vacation destinations with optimal weather conditions and nearby accommodations.
