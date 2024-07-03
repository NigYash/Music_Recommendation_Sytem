# Music Recommendation System

### Data retrieval and preprocessing: 
The code uses the Spotify API to fetch track data from a specified playlist, including audio features, popularity, and release dates. It then preprocesses this data, scaling numeric features and calculating weighted popularity scores based on release dates.

### Content-based recommendation: 
The code implements a content-based recommendation function that uses cosine similarity on scaled audio features to find songs similar to a given input track.

### Hybrid recommendation system: 
The code combines content-based recommendations with popularity-based filtering to create a hybrid recommendation system. It uses both audio feature similarity and weighted popularity scores to generate and rank song recommendations for a given input track.
