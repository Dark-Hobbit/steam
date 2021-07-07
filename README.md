# Steam Data Analysis
## Overview
Video games are a huge industry nowadays, with millions of people playing games every day. The main platform for distributing games made for PC is Steam, for which there is a lot of data freely available. The goal of this project is to research Steam data for insights on the behaviour of its users and how it differs for various games.

Without much surprise, the analysis is going to pay special attention to the games I personally have an interest in. That encompasses mostly strategies as they are my long-time favourite genre, and particularly the games created by the Paradox Development Studio - my favourite game creator.

## Kaggle data analysis
Before going through the effort of gathering the data ourselves let us first explore the existing Steam datasets from Kaggle. While they might not always match the questions perfectly, there are still some insights to be extracted.

The data is not going to be stored on GitHub since some of the files can be rather large in size. Instead, each file will have an ID in the name indicating its source.

### Dataset 1
The first dataset contains information on actions of individual people separated into buying games and playing game, with the amount of hours played. Aggregating the data to a game-level with the number of copies bought, games launched and hours played showed a number of potential insights to some of the tendencies that the games follow in terms of popularity. In particular, the interest seems to be heavily shifted towards a smaller number of very popular games, with the top one having more play time than the the first 75% quantile combined. Paradox Development Studio games also showed pretty good results, particularly so for the newer games. For full information, check out the kaggle_1.ipynb notebook.

## Dataset 2
The second dataset contains summary information on games. That includes general information (name, release date, genres, etc.), review ratings, play time for the past two weeks and estimated number of owners. While we are primarily interested in the numeric indicators, the categoric ones can be used for data visualisations or Machine Learning models.

## Materials used
1. https://www.kaggle.com/tamber/steam-video-games
2. https://www.kaggle.com/nikdavis/steam-store-games