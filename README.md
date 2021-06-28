# Movies-ETL
## This project was an introduction ot the EXTRACT, TRANSFORM, and LOAD process. Movie data from Wikipedia, Kaggle, and aggregated ratings was used to assemble a movie database from a clean dataset for a fictional hackathon.

#Overview

## The goal of this analysis is to create automated pipeline that extracts, transform and loads data = E.T.L.

## We were able to do this in four steps:

### 1: 

Data is extracted from the website in JSON and CSV formats.
Data is transformed into Pandas data frames.
JSON file requires extra step – loading file first and then transforming into data frame.

2: Clean Wiki movies using python list comphrehension , apply(), map() , and regex expressions/

3: Clean kaggle data fill missing values, merge data frames , change dtat types.

4: Create database using sqlalchemy, postgres and pg admin.
