# MovieRecommendation
This is a demonstration of different machine learning algorithms through the lens of a movie recommendation system. Uses two categories of recommenders: Collaborative vs. Content-based

Content-Based
- Uses movielens.com dataset for tags and attributes for movies
- Uses pfidvectorizer on categories, tags, keywords, and title
- Cosine similarity function in order to match movies that are close to one another

Collaborative
- Uses same movielens dataset
- Compares user ratings in order to find "similar users"
- List of good recommendable movies extracted from the list of movies that "similar users" like
