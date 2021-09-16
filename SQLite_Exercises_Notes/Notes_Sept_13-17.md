## What I'm doing in the exercises:

Sept. 16, 2021:
- Currently, starting on Chapter 7 of the book!
- Functions: are speacial keywords that accept certain parameters, perform an operation, and return the result of tat operation as a value (page 188).
  - *String functions*: modeify character and text-based data.
  - *Date functions*: modify time and date data.
  - *Aggregate functions*: perform mathematical operations.   
- String: another word for text data stored in a text-based data type. 
  - Concatenation: joining fields together. To do this, use two-pipe || operator. 
  - LENGTH(): counts the number of characters there are in a string.
  - SUBSTR():  
    - SUBSTR(X, Y): returns all characters through the end of the string X beginning with the Y-th.
    - SUBSTR(X,Y,Z): returns a substirng pf input string X that begins with the Y-th character and that is Z characters long.  


Sept. 15, 2021:
- Inner Joins with More Than Two tables:joins can combine more than two tables. 
- Using NOT, IS, and NULL with Left Outer Join: 
  - Specific SQL keywords: 
    - IS NULL in a WHERE clause would return only values that were null
    - NOT NULL would return only values that were not null  

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
