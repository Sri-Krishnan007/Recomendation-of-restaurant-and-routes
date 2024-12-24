# 🍽️ Restaurant Recommendation and Route Optimization System

#  📌 Project Overview

This project is a Restaurant Recommendation and Employee Route Optimization System developed using Streamlit. It combines geolocation, graph algorithms, and interactive UI to provide optimized routes for employees and personalized restaurant recommendations for users.

#  🛠️ Technologies Used

Streamlit: Interactive web application framework.

Pandas: Data analysis and manipulation.

Geopy: Geographical distance calculations.

NetworkX: Graph algorithms for route optimization.

NumPy: Matrix and numerical computations.

Pillow (PIL): Image handling.

Geocoder: User location detection.

Webbrowser: External browser integration.

# 📂 Dataset Details

Employee.xlsx: Employee location data (Latitude, Longitude, Locations).

Zomato Chennai Listing 2020.csv: Chennai restaurant data.

Coimbatore Restaurants.csv: Coimbatore restaurant data.

#  🚀 Core Functionalities

1️⃣ Find Your Location

Detects user geolocation.

Displays latitude and longitude.

2️⃣ Open Maps

Redirects users to an interactive Google Maps view.

3️⃣ Recommend Nearby Restaurants

Recommends restaurants based on the user's location.

Utilizes Prim's MST algorithm for route efficiency.

4️⃣ Review and Rating

Displays top-rated restaurants.

Sorted by combined dining and delivery ratings.

5️⃣ Select Restaurant

Detailed information about selected restaurants:

Address

Phone

Cuisine

Price for Two

Ratings

6️⃣ Chennai Restaurants

Filters restaurants by:

Location

Cuisine

Price for two

Results are sorted by combined ratings.

7️⃣ Employee Route Optimization

Processes an uploaded Excel file with employee locations.

Calculates shortest routes using Dijkstra's algorithm.

Displays the top 5 optimized routes.

#  🧠 Algorithms Implemented

Haversine Distance: Calculate distance between two points on Earth.

Prim's Algorithm: Minimum Spanning Tree for route optimization.

Dijkstra's Algorithm: Shortest path calculation between locations.

#  📦 Setup and Installation

Clone the repository:

https://github.com/Sri-Krishnan007/Recomendation-of-restaurant-and-routes

Install dependencies:

pip install streamlit pandas geopy numpy networkx pillow geocoder

Run the application:

streamlit run main.py

Access the app at:

http://localhost:8501



# 📄 Future Improvements

Optimize large dataset filtering.

Enhanced error handling for geolocation services.

Improved UI/UX.



# 📬 Contact

Developer: Sri Krishnan G

Email: srikrish2705guru@gmail.com

