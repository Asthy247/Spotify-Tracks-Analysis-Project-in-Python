# Spotify-Tracks-Analysis-Project-in-Python

This project aims to explore and visualize a dataset containing information about various Spotify tracks. 

The primary goal is to gain insights into song characteristics, identify patterns, and understand how features correlate with each other.

# Research Questions

**What are the characteristics of the most and least popular songs in terms of audio features and duration?**

**How do different audio features (e.g., danceability, energy) correlate with each other?**

**Is there a relationship between popularity and other song characteristics (e.g., duration, acousticness)?**

**How has the average duration of songs changed over time?**

# Data Acquisition:

The project utilizes a Spotify Tracks dataset downloaded from Kaggle (https://lnkd.in/gkZpKDbt).

# Analysis and Results

# Data Cleaning: 
Initial checks are performed to identify and handle missing values.

# Exploratory Data Analysis
We identify the 10 least and most popular songs based on their popularity score.

We analyze descriptive statistics of various features like popularity, duration, and audio features (danceability, energy, etc.).

We explore specific relationships between features like:

Popularity vs. Duration

Loudness vs. Energy

Popularity vs. Acousticness

# Data Transformation
Song duration is converted from milliseconds to seconds for better interpretation.

# Data Visualization

# Histograms are used to display the distribution of song duration.

![image](https://github.com/user-attachments/assets/fef9265d-4105-4d30-9013-6f736bd4dbd6)

**Key Observations:**

**Peak Around 200 Seconds:** The histogram shows a distinct peak around the 200-second mark, indicating that a significant number of 
songs on the platform have a duration of approximately 3-4 minutes.


 **Long Tail:** The distribution is right-skewed, with a long tail extending towards higher durations. 
 This suggests that there are a smaller number of longer songs, such as extended mixes, remixes, or live performances.

 
**Mode:** The mode of the distribution is around 200 seconds, confirming the most frequent duration.

# Heatmaps are created to visualize correlations between numerical features.


![image](https://github.com/user-attachments/assets/564697f7-86e5-43ae-8e6a-9b441e173052)

**Key Observations from the Heatmap:**

**Positive Correlations:**

**o	Popularity and Duration:** There's a weak positive correlation, suggesting that longer songs tend to be more popular.

**o	Energy and Loudness:** These two features are highly correlated, indicating that louder songs are generally more energetic.

**o	Danceability and Energy:** There's a moderate positive correlation, suggesting that danceable songs are often energetic.

**Negative Correlations:**

**o	Acousticness and Energy:** There's a strong negative correlation, indicating that acoustic songs tend to have lower energy levels.

**o	Instrumentalness and Speechiness:** These two features are negatively correlated, suggesting that songs with more instruments tend to have less spoken word content.

**o	Liveness and Acousticness:** There's a negative correlation, indicating that live performances are less likely to be acoustic.

**Weak Correlations:**

o	Many features have weak or no correlation with each other, suggesting that they might capture different aspects of music.


# Scatter Plot for Loudness vs. Energy Scatter Plot

![image](https://github.com/user-attachments/assets/c04f9e2a-98cc-4f23-ac85-40ca0251c4b6)

**Key Observations:**

**Positive Correlation**: The scatter plot clearly shows a positive correlation between loudness and energy. As energy increases, loudness also tends to increase.

**Cluster Formation:**The data points seem to form clusters or bands, suggesting that certain combinations of loudness and energy are more common than others.

**Outliers:** There are a few data points that deviate significantly from the main trend, which could be considered outliers.

**Implications:**

**•	Audio Feature Relationships**:The positive correlation indicates that energetic songs are often also louder. 

This relationship can be exploited in music recommendation systems or audio analysis tasks.

# Answers to Research Questions

**Popularity:**

Most popular songs tend to be shorter in duration and have higher danceability, energy, and potentially lower acousticness.

Least popular songs may exhibit a wider range of characteristics.

**Feature Correlations:**

A positive correlation exists between features like danceability and energy, suggesting that energetic songs are often danceable.

A negative correlation might be observed between acousticness and features like energy, implying that acoustic songs tend to have lower energy.

**Popularity and Other Characteristics:**

A weak positive correlation might exist between popularity and duration, suggesting slightly longer songs may be more popular.

A negative correlation is observed between popularity and acousticness, implying listeners tend to prefer less acoustic (more energetic) tracks.

**Duration Over Time:**

Time series analysis of average song duration can reveal trends in song length across different release years.

# Recommendations

**Further Exploration:** Analyze additional features (e.g., valence, tempo) and their relationships with popularity and other features.


**Clustering:** Group songs based on similar characteristics to identify distinct musical styles.


**Predictive Modeling:** Develop models to predict popularity based on audio features and other song characteristics.

# Conclusion
This Spotify Tracks analysis project provides valuable insights into song characteristics and their relationships.

The findings can be used for various purposes, including music recommendation system development, understanding listener preferences, 

and informing music production strategies. By extending the analysis and exploring further research questions, 

we can gain a deeper understanding of music trends and user behavior on Spotify.
