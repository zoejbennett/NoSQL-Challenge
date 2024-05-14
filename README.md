# NoSQL-Challenge

This repository evaluates the hygiene ratings data shared by the UK Food Standards Agency. The evaluation aims to aid the journalists and food critics of the fictional UK food magazine Eat Safe, Love on where to focus future articles.
The first portion of the code, found in the file 'NoSQL_setup_starter.ipynb' updates the database, adding a new restaurant called 'Penang Flavours'. The file also filters out data not useful to the magazine, in this case, establishments based in Dover. The file removes all restaurants that fall under the authority of the Dover Local Authority. The last step to prepare the database for analysis is to update the the type of values stored, changing the location and rating value data from strings to decimal and integer numbers respectively.

After the database has been cleaned and filtered, the analysis is conducted in the file 'NoSQL_analysis-starter.ipynb.' 
The following questions are answered: 
  1. Which establishments have a hygiene score equal to 20?
  2. Which establishments in London have a Rating Value greater than or equal to 4?
  3. What are the top 5 establishments with a Rating Value of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
  4. How many establishments in each Local Authority area have a hygiene score of 0?

To answer each of these questions, the code first provides the count of how many establishments in the database fit the criteria. Next, a pandas DataFrame is created to showcase the data in a digestible format. 
