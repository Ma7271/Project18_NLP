Recipe Recommendation System

This project focuses on developing a recommendation system based on recipe datasets, using a combination of content-based and collaborative filtering approaches. The system includes sentiment analysis, clustering, and hybrid recommendation techniques, leveraging both user reviews and recipe content.

There are 14 Task assigned to this project. The code of Task 1 to Task 11 is found in Project18_0.ipynb.

file Pr18_Q12.ipynb contains the code of Task 12.
file Pr18_Q14.ipynb contains the code of Task 14 (the code is not completed).

Data Files

RAW_recipes.csv: Contains recipe details like name, id, minutes, tags, ingredients, etc.
RAW_interactions.csv: Contains user interactions including user_id, recipe_id, rating, and review.


RAW_interactions_filtered.csv: filtered version of RAW_interactions.csv. it is used to speed up the process and reduce the processing time

RAW_recipes_filtered.csv: filtered version of RAW_recipes.csv. it is used to speed up the process and reduce the processing time


Usage:
First run Reduce_size_of_data_set.ipynb. This code reduce the size of the data set RAW_recipes.csv,and RAW_interactions.csv by filtering the recipes that has less than 10 ratings. This code generates the new data sets RAW_recipes_filtered.csv,and RAW_interactions_filtered.csv. These new data sets have less data and in this way we can process the data sets faster

In order to generate the plots and the tables only run the code assigned to each Task, it is easy to identify because in each code the number of the task is at the beginning of the code.


For Task 14, the code is not working, It needs to perform a debug, but was not possible due to the running time takes a lot because of the length of the data set.

