1. **What is Recommender System?**



A recommender system automatically suggests relevant items to users based on their past behavior, preferences, or similarities with other users.



**2. Types of Recommender System?**



There are three main types of recommender system given below

* &#x20;Content Base Recommender System
* &#x20;Collaborative Recommender System
* &#x20;Hybrid Recommender System



**Content Base Recommender System:**

&#x09;			This system suggests items to users based on the features and attributes of items the user has liked in the past. It creates a user profile by analyzing item characteristics such as genre, color, price, or keywords. The system then recommends similar items that match this user profile without requiring data from other users.

**Example:** If a user likes action movies, the system recommends other action movies with similar actors or directors.



**Collaborative Recommender System:**

&#x09;			 This system suggests items by finding users with similar preferences and behaviors. It assumes that if user A and user B have rated items similarly in the past, they will have similar tastes in the future. The system recommends items that similar users have liked, without analyzing the actual content or features of items.

**Example:** If User A and User B both liked movies X and Y, and User A also liked movie Z, the system recommends movie Z to User B.



**Hybrid Recommender System:**

&#x09;		  Hybrid recommender system combines both content-based and collaborative filtering methods to overcome their individual limitations. It can use different approaches like weighting predictions from both systems, switching between methods based on conditions, or building a unified model that incorporates both item features and user similarities. 

**Example:** Netflix uses a hybrid approach to handle cold-start problems while providing diverse and personalized recommendations to millions of users.





**3. Problem Statement**

Users face information overload while choosing movies from thousands of options. This system solves the problem by recommending relevant movies based on:

\- Movie genres, cast, crew, keywords

\- User ratings and viewing patterns



**4. Goal:**

&#x20;    To build a content-based movie recommender system that suggests 5 most similar movies to any given movie based on features like genres, cast, crew, title ,id ,keywords and overview using cosine similarity algorithm.



**5. Dataset:**

&#x20;	   Source: TMDB 5000 Movie Dataset (Kaggle)

&#x20;	   Total Movies: 5,000+

**6. Features Used:** 

&#x20; 		 Title, Genres, Cast, Crew, Keywords, Overview, id





