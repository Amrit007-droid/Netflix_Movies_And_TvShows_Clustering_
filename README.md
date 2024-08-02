
![Netflixbillboard700](https://github.com/user-attachments/assets/89a59870-232f-4305-9b36-e642affb3b41)

# Unsupervised ML: Netflix Movie and TV Show Clustering

## Industry Context

The entertainment industry, particularly the streaming sector, is highly competitive. Companies like Netflix, Amazon Prime, and Hulu are constantly seeking ways to enhance user experience and increase subscriber retention. Clustering movies and TV shows can help these platforms in several ways

## Project Overview

- The aim of this project is to analyze the Netflix Dataset of movies and TV shows until 2019, sourced from the third-party search engine Flixable.
- The goal is to group the content into relevant clusters using NLP techniques to improve the user experience through a recommendation system. This will help prevent subscriber churn for Netflix, which currently has over 220 million subscribers.

## Attribute Descriptions

- show_id - Unique ID for every Movie/Tv Show.

- type - Identifier- A Movie or Tv Show.

- title - Title of the Movie/Show.

- director - Director of the show.

- Cast - Actors involved.

- Country - Country of Production.

- date_added - Date it was added on Netflix.

- release_year - Actual release year of the show.

- rating - Tv rating of the Show.

- duration - Total duration in minutes or number of seasons.

- listed_in - Genre.

- Description - The summary description.

## Steps Involved

### Data Collection
- Used the dataset from AlmaBetter Project Section which includes comprehensive information about Netflix content.

### Data Wrangling

- Handling Null values from each feature
- Handling nested columns i.e 'director', 'cast', 'listed_in' and 'country'
- Merging all the unnested dataframes
- Typecasting of attributes
- Binning of rating attribute
- Separating Movies and TV Shows

### Storytelling & Experimenting with charts: EDA

- Content Distribution: Analyzed how content is distributed over Netflix.
![Screenshot (196)](https://github.com/user-attachments/assets/88467a33-dce9-4480-baf1-79c1c6df79ee)

- Top Actors: Identified top actors performing in movies and TV shows.
![Screenshot (197)](https://github.com/user-attachments/assets/b69e82a2-c43f-445e-b9d9-8bf6b44c743d)

- Top Directors: Identified top directors directing movies and TV shows.
![Screenshot (198)](https://github.com/user-attachments/assets/1a7107ee-9f05-437e-bff9-d48ab8c6a2f9)

- Top 10 Countries: Found the top 10 countries involved in content creation.
![Screenshot (199)](https://github.com/user-attachments/assets/c39acc79-54cd-4149-8263-ebf19b3e4265)

- Country Spread: Determined which countries have the highest spread of movies and TV shows on Netflix.
![Screenshot (200)](https://github.com/user-attachments/assets/e536d278-ffe3-4e8f-8931-23c041b570c1)

- Popular Genres: Analyzed which genres are popular on Netflix.
![Screenshot (201)](https://github.com/user-attachments/assets/08469e7c-37e8-466b-b7b4-10745900602a)

- Yearly Releases: Calculated the total number of movies/TV shows released and added per year on Netflix.
![Screenshot (202)](https://github.com/user-attachments/assets/349c18e3-71c5-44ac-aacc-e3acec6a46e6)

- Monthly Additions: Calculated the total number of movies/TV shows added per month on Netflix.
![Screenshot (203)](https://github.com/user-attachments/assets/f05e1f7f-7e05-41b7-9587-572d56155143)

- Correlation Heatmap: Created a heatmap to show the distribution of content rating in each of the highest content-creating countries.
![Screenshot (204)](https://github.com/user-attachments/assets/565f3b8c-67f0-4114-a9f5-10362b46eaad)

## Hypothesis Testing : 
Based on the chart experiments, I defined three hypothetical statements from the dataset.

## Dimesionality Reduction - PCA Analysis
![Screenshot (205)](https://github.com/user-attachments/assets/a03ba32e-2cd5-4f7b-9859-c3cf5cf9e615)

## ML Model - 1 (K-Means Clustering)
![Screenshot (206)](https://github.com/user-attachments/assets/73c8492f-eebe-4343-9934-ca61ebbd7010)

## ML Model - 2 (Hierarchial Clustering)
![Screenshot (207)](https://github.com/user-attachments/assets/1e4df230-e3d3-48fd-ac39-552aab6ca1b1)

## Recommender system
![Screenshot (209)](https://github.com/user-attachments/assets/7950d046-3d65-4a8e-ab4a-491f34d711dc)

### Built a Recommendation system that can help Netflix improve user experience and reduce subscriber churn by providing personalized recommendations to users based on their similarity scores.


