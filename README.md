# Location-Based-Restaurant-Analysis
(Cognifyz ML Internship)

1)Task Objective:
The goal of this task is to perform a location-based analysis of restaurant data using latitude and longitude. The analysis involves plotting restaurants on a map, grouping them by city, and understanding how location impacts rating and price.

This task simulates what apps like Zomato or Google Maps do when they show nearby restaurants with pins on a map.

2)Technologies Used:
Python
Pandas
Folium (for maps)
Matplotlib / Seaborn (for graphs)
Scikit-learn (for clustering)
Jupyter Notebook / Google Colab

3)Project Structure:
├── location_dataset.csv
├── task4_location_analysis.ipynb
├── restaurant_map.html
├── README.md

4)Steps Performed:

1)Import Dataset
Load restaurant data containing location, ratings, and pricing.

2)Clean Dataset
Handle missing values and ensure valid coordinates.

3)Map Visualization
Use Folium to create an interactive map with pins for each restaurant based on latitude & longitude.

4)Group by City
Group restaurants by city and calculate:
Number of restaurants
Average rating
Average price range

5)Create Graphs
Use bar charts to visualize:
Restaurant count by city
Average rating by city

6)Output Files
restaurant_map.html: Interactive map with restaurant pins.

Bar graphs: Showing city-wise restaurant stats.


5)Sample Output :

City      | Restaurant Count | Avg Rating | Avg Price Range
-----------------------------------------------------------
Mumbai    |         2        |    4.05    |       2.0
Delhi     |         1        |    4.2     |       3.0
Chennai   |         1        |    3.9     |       2.0
Bangalore |         1        |    4.5     |       3.0

6)Key Learnings:
*Visualizing geolocation data on maps
*Calculating city-wise restaurant statistics
*Understanding how ratings and prices vary by location
*Using clustering for zone-based grouping

Output:
