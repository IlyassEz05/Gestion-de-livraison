# 🚚 Delivery Optimization System – Python, OpenRouteService & Folium

This project was developed during an internship with the goal of reducing delivery times and transportation costs through a Python-based optimization algorithm leveraging the **OpenRouteService API**.

## 📋 Overview

The system automates route planning for delivery operations by computing the **most efficient routes** between depots and multiple delivery points while respecting logistics constraints such as **time windows, vehicle capacity, and delivery quantities**.  
Developed using **Google Colab** and **Visual Studio Code**, the program generates an **interactive map** visualizing optimized routes, delivery locations, and detailed delivery information.

## 🧠 Key Responsibilities & Achievements

- 🔹 Designed and implemented a **Python optimization algorithm** to compute the shortest delivery paths.  
- 🔹 Integrated **OpenRouteService API** to calculate accurate distances and travel times according to the vehicle profile.  
- 🔹 Applied essential logistics constraints:
  - Delivery time windows  
  - Vehicle capacity limits  
  - Quantity per delivery point  
- 🔹 Used the **Haversine formula** for precise geographical distance calculations.  
- 🔹 Generated **estimated arrival times**, identified **unserved locations**, and provided reasons such as excessive distance or time window violation.  
- 🔹 Developed a **dynamic Folium map** displaying:
  - 🏠 Depot locations (custom house icons)  
  - 📍 Delivery points (simple markers)  
  - 🚗 Optimized route lines connecting all points  
  - 🗂️ Popups containing detailed delivery information (client name, quantity, time window, etc.)

## 🛠️ Technologies Used

- **Python 3.x**
- **Google Colab**
- **Visual Studio Code**
- **OpenRouteService API**
- **Folium**
- **Pandas**
- **Geopy**
- **JSON / GeoJSON**

## 🌍 Visualization

When executed, the program produces an **interactive Folium map** that:
- Shows depots with house icons 🏠  
- Displays delivery points 📍  
- Connects all locations with optimized colored lines  
- Allows users to click on each marker to view delivery or depot information  



## 🚀 How to Run the Project

1. **Clone the Repository**
   ```bash
   git clone <repository-url>
   cd delivery-optimization
   
Install Required Packages:

pip install openrouteservice folium geopy pandas

Add Your OpenRouteService API Key:

client = openrouteservice.Client(key='5b3ce3597851110001cf6248316e4e7ca5ba4c7487f23f9ea5e0abe3')

Run the Script:

In Google Colab: Upload the .ipynb file and execute all cells.
In VS Code: Run the Python file (python main.py).

The system will:
Load the dataset (delivery coordinates)
Compute the optimized routes
Display the interactive Folium map in your browser

 Results:
This delivery optimization solution provides:
Efficient and cost-effective route planning
Real-time distance and time computation
Interactive visualization of delivery operations
Better decision-making for logistics management

 Summary:
Goal: Reduce delivery time and cost through intelligent route optimization
Method: Python algorithm + OpenRouteService API
Output: Interactive map showing optimized routes and delivery details
Tools: Google Colab & Visual Studio Code

Built with Python and Google Colab for smarter, faster, and more efficient delivery management.
#Python #OpenRouteService #Folium #GoogleColab #VSC #Logistics #Optimization #DataScience #Mapping
