**✅ Project Overview:**
 
-  This project demonstrates SQL query applications for analyzing movie data. It includes practical exercises to retrieve, filter, and sort data based on release year, rating, and studio, making it a great reference for learning SQL in real-world scenarios.
  
-  The reports in this project were inspired by the Codebasics SQL learning module and adapted to provide structured insights through SQL queries.

   ****

 
**✅ SQL Concepts Used:**

-  SQL Clauses: ORDER BY, WHERE, HAVING

-  SQL Operators: IN, BETWEEN, LIKE, !=


   ****
  
 
**✅ Included Reports:**  
   
  Each report corresponds to an SQL query exercise:
 
1️⃣ [Movies Sorted by Release Year](https://github.com/DataSagar/-Movie-Data-Analysis-with-SQL-Queries/blob/main/report_1.1.pdf)

-    Retrieves all movies ordered latest first.

-    Query : SELECT 
title, release_year
FROM movies
ORDER BY release_year DESC;



2️⃣ [Movies Released in 2022](https://github.com/DataSagar/-Movie-Data-Analysis-with-SQL-Queries/blob/main/report_2.1.pdf)

-    Filters movies only from the year 2022.

-    Query : SELECT 
title, release_year
FROM movies
WHERE release_year = 2022;



3️⃣ [Movies Released After 2020](https://github.com/DataSagar/-Movie-Data-Analysis-with-SQL-Queries/blob/main/report_3.1.pdf)

-    Retrieves movies released after 2020.

-    Query : SELECT 
title, release_year
FROM movies
WHERE release_year > 2020;



4️⃣ [Movies After 2020 with IMDb Rating > 8](https://github.com/DataSagar/-Movie-Data-Analysis-with-SQL-Queries/blob/main/report_4.1.pdf)

-    Filters movies released after 2020 with a rating higher than 8.

-    Query : SELECT 
title, release_year,imdb_rating
FROM movies
WHERE release_year > 2020
HAVING imdb_rating > 8;



5️⃣ [Movies by Marvel Studios & Hombale Films](https://github.com/DataSagar/-Movie-Data-Analysis-with-SQL-Queries/blob/main/report_5.1.pdf)

-    Selects movies produced only by these studios.

-    Query : SELECT 
title,studio
FROM movies
WHERE studio in ('Marvel studios' , 'Hombale Films');


6️⃣ [All THOR Movies Sorted by Release Year](https://github.com/DataSagar/-Movie-Data-Analysis-with-SQL-Queries/blob/main/report_6.1.pdf)

-    Retrieves only THOR movies, sorted chronologically.

-    Query : SELECT 
title,release_year
FROM movies
WHERE title like '%thor%'
ORDER BY release_year ASC;


7️⃣ [Movies Not from Marvel Studios](https://github.com/DataSagar/-Movie-Data-Analysis-with-SQL-Queries/blob/main/report_7.1.pdf)

-    Selects movies excluding Marvel Studios productions.

-    Query : SELECT 
title,studio
FROM movies
WHERE studio != 'Marvel Studios';


