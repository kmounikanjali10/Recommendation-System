 #Recommendation-System
A movie recommendation system is an application that suggests movies to users 
based on their preferences and viewing history. The system uses machine 
learning algorithms to analyze user data and provide personalized movie 
recommendations.

The system will consider various factors such as genre, director, actor, rating, 
and popularity to suggest relevant movies to the user.


To build a movie recommendation system, we can use a variety of techniques 
such as collaborative filtering, content-based filtering. The collaborative 
filtering technique analyses user behaviour to identify similar users and 
recommend movies that the user's peers enjoyed. 


The content-based filtering technique, on the other hand, uses features of the 
movie such as genre, director, and actor to suggest movies that are similar to the 
user's preferences.
![image](https://github.com/kmounikanjali10/Recommendation-System/assets/89678374/fd6ee0cc-640a-466c-aeb8-273674568fd5)




Building a movie recommendation system involves several steps:-
• data pre-processing
• model training
• deployment

![image](https://github.com/kmounikanjali10/Recommendation-System/assets/89678374/756e6980-9eda-4d4b-95c0-bac87597c747)

The data pre-processing step involves cleaning and formatting the data to 
prepare it for analysis. The data we are working is taken from Kaggle Dataset 
i.e., TMDB 5000 Movie Dataset. where this contains 2 dataset : 1. 
Tmdb_5000_credits.csv 2. Tmdb_5000_movies.csv .

After doing some basic Exploratory data analysis (EDA), we do text
vectorization in this step we convert the text tags of the movie into vectors.
Then the vectors are passed to cosine similarity.

We use the Cosine Similarity from Sklearn, as the metric to compute the 
similarity between two movies. Cosine similarity is a metric used to measure 
how similar two items are.
![image](https://github.com/kmounikanjali10/Recommendation-System/assets/89678374/c926d8dd-0800-4c12-80bb-efa39c30e35a)

The output value ranges from 0–1. 0 means no similarity, whereas 1 means 
that both the items are 100% similar.
![image](https://github.com/kmounikanjali10/Recommendation-System/assets/89678374/7ec677e3-4053-4f6e-88bb-ca06c952cfde)
![image](https://github.com/kmounikanjali10/Recommendation-System/assets/89678374/283013fc-5765-44fb-a50c-e938482a2afc)
