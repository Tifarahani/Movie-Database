# Movie-Database-ELT 
---
### Overview
Create an ETL pipeline using Jupyter Notebooks and PostgreSQL from raw data to SQL database.
Extracting data,Deleting bad data (corrupted or missing), removing duplicate rows, and consolidating columns. 
Using RegEx to parse data and transform text into numbers.Load: Export transformed data into a database 
### Resources
* Software: Python ,Anaconda, Jupyter Notebooks, PostgreSQL 
* Libraries: Pandas, SQLAlchemy, NumPy 
* Files: Wikipedia Json, Movie Database Metadata, and MovieLens Ratings
---
#### Deliverable 1: Write an ETL Function to Read Three Data Files

ltimately, we were able to clean, merge the datasets and export the two new tables into PostgreSQL by using Python. The final results created a movies table with 6,052 rows. A 17% reduction from the original of 7,311 and a ratings table with 26,024,289 rows.

![movies_query](https://github.com/Tifarahani/Movie-Database/blob/main/Resources/movies_query.png)

![ratings_query](https://github.com/Tifarahani/Movie-Database/blob/main/Resources/ratings_query.png)

**Practice File Results**

![Rating](https://github.com/Tifarahani/Movie-Database/blob/main/Resources/Images/Rating..png.png)

**Deliverable 4 File Results**

![11](https://github.com/Tifarahani/Movie-Database/blob/main/Resources/Images/11.png.png)
 
#### Deliverable 2: Extract and Transform the Wikipedia Data


#### Deliverable 3: Extract and Transform the Kaggle data


####  Deliverable 4: Create the Movie Database
---
### Result
After cleaning, merging the datasets and exporting the two new tables into PostgreSQL by using Python, the final results created a movies table with 6,052 rows. A 17% reduction from the original of 7,311 and a ratings table with 26,024,289 rows.
### Summary:
The process of reviewing the data and knowing what to "clean" was challenging, including cross comparison between the datasets, as well as, learning how to use RegEx to parse the text. This process can be applied to large data bases. I
