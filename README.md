# 🎬 TMDB Movie Dataset Clustering with PySpark  

## 📌 Overview  
This project applies **unsupervised machine learning** to the **TMDB Movie Dataset** using **PySpark**. The aim is to explore patterns in movie data by clustering films based on numerical attributes such as budget, popularity, runtime, ratings, and revenue. Dimensionality reduction techniques like PCA are used to visualize high-dimensional clusters effectively.  

## 📊 Dataset  
- **Source**: TMDB Movie Dataset (`TMDB_movie_dataset_v11.csv`)  
- **Features Used**:  
  - Budget  
  - Popularity  
  - Runtime  
  - Vote Average  
  - Vote Count  
  - Revenue  

## ⚙️ Methodology  
1. **Data Cleaning**  
   - Removed nulls and negative values.  
   - Outlier handling using **IQR filtering**.  

2. **Feature Engineering & Scaling**  
   - Assembled numeric features into vectors.  
   - Scaled features to [0, 1] using **MinMaxScaler**.  

3. **Clustering**  
   - Implemented **KMeans** clustering to group movies.  
   - Evaluated using **Silhouette Score**.  

4. **Dimensionality Reduction & Visualization**  
   - Applied **PCA** for 2D visualization.  
   - Plotted clusters with **Matplotlib/Seaborn**.  

## 📈 Results  
- Successfully grouped movies into clusters with similar production and audience metrics.  
- PCA visualization highlights distinct groupings, revealing insights into movie characteristics (e.g., high-budget blockbusters vs. low-budget independent films).  

