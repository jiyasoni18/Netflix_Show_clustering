# Netflix_Show_clustering
🎬 Netflix Movie Clustering using K-Means
This project applies unsupervised machine learning to cluster Netflix shows based on their attributes like genre, duration, and rating using the K-Means Clustering algorithm.

Project Objective
To analyze and group Netflix titles into meaningful clusters using K-Means, enabling better content insights and genre categorization.

📂 Dataset
The dataset includes Netflix movie/show titles with attributes such as:

title, rating, genre, duration, release_year

⚙️ Technologies Used
Python, Pandas, NumPy, Matplotlib / Seaborn, Scikit-learn (KMeans, StandardScaler)

🔍 Key Steps
Data Cleaning & Preprocessing
Removed null values
Encoded categorical features
Normalized numeric values (duration, rating)
K-Means Clustering
Elbow method used to determine optimal number of clusters
Applied KMeans to group movies into clusters
Data Visualization
Bar plots of average rating per cluster
Top genres per cluster

📊 Cluster Insights
After applying K-Means, the dataset was divided into 4 clusters with the following characteristics:

Cluster 0:
🎵 Mostly Music & Musicals and Comedies → Likely musical/comedy content

Cluster 1:
🎭 High counts of Dramas and International Movies with long durations → Heavy/intense films

Cluster 2:
👨‍👩‍👧‍👦 Dominated by Children & Family genres with short durations → Short kids/family content

Cluster 3:
📺 Very short duration and high rating-encoded (TV-MA) → Aftershows or Netflix originals
