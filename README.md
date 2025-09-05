# Creating-Cohorts-of-Songs-using-Machine-Learning-Techniques
#### 🎶 Spotify Song Clustering 🎧 From beats to vibes — this project cleans Spotify song data, explores features, reduces dimensions with PCA, and uses K-Means to group tracks into cohorts (chill, balanced, high-energy). Basically, a machine learning–powered playlist generator 🤖🎵.

## 📂 Project Overview
### Data Cleaning 🧹
#### Removed duplicates, handled missing values, and prepped the dataset.

### Exploratory Data Analysis (EDA) 🔍
#### Looked at distributions of features like danceability, energy, valence, loudness, popularity, etc.
#### Found cool patterns like: happy songs tend to be more danceable.

### Dimensionality Reduction (PCA) 🔮
#### Reduced 10+ features into 2D for visualization.
#### Captured the essence of songs as “energy vs mood/positivity.”

### Clustering (K-Means) 🗂️
#### Used the Elbow method → optimal k=3 clusters.
#### Song cohorts discovered:
#### *Cluster 0 → Balanced / Mid-energy Tracks* 🎤
#### *Cluster 1 → High-energy, Danceable Hits* ⚡
#### *Cluster 2 → Live & Intense Performances* 🎸

## 📊 Tech Stack
#### Python 🐍
#### pandas, numpy → data wrangling
#### matplotlib, seaborn → visualizations
#### scikit-learn → PCA + clustering

## 🖼️ Sample Visuals
#### The clusters of Co-horts formed from the data-set using K-means clustering.
#### <img width="679" height="547" alt="87e185c6-31a3-43cd-a4de-91acfcaedac2" src="https://github.com/user-attachments/assets/4fffa863-c4ce-424a-80db-9b5ed054febb" />
#### The elbow graph plotted to find the optimal number of clusters.
#### <img width="589" height="455" alt="6dab4898-a2f7-4ba8-8bd0-75e4b943d734" src="https://github.com/user-attachments/assets/3d5f51b8-0b1c-4a49-81be-c1d61c657e3f" />
#### The heatmap Plotted, to find the strenght of correlation between different features of the data-set.
#### <img width="1021" height="925" alt="81896f27-d1d4-4172-a47f-f14d5b5088b7" src="https://github.com/user-attachments/assets/42639554-9df9-4b45-864c-dd2a0eb91055" />

## 🎤 Insights & Fun
#### Popularity is not only about audio features → context (marketing, culture, timing) matters a lot.
#### But clustering shows hidden music groups (chill, balanced, high-energy) that explain styles & vibes.
#### You could totally use this as the foundation for your own AI playlist recommender 🎶.

## 🏆 Future Work
#### Try different clustering techniques (Hierarchical, DBSCAN).
#### Add lyrics-based sentiment analysis for richer clusters.



