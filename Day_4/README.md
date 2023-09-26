# Europe Economy Gap Analysis
This repository contains Python code for analyzing Europe's economy, focusing on various economic indicators such as GDP, interest rate, inflation rate, and more. The analysis is performed using data visualization techniques and clustering algorithms.

## Code Overview
### Data Import and Preprocessing:
The data is imported from a CSV file containing economic indicators.
Necessary preprocessing steps include handling missing values, data type conversions, and dropping unnecessary rows and columns.


### Exploratory Data Analysis (EDA):
Heatmap: A heatmap is generated to visualize correlations between different economic indicators.
Boxplots: Boxplots are created to showcase the distribution of each indicator.


### Feature Engineering:
GDP per Population: A new feature, 'GDP_per_population,' is calculated by dividing GDP by the population.

### Standardization:
StandardScaler is applied to standardize the data for further analysis.

### Clustering:
KMeans clustering is used to identify economic clusters based on the standardized data.
Elbow method is utilized to determine the optimal number of clusters.

### Cluster Analysis:
Cluster characteristics and boxplots for each economic indicator within the clusters are visualized.


### PCA and 3D Visualization:
Principal Component Analysis (PCA) is employed to reduce the dimensionality of the data.
A 3D plot is generated to visualize the clusters based on the principal components.
