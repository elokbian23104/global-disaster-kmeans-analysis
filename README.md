# global-disaster-kmeans-analysis
Exploratory data analysis and K-Means clustering of global disaster events using Python.

# Global Disaster Analysis using K-Means Clustering
This project presents an exploratory data analysis and clustering of global disaster events
using historical disaster data. The study aims to identify patterns and group disaster events
based on their characteristics using the K-Means clustering algorithm.

## Objectives
- Perform exploratory data analysis (EDA) on global disaster data
- Handle missing values, duplicates, and outliers
- Extract temporal and vulnerability-related features
- Group disaster events using K-Means clustering
- Support disaster risk and vulnerability assessment

## Dataset
The dataset used in this project is sourced from Kaggle and contains **50,000 records**
of global disaster events.

### Features
- `date` : Date of disaster occurrence
- `country` : Country where the disaster occurred
- `disaster_type` : Type of disaster (e.g., flood, earthquake, wildfire)
- `severity_index` : Composite index representing disaster severity
- `casualties` : Number of casualties
- `economic_loss_usd` : Estimated economic loss in USD
- `response_time_hours` : Time taken for initial response (hours)
- `aid_amount_usd` : Amount of aid distributed in USD
- `response_efficiency_score` : Response effectiveness score
- `recovery_days` : Number of days required for recovery
- `latitude` : Latitude of disaster location
- `longitude` : Longitude of disaster location

> Source: Kaggle (public dataset).  
> Dataset link: https://www.kaggle.com/datasets/zubairdhuddi/global-daset
> The dataset is not included in this repository to comply with Kaggle data redistribution policies.

## Methodology
1. Data loading and initial inspection  
2. Data cleaning and validation  
3. Handling missing values, duplicates, and outliers  
4. Date conversion and feature extraction  
5. Vulnerability index analysis  
6. Exploratory Data Analysis (EDA):
   - Time-based analysis
   - Distribution analysis
   - Correlation analysis  
7. K-Means clustering and cluster interpretation  

## Clustering Approach
- Feature scaling and normalization
- Determination of optimal number of clusters
- K-Means implementation
- Cluster labeling and interpretation

## Tools & Technologies
- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Project Structure
notebooks/ → analysis notebook
data/ → dataset (not uploaded)

## Output
- Clustered global disaster events
- Exploratory visualizations
- Interpretation of disaster vulnerability patterns

## Author
elokbian23104
