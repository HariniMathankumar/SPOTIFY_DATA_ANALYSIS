<b>🎧 Spotify Data Analysis</b>
This project explores a dataset of Spotify tracks to uncover trends and patterns in song features, genres, and popularity. Through data cleaning, visualization, and statistical analysis, it answers questions like: What makes a song popular? Which genres are most danceable? How do audio features vary with popularity?

<b>📁 Dataset</b>
The dataset includes various attributes of songs such as:

danceability, energy, acousticness, valence, liveness, popularity, genre, etc.

Source: Spotify dataset (via Kaggle or Spotify API)

<b>🔍 Key Analyses & Visualizations</b>
✅ 1. Correlation Analysis
Used a heatmap to examine relationships between numerical audio features.

Found strong positive correlation between energy and loudness.

Noted negative correlation between acousticness and energy.

✅ 2. Popularity vs Audio Features
Regression plots showed:

Danceable and energetic songs tend to be more popular.

Highly acoustic songs are generally less popular.

✅ 3. Genre-wise Danceability
Bar plot of average danceability by genre revealed:

Genres like Pop, EDM, and Reggaeton score high on danceability.

Classical and ambient genres are on the lower end.

✅ 4. Popularity Binning Analysis
Created 4 popularity bins: 0-25, 26-50, 51-75, 76-100.

Calculated mean values of features across each bin.

<b>Area chart showed:</b>

Danceability and energy increase with popularity.

Acousticness decreases, indicating modern hits are less acoustic.

Valence (positivity) tends to be higher in popular tracks.

<b>📌 Key Insights</b>
Popular songs often have higher danceability, energy, and positivity.

Less popular tracks may be more acoustic or experimental in nature.

Genre plays a significant role in how features like danceability are distributed.

This type of analysis can aid in music recommendation engines, playlist curation, or even music production decisions.

<b>🛠️ Tools & Libraries Used</b>
Python, Pandas, NumPy

Matplotlib, Seaborn

Jupyter Notebook

<b>📄 Future Enhancements</b>
Add interactive visualizations with Plotly or Dash.

Perform clustering of songs based on audio features.

Integrate Spotify API for real-time track analysis.

