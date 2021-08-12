# ANC Neighbors

This is a geospatial analysis of household addresses to connect church members (Austin New Church) across Austin metro in a data-driven fashion.

Project overview:

- Load and extract addresses from database and convert them to geospatial coordinates
- Apply k-means clustering to identify geospatial clusters and classify new datapoints
- Perform basic descriptive statistics and visualizations for geospatial clusters

**Tools:** *Pandas, NumPy, scikit-learn, folium, Google Maps Geocoding API*

*Note: cell outputs with personal identifying information were cleared*

# Train classifier (N = 246)
<iframe src="maps/training_model.html" height="500" width="500"></iframe>

# Predict new geosptial data points (N = 108)
Before applying classifier:
<iframe src="maps/test_set.html" height="500" width="500"></iframe>

After applying classifier:
<iframe src="maps/test_set_classified.html" height="500" width="500"></iframe>

# Full map (N = 354)

<iframe src="maps/fullset.html" height="500" width="500"></iframe>
