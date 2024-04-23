# SC1015-FDAD-TEAM-3

# TikTok Music Popularity Analysis 🎵

## Project Overview 🌟
This project explores the factors driving track popularity on TikTok, focusing on musical qualities, clustering analysis, and statistical validation. It aims to uncover the key elements contributing to a song's virality on TikTok, emphasizing that star power is not always necessary for success.

## Methodology ⚙️
The project employs a comprehensive approach, integrating several key analyses to reach its conclusions:

- **Exploratory Data Analysis (EDA)**: This step provides a preliminary examination of the dataset, identifying significant correlations and patterns. The analysis revealed a notable correlation between "artist_pop" and "track_pop," suggesting that artist popularity has a global impact on track success.

- **Feature Analysis with H2O AutoML**: Automated machine learning helped identify the most significant predictors of track popularity. This step confirmed that "artist_pop" is the most significant factor affecting "track_pop" globally.

- **Clustering Analysis**: K-Means clustering grouped songs based on musical qualities. The Elbow method helped determine the optimal number of clusters, suggesting a 3- or 4-cluster setup as optimal for further analysis.

- **T-Test Validation**: T-tests were used to assess the statistical significance of differences between clusters. This validation step confirms the distinctiveness of certain clusters and identifies key differentiators.

- **Text Analysis of Lyrics**: Planned future enhancement, involving scraping lyrics from the Genius API and performing text analysis to explore the relationship between lyrical content and musical elements.

## Key Insights 🔍
The project identifies several factors contributing to TikTok virality:

- **Energy and Loudness**: Tracks with high energy and loudness are more likely to capture attention on TikTok.
- **Danceability and Valence**: High danceability and positive sentiment in tracks align with the platform's dynamic and engaging content.
- **Distinct Tempo**: Certain tempo ranges are often associated with viral success, driving popular dance challenges and skits.

## Conclusion ✨
While traditional music platforms rely heavily on artist popularity, TikTok offers a level playing field where creativity, energy, and rhythm matter most. This project demonstrates that tracks can go viral on TikTok without relying solely on star power, highlighting the importance of unique musical qualities.

## Future Directions 🚀
The project plans to explore advanced feature engineering with text analysis of lyrics, focusing on the relationship between lyrical content and musical elements. By combining musical and textual analysis, the project aims to provide a more comprehensive understanding of what drives song virality on TikTok.

## How to Use This Repository 🛠️
- **Code**: This repository contains code for EDA, feature analysis, clustering, and statistical validation.
- **Data**: Sample data (if included) for reproducing the analyses.
- **Instructions**: Follow the README and additional documentation to understand the project's structure and run the analyses.
