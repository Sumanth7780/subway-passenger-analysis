# subway-passenger-analysis
Deep Learning Project

## Overview
This project aims to analyze subway passenger flow to derive meaningful insights using clustering techniques and data visualization. The dataset contains AFC (Automated Fare Collection) data, which helps in identifying different passenger categories, station clusters, and travel patterns.

## Project Structure
```
├── 1-data-gathering.ipynb               # Collecting and loading AFC data
├── 2.1-data-preprocessing.ipynb         # Cleaning and structuring the dataset
├── 2.2-data-generation.ipynb            # Feature extraction and transformation
├── 3-data-exploration.ipynb             # Statistical analysis and visualizations
├── 4.1-cluster-stations.ipynb           # Clustering stations based on passenger flow
├── 4.2-cluster-stations-viz.ipynb       # Visualizing station clusters
├── 4.3-cluster-ind-traces.ipynb         # Clustering individual travel traces
├── 4.4-cluster-ind-traces-performance.ipynb # Performance evaluation of clustering models
├── 4.5-cluster-ind-traces-viz.ipynb     # Visualization of individual trace clusters
├── 5.1-supp-viz.ipynb                   # Additional visualizations and insights
├── gmm_entry_10.sav                     # Gaussian Mixture Model saved state
├── pairplot.png                          # Correlation matrix visualization
├── requirements.txt                      # List of dependencies
├── .gitignore                            # Ignoring unnecessary files
├── README.md                             # Documentation (this file)
├── CONTRIBUTING.md                       # Guidelines for contributing
├── LICENSE                               # License information
```

## Installation & Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/subway-passenger-analysis.git
   cd subway-passenger-analysis
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Open Jupyter Notebook and explore the project:
   ```sh
   jupyter notebook
   ```

## Data Analysis Pipeline
1. **Data Gathering**: Load AFC data, preprocess, and clean missing values.
2. **Preprocessing & Feature Engineering**: Convert categorical data, normalize numerical values.
3. **Exploration**: Generate statistics, visualize trends, and detect anomalies.
4. **Clustering Stations**: Identify similar stations using clustering methods.
5. **Clustering Individual Travel Traces**: Segment travel patterns to detect behavioral insights.
6. **Evaluation & Visualization**: Compare clustering models and visualize patterns using advanced plotting.

## Key Features
**Passenger Flow Analysis**: Identifies how different passenger categories move across subway stations.
**Clustering Algorithms**: Uses K-Means, Gaussian Mixture Model (GMM), and DBSCAN.
**Advanced Visualization**: Implements seaborn, Matplotlib, and Plotly for interactive plots.
**Optimized Performance**: Benchmarks different clustering techniques to choose the best.

## Author
Developed by Sumanth Dadi

