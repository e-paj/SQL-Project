## What I'm doing in the exercises:

Sept. 14, 2021:
- Joins: a command that combines the field from two ro more tables of a relational database. 
  - ON operator: provides the query with the link between the two tables. 
  - Inner Join: only returns matching records. any unmatched data from either table is ignored. 
  - Left Outer Join: combines all the records from the left tbale with any matching records from the right table.
  - Right Outer Join: returns the entire right table as well as matching information from the left table. 
- Normalization: the process of distributing fields across related tables. It keeps the sizes of databases smaller, as it reduces the need to have duplicate fields in the same table. 

Sept. 13, 2021:
- OPERATORS:
  - IN operator: used to find a list of precise values. Also allows us to find specific values within a dataset.
  - = operator only allows to find only one value. IN allows many values which have to be separated by a comma wrapped in a parenthesis.
  - When using text as criteria in the WHERE caluse, the text value must be surrounded by single quotes.
  - Wildcard characters will always be enclosed in a single quotation marks (page 123). 
    - Add only one % after the letter to look for any words that start with that letter.
    - Adding another % before the letter would change the search to look for any words that has that leeter anywhere un it. 
  - OR operator: allows to find the records that match any of teh criteria being asked for.
- DATE() Function: allows to exclude the time when specifying the date criteria.
- CASE Statement: allows to create a new, temporary field in the database that serves as a label for the data based on unique-specified conditions. 
