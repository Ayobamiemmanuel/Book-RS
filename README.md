# Book Movie Recommendation System using Item-Item Collaborative Filtering
# Overview
This is a project I built using collaborative filtering to recommend books based on users' ratings. The goal of this project was to build a personalized recommendation system that suggests books to users based on their individual tastes and preferences (ratings). This project aims to build a book recommendation system using collaborative filtering technique. The system is designed to provide users with personalized recommendations based on their past ratings and preferences. The datasets used for this project are books.csv and ratings.csv. The books.csv file contains information about books such as the book ID, authors, publication year, title, and ratings. The ratings.csv file contains user ID, book ID, and corresponding ratings.

# Methodology:

The collaborative filtering technique used in this project is item-item based. This approach recommends books to users based on the similarity between the books. The idea is that if a user likes a particular book, they are likely to enjoy other books that are similar to it. To achieve this, we first create a matrix that represents the ratings of each user for each book. We then calculate the similarity between books using cosine similarity. Once the similarity matrix is obtained, we predict the ratings for the books that the user has not rated.

# Reasons for Using Item-Item Based Collaborative Filtering:
 I chose item-item based collaborative filtering because it has been proven to be effective in providing accurate recommendations to users. This approach focuses on the similarities between items (in this case, books) rather than users. It is more scalable than user-user based collaborative filtering because it requires less computation and can handle large datasets. Additionally, it avoids the problem of recommending unpopular items that may have high similarity to a user's preferences but have very few ratings.

# Libraries Used:

The following libraries were used in this project:

Pandas
NumPy
Scikit-learn
Seaborn
NLTK

# Conclusion:

This project demonstrates the effectiveness of collaborative filtering-based recommendation systems in providing personalized book recommendations to users. The item-item based collaborative filtering approach is an efficient and scalable method for providing accurate recommendations based on the similarities between books.
