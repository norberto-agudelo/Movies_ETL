# Movies_ETL
#module 8
## Overview 

The purpose of this project is to apply the Data pipeline know as ETL (Extract, Transform an Load )  to create some data sets on a Postgres Data Base.  The ETL process is used to move data between different data bases.

In this case, a company, Amazon Prime Video is sponsoring a hackathon where the data sets to be used have two sources: data of movies released since 1990 from Wikipedia and rating data from the Movie Land’s website. The goal is extract data from those sources, transform it into one clean data set and load that data set into a SQL table that is going to be used in the hackathon.

In this project the company wants to keep the data set updated, so it is necessary to create an automated ETL pipeline that extract data from the sources stated before, performs some transformations to clean de data and finally load it into a new Data Base. 

 In this project we had to refactor the code used on previous lessons to create a function that extract data from three sources “—Wikipedia data, Kaggle metadata, and the MovieLens rating data —” transform it and load it into a PostgreSQL database.
