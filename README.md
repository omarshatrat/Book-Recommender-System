# Book-Recommender-System

This program takes in a list containing usernames, books read, and ratings.
It creates a dictionary with each user as a key and their list of ratings as a value.
Following this, the average review score for each book is calculated.
A similarity score for a given user is calculated by taking the dot product of their review scores (in vectorized form) with the review scores of other users. The dot products help identify to the user which other users have tastes most similar to theirs. 
The average rating for each book is then calculated using the values of the 3 most similar users.
Finally, the user receives a list of all books ordered by average similarity score, with a higher rating being more recommended to the user.
