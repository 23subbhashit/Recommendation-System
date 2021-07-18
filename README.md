# Recommendation-System
Built different types of Recommendation System

- Popularity-Based Recommender :This system used the overall Number of Rating and VMean Rating to find the top 10 productIds. The IMDB Weighted Rating System was used to calculate scores on which the sorting was finally performed.
- Collaborative Filtering:  Used the powerful Surprise Library to build a collaborative filter based on single value decomposition. The RMSE obtained was about 1.29 and the engine predicted estimated ratings for a given user and product.
- Hybrid Engine:  Combined corrwith() method which computed the Pearson correlation coefficients with collaborative filtering. My hybrid recommender took useId and productId as input and suggested up to 5 products that were similar to the input productId based on the estimated ratings that was internally calculated for the input userId.
