1.Book-recommender-system:

  A book recommender system is a type of a type of recommendation system where we have to recommend similar books to the reader based on his interest.
  
  In this project, we will implement the populartity based recommender system and collabrative based recommender system to build a book recommender system.
  
2.Dataset description:

 we have three files in our dataset which is extracted from some books selling websites. 

1] Books: first file contains about books which contain all the information releated to books like an author, title, publication year, etc.

2] Users: The second file contains registerd users information like user, id, location.

3] Ratings: Ratings contain information like which user has given how much rating to which book.

Here is the link for the dataset: https://www.kaggle.com/datasets/rxsraghavagrawal/book-recommender-system

3.Popularity based recommender system:

For implementing popularity based recommender system we will display the top 50 books with the highest average rating.

But we will only consider thoes books which have got greater than 250 votes.

Here is the top 50 books with the rating greater than 250.

![Screenshot (61)](https://user-images.githubusercontent.com/105923718/226258570-045c853d-2136-4990-9376-993aed0b8a35.png)

4.Collabrative based recommender system: 

A big flow with a problem statement in the datset is, if we take all the books and all the users for modelling don't you think it will crete problem? so, what we have to do is we have to decrease the number of users and books beacause we can not consider a user who only registered on the website or has read only one or two books on such user we cannot rely to recommend books.

so what we will limit this number and we will take a user who has rated at least 200 books and take only thoes books which have received at least 50 ratings from user.

5.Modeling:

We have prepared our datset for modelling. we will use the cosine similarity algorithm.

In cosine simalarity text is converted into a vector and with the help of cosine disance we identify the nearest vector.

The closer the vector is the more similar the books are.

Let's see the suggested books

![Screenshot (63)](https://user-images.githubusercontent.com/105923718/226262925-c60f1529-6ed3-423c-83e7-b6e1a291525f.png)

Here is the final output







