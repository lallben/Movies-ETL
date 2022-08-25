# Movies-ETL
## Background
What started off as a project for a hackathon to inspire staff has turned into a dataset with other possibilities.<br>
Amazing Prime, the platform for streaming movies and TV shows now wants to keep the dataset updated on a daily basis. Britta, needs your help to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. 
## Objective
The objective of this project was to create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and perform the ETL process by adding the data to a PostgreSQL database.
## Source files
- Wikipedia data
- Kaggle metadata
- Movielens rating data
## The Process
### Step 1: Write an ETL Function to Read Three Data Files
The purpose of writing a function to read the three data files is to automate the ETL process and make sure that no one has to write all the code from scratch everytime. Writing a function to do this means that now we can do the work faster and efficiently.<br>
The file for the code can be found at [this link.](https://github.com/lallben/Movies-ETL/blob/main/ETL_function_test.ipynb)
### Step 2: Extract and Transform the Wikipedia Data
In the next step we refined and presented a comprehensive code to extraxt and transform the Wikipedia Data. This included a lot of work in the transformation of the data which involved cleaning it up to make it available in a way that it would make data analysis possible and have the cleanest data possible.<br>
The file for the code can be found at [this link.](https://github.com/lallben/Movies-ETL/blob/main/ETL_clean_wiki_movies.ipynb)
### Deliverable 3: Extract and Transform the Kaggle data
We then took the data retrirved from Kaggle and Movielens ratings data cleaned it up as well for the purposes stated above.<br>
The file for the code can be found at [this link.](https://github.com/lallben/Movies-ETL/blob/main/ETL_clean_kaggle_data.ipynb)
### Deliverable 4: Create the Movie Database
The final step was to write code that would take the data from Wikipedia and Kaggle, merged into one table called movies, and then export the movies and the ratings table into the SQL database.<br>
The file for the code can be found at [this link.](https://github.com/lallben/Movies-ETL/blob/main/ETL_create_database.ipynb)
We then ran a query in the database to confirm the # of rows for movies which was 6,052<br>
![Movie Query](https://github.com/lallben/Movies-ETL/blob/main/movies_query.png)
Another query was run to confirm the # of raows in the ratings table which was 26,024,289 <br>
![Ratings Query](https://github.com/lallben/Movies-ETL/blob/main/ratings_query.png)
## Summary
Mission Accomplished!
