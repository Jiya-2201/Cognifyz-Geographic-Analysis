🌍 Geographic Analysis — Cognifyz Technologies Internship (Level 2: Task 3)
👩‍💻 Intern: Jiya Pranavkumar Chauhan

Domain: Data Analytics
Organization: Cognifyz Technologies

🧭 Overview

This project is part of the Cognifyz Technologies Data Analyst Internship, specifically Level 2 – Task 3: Geographic Analysis.
The goal is to explore the geographical distribution of restaurants based on latitude and longitude coordinates and visualize clusters, city-level patterns, and spatial correlations with ratings and votes.

By leveraging Python, Pandas, and Folium, the analysis provides an interactive and insightful view of restaurant placement and performance.

🎯 Objectives

Plot the locations of restaurants on an interactive map using their latitude and longitude coordinates.

Identify clusters and hotspots of restaurants across different regions.

Explore city-level insights, including the number of restaurants and average ratings.

Visualize geographic patterns to derive meaningful business insights.

🧹 Data Preprocessing
Performed Data Cleaning and Formatting:

Removed duplicate entries and missing coordinate values.

Selected relevant columns:

Restaurant Name, City, Latitude, Longitude, Aggregate rating, and Votes.

Converted numeric columns (Aggregate rating, Votes) to proper data types.

Dropped records with invalid or null coordinate data.

Verified consistency in rating scales and city labels.

🧩 Data Analysis Workflow
🔹 Step 1: Load and Inspect Data

Imported libraries (pandas, folium, matplotlib, seaborn).

Verified dataset structure and null values.

🔹 Step 2: Create Interactive Map (Folium)

Used Folium to map each restaurant’s location based on latitude and longitude.

Color-coded markers to represent restaurant ratings:

🟢 Green → Rating ≥ 4.0

🔵 Blue → Rating < 4.0

Each marker displays restaurant name, rating, and votes in a popup tooltip.

Output:
📄 outputs/reports/restaurant_map.html — Interactive map file.

🔹 Step 3: Analyze City-Wise Restaurant Distribution

Grouped restaurants by city and counted the number of entries.

Created a horizontal bar chart to display Top 10 Cities with Most Restaurants.

Output:
📊 outputs/charts/top_cities_restaurants.png

🔹 Step 4: Analyze Average Rating by City

Aggregated average Aggregate rating per city.

Identified top 10 cities with the highest average customer ratings.

Created another bar chart for comparison.

Output:
⭐ outputs/charts/top_cities_by_rating.png

📈 Visual Results
Visualization	Description
Interactive Map	Plots all restaurant locations with rating-based color markers.
Top 10 Cities with Most Restaurants	Identifies high-density regions for restaurant businesses.
Top 10 Cities by Average Rating	Shows cities with the best-rated dining experiences.
💡 Insights & Observations
Observation	Business Implication
1. City Clustering: Certain metro cities like Delhi, Bangalore, and Mumbai show dense restaurant clusters.	Indicates highly competitive and diverse food markets.
2. Rating Concentration: Higher ratings often appear in central city regions.	Suggests better service standards and customer engagement in prime zones.
3. Regional Hotspots: Some cities with fewer restaurants show higher average ratings.	Niche or specialized restaurants may thrive in smaller markets.
4. Multi-Location Presence: Several brands operate in multiple cities, showing regional expansion trends.	Useful for franchise or expansion strategy insights.
🧠 Conclusion

The Geographic Analysis task highlights how location data can reveal meaningful spatial and business insights.
Through mapping and visualization, this project successfully demonstrates how:

Restaurant clusters indicate urban market potential.

Ratings vary with geographical and competitive density.

Interactive maps can help visualize data distribution intuitively.

Such analyses are valuable for decision-making in marketing, restaurant expansion planning, and competitor landscape studies.

🛠️ Tools & Technologies Used
Category	Tools
Programming	Python 3
Libraries	pandas, numpy, folium, seaborn, matplotlib
Visualization	Folium (Interactive Map), Seaborn (Charts)
IDE	VS Code / Jupyter Notebook
Version Control	Git, GitHub
📂 Project Structure
Level2_Task3/
│
├── Dataset.csv
├── geo_analysis.ipynb
├── geo_analysis.py
├── README.md
├── requirements.txt
│
├── outputs/
│   ├── charts/
│   │   ├── top_cities_restaurants.png
│   │   └── top_cities_by_rating.png
│   └── reports/
│       ├── restaurant_map.html
│       └── Level2_Task3_Report.html

📁 Outputs Summary
File	Description
outputs/charts/top_cities_restaurants.png	Bar chart showing top 10 cities with most restaurants.
outputs/charts/top_cities_by_rating.png	Bar chart showing top 10 cities by average rating.
outputs/reports/restaurant_map.html	Interactive geographic map (Folium).
outputs/reports/Level2_Task3_Report.html	Exported HTML report for presentation.
🌐 Connect with Me

👩‍💻 Jiya Pranavkumar Chauhan
📊 Data Analyst Intern | Cognifyz Technologies



🏷️ Tags

#CognifyzTechnologies #DataAnalysis #Internship #Python #EDA #Visualization #DataScience #GeographicAnalysis #Folium #Pandas #MapVisualization.com/Jiya-2201)
