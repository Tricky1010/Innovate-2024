# Forest Fire Detection and Hotspot Identification

This project aims to identify forest fire hotspots using k-means clustering. By analyzing various features such as latitude, longitude, temperature, humidity, wind speed, and precipitation, this approach helps in efficiently allocating necessary resources to mitigate the severity of wildfires.

## Objectives
- Identify crucial hotspots during forest fires.
- Mitigate the severity of wildfires.
- Regulate and predict wildfire behavior.
- Efficiently allocate necessary resources.

## Dataset
The dataset used in this project includes:
- `latitude`: Geographic latitude of the fire incident.
- `longitude`: Geographic longitude of the fire incident.
- `size`: Size of the fire incident.
- `temperature`: Temperature at the location.
- `humidity`: Humidity at the location.
- `wind_speed`: Wind speed at the location.
- `precipitation`: Precipitation at the location.
- `forest_name`: Name of the forest where the incident occurred.

## Project Steps

### 1. Data Preparation
Create a DataFrame with real forest names and realistic data.

### 2. Data Cleaning
Handle any potential missing values and fill them with the mean of the respective columns.

### 3. Data Normalization
Normalize the features to ensure they're on a similar scale, which is important for clustering algorithms.

### 4. Determine the Optimal Number of Clusters
Use the Elbow Method to determine the optimal number of clusters for K-Means clustering.

### 5. Apply K-Means Clustering
Using the optimal number of clusters identified, apply K-Means clustering to the data.

### 6. Visualize the Clusters
Visualize the clusters on a scatter plot.




