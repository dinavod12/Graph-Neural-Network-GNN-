# Graph-Neural-Network-GNN-
 Loading Graphs from CSV
Here, we will show how to load a set of *.csv files as input and construct a heterogeneous graph from it, which can be used as input to a heterogeneous graph model. 

We are going to use the Anime Dataset 2023 collected/Downloaded from the Kaggle. 

Context
Anime is a popular form of entertainment originating from Japan. It encompasses a wide range of animated TV series, movies, and OVAs (original video animations) that cater to various genres and target audiences. Anime is known for its distinctive art style, compelling storytelling, and diverse themes.
Anime covers a vast array of genres, including action, adventure, comedy, drama, romance, fantasy, sci-fi, and many more. Each genre offers unique storytelling elements and appeals to different preferences and interests among anime enthusiasts. It has gained significant popularity worldwide and has developed a dedicated and passionate fanbase. Fans of anime often engage in discussions, reviews, and rankings, contributing to the vibrant community surrounding this form of entertainment.
Due to the vast number of anime titles available, recommendations play a crucial role in helping enthusiasts discover new shows that align with their interests. Recommendation systems leverage user ratings, genres, and other factors to suggest anime series that users might enjoy based on their preferences.

Content
------------------------------------------ "anime-dataset-2023.csv" ----------------------------------------------
anime_id: Unique ID for each anime.
Name: The name of the anime in its original language.
English name: The English name of the anime.
Other name: Native name or title of the anime(can be in Japanese, Chinese or Korean).
Score: The score or rating given to the anime.
Genres: The genres of the anime, separated by commas.
Synopsis: A brief description or summary of the anime's plot.
Type: The type of the anime (e.g., TV series, movie, OVA, etc.).
Episodes: The number of episodes in the anime.
Aired: The dates when the anime was aired.
Premiered: The season and year when the anime premiered.
Status: The status of the anime (e.g., Finished Airing, Currently Airing, etc.).
Producers: The production companies or producers of the anime.
Licensors: The licensors of the anime (e.g., streaming platforms).
Studios: The animation studios that worked on the anime.
Source: The source material of the anime (e.g., manga, light novel, original).
Duration: The duration of each episode.
Rating: The age rating of the anime.
Rank: The rank of the anime based on popularity or other criteria.
Popularity: The popularity rank of the anime.
Favorites: The number of times the anime was marked as a favorite by users.
Scored By: The number of users who scored the anime.
Members: The number of members who have added the anime to their list on the platform.
Image URL: The URL of the anime's image or poster.
The dataset offers valuable information for analyzing and comprehending the characteristics, ratings, popularity, and viewership of various anime shows. By utilizing this dataset, one can conduct a wide range of analyses, including identifying the highest-rated anime, exploring the most popular genres, examining the distribution of ratings, and gaining insights into viewer preferences and trends. Additionally, the dataset facilitates the creation of recommendation systems, time series analysis, and clustering to delve deeper into anime trends and user behavior.

--------------------------------------------- "users-details-2023.csv" ------------------------------------------------
Mal ID: Unique ID for each user.
Username: The username of the user.
Gender: The gender of the user.
Birthday: The birthday of the user (in ISO format).
Location: The location or country of the user.
Joined: The date when the user joined the platform (in ISO format).
Days Watched: The total number of days the user has spent watching anime.
Mean Score: The average score given by the user to the anime they have watched.
Watching: The number of anime currently being watched by the user.
Completed: The number of anime completed by the user.
On Hold: The number of anime on hold by the user.
Dropped: The number of anime dropped by the user.
Plan to Watch: The number of anime the user plans to watch in the future.
Total Entries: The total number of anime entries in the user's list.
Rewatched: The number of anime rewatched by the user.
Episodes Watched: The total number of episodes watched by the user.
The User Details Dataset provides valuable information for analyzing user behavior and preferences on the anime platform. By examining mean scores and anime genres, you can gain insights into user preferences. Users can be segmented into different groups based on their watching behavior, such as active users and casual viewers. Personalized recommendation systems can be built using users' completed and plan-to-watch lists. Location-based analysis reveals anime popularity and user engagement in various countries. Trends in watching behavior, user retention, and gender-based differences in anime preferences can be identified. Additionally, you can explore rewatching habits and perform time series analysis to understand user engagement patterns over time.

---------------------------------------------- "users-score-2023.csv" -------------------------------------------------
user_id: Unique ID for each user.
Username: The username of the user.
anime_id: Unique ID for each anime.
Anime Title: The title of the anime.
rating: The rating given by the user to the anime.
The User Score Dataset enables various analyses and insights into user interactions with anime. By examining user ratings for different anime titles, you can identify highly-rated and popular anime among users. Additionally, you can explore user preferences and watch patterns for specific anime titles. This dataset also forms the foundation for building recommendation systems based on user ratings, helping to suggest anime that align with individual tastes. Furthermore, you can perform collaborative filtering and similarity analysis to discover patterns of similar user interests. Overall, this dataset offers valuable information for understanding user engagement and preferences on the anime platform.


You can download dataset using this link --- https://www.kaggle.com/datasets/dbdmobile/myanimelist-dataset.
