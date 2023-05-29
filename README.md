# nosql-challenge
Module 12 No SQL Challenge by Mwohania (Nia) Taylor

Repo for UC Berkeley Data Analytics Bootcamp

## Background
The purpose of this activity was to analyze the best rated restaurants in the UK. The criteria was based upon the evaluated food hygiene rating for different establishments.

## Database and Jupyter Notebook Setup
1. Imported the establishment data to MongoDB
2. Use libraries specified in Jupyter notebook
3. Create a Mongo client instance
4. Confirm the creation of the database and data collection
5. Assigned the collection for further use

## Update the Database
1. Update the script in the notebook for "Penang Flavours"
2. Found the BusinessTypeID for " Restuarant/Cafe/Canteen" and return with the only fields
3. Updated the new restaurant with the obtained BusinessTypeID
4. Remove all establishments
5. The script updates fields to decimals and integers for further analysis

## Exploratory Analysis
Ensure that the notebook analyses the following:
- Establishments have hygiene score equal to 20
- Establishments in London have a rating higher than or equal to 4
- Top 5 establishments with a rating of 5 sorted from lowest hygiene score and nearest "Penang Falvours"
- Calculated the number of establihments in each local area with a hygiene score of 0
