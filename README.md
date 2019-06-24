# Capstone/Thesis
SMU Capstone project - a comparative evaluation of recommender systems for hotels
by Ryan Khaleghi, Raghuram Srinivas (advisor)

Purpose:
Building on previous work by R. Srinivas, this analysis is to compare two recommender systems models, Collaborative Filtering and Matrix Factorization. The goal is to measure processing time and accuracy and determine which model is superior. After that is established, to determine whether small increases in review numbers can have an impact on the accuracy of the collaborative filtering model, or if the model requires a relatively large number of reviews to see any accuracy gain.


Steps:
Load dataset and features. 
Perform EDA and deal with missing values.
Transform review text feature into numerical 1-5 rating to match other ratings from users.
(Review text was handled using a TF-IDF Vectorizer and Linear Support Vector Machine to classify review texts as numerical scores.)
Add transformed review text scores into dataframe.
Create the collaborative filtering and matrix factorization models.
Compare the processing speed and accuracy between the models.
Separate dataframe by number of entries per user to create multiple dataframes with different review counts per user.
Create and compare collaborative filtering accuracy results using these dataframes.


Next steps:
Future work is the Neural Network NLP project, where I handle these same review texts using neural networks to see if I can improve on the accuracy obtained from the TF-IDF/SVM model.
