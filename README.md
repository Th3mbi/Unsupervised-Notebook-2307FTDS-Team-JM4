# Unsupervised-Notebook-2307FTDS-Team-JM4
## 1) Overview 
In today’s technology driven world, recommender systems are socially and economically critical for ensuring that individuals can make appropriate choices surrounding the content they engage with on a daily basis. One application where this is especially true surrounds movie content recommendations; where intelligent algorithms can help viewers find great titles from tens of thousands of options.

...ever wondered how Netflix, Amazon Prime, Showmax, Disney and the likes somehow know what to recommend to you?

![image](https://github.com/Th3mbi/Unsupervised-Notebook-2307FTDS-Team-JM4/assets/143552845/32454561-1c0a-49b5-b8e2-b22d6543818c)

..it's not just a guess drawn out of the hat. There is an algorithm behind it.

With this context, EA is challenging you to construct a recommendation algorithm based on content or collaborative filtering, capable of accurately predicting how a user will rate a movie they have not yet viewed based on their historical preferences.
## 2) Introduction
Recommender systems are amid the most well known applications of data science today. They are used to predict the "rating" or "preference" that a user would possibly give to an item. Recommender systems uses its techniques by searching through large volume of dynamically generated information to provide users with personalized content and services. Technically recommender system has the ability to predict whether a particular user would prefer an item or not based on the user’s profile.

The objective is to construct a recommender system that employs content or collaborative filtering approaches to accurately forecast a user's rating for a movie they haven't watched, leveraging their past preferences. The aim is to develop a robust and effective solution that holds substantial economic potential, as it enables users to discover and engage with content aligned with their interests, ultimately driving revenue and fostering loyalty to the platform.
## 3) Data Description
* genome_scores.csv - a score mapping the strength between movies and tag-related properties.
* genome_tags.csv - user assigned tags for genome-related scores.
* imdb_data.csv - Additional movie metadata scraped from IMDB using the links.csv file.
* links.csv - File providing a mapping between a MovieLens ID and associated IMDB and TMDB IDs.
* tags.csv - User assigned for the movies within the dataset.
* test.csv - The test split of the dataset. Contains user and movie IDs with no rating data.
* train.csv - The training split of the dataset. Contains user and movie IDs with associated rating data.
