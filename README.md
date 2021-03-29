# Movies-ETL
We created a dataset for Amazing Prime.  For the challenge, Amazing Prime wants to keep it updated on a daily basis. We need to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. We will create a function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.

## Deliverables
For this challenge there are 4 main deliverables:
1. Deliverable 1: Create a ETL function that reads 3 data files.  This can be found in the ETL_function_test.ipynb file.
2. Deliverable 2: Created a "cleaned" Wiki dataset and converted to a pandas dataframe.  This can be found in the ETL_clean_wiki_movies.ipynb file.
3. Deliverable 3: We extract and transform the Kaggle metadata and the MovieLens rating data using our ETL function.  Please see ETL_clean_kaggle_data.ipynb file.
4. Deliverable 4: Created a the Movie Database in PostgreSQL. This is an add on tot he other code deliverables. This code is found as ETL_create_database.ipynb file.  I was also able to query the database to test the right amount of rows were copied overed.  See movies_query.png and ratings_query.png which are snap-shots of the database query counts found in the Resources folder.  

Note: I added the 3 files (Wikipedia data, Kaggle metadata, and the rating data)to the Resources folder.  I had to compress a few of them to add.  
