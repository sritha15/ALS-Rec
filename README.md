# ALS-Rec

I did This small mini-project to build a recommendation system for recommending moisturizers to users using collaborative filtering using ALS matrix factorization. ALS considers rating into account when finding the latent features. Currently, I considered product_id, author_id, and rating for building the matrix, later I plan to make it a hybrid model to address the cold start problem and consider more features in the background for better prediction. The dataset I have used is a Sephora dataset. 

For testing purposes, I am currently building my dataset to test the performance of the recommendation system using RMSE/MSE. Given the Author_ID (user), the recommendation system gives a top 5 product_id that can be used to retrieve the top 5 recommendations for a user based on similar user preferences. This recommendation system doesn't solve the cold start problem yet, and I am about to experiment with using LLama 2 to deal with a cold start problem.

Link to Datasets: https://www.kaggle.com/datasets/nadyinky/sephora-products-and-skincare-reviews
