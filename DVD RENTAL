1 Task
SELECT 
     CASE WHEN director = '-' THEN 'not given' ELSE director END AS director
FROM MOVIES

2 Task 
SELECT date_added,
           CASE WHEN EXTRACT (MONTH FROM DATE_ADDED) = 1 THEN 'JAN'
		   --Go thought the rest
		        WHEN EXTRACT (MONTH FROM DATE_ADDED)= 9 THEN 'SEP'
				-- Gothrough the rest
				WHEN EXTRACT (MONTH FROM DATE_ADDED) = 12 THEN 'Dec'
			END AS month_added
FROM movies

3 Task
SELECT
CASE
WHEN duration LIKE '%Season%' THEN 'TV Series'
ELSE 'Movies'
END AS title_type
FROM MOVIES

4 Task
SELECT CONCAT ('RATING_1', 'RATING_2') AS RATING
FROM MOVIES

5 Task 
SELECT
-- QUERY FRO QUESTION 1
CASE
WHEN DIRECTOR = '-' THEN 'not given'
ELSE director
END AS director,

 --Quary for question 1
 CASE
WHEN director = '-' THEN 'not given'
ELSE director
END AS country,

---QUERY FOR QUESTION 2
CASE WHEN EXTRACT (MONTH FROM DATE_ADDED) = 1 THEN 'JAN'
--Go thought the rest
WHEN EXTRACT (MONTH FROM DATE_ADDED)= 9 THEN 'SEP'
-- Gothrough the rest
WHEN EXTRACT (MONTH FROM DATE_ADDED) = 12 THEN 'Dec'
END AS MONHT_ADDED,
DATE_ADDED,
---- QUERY FOR QUESTION 3
release_year,
case when duration like '%Season%' then 'TV Series'
ELSE 'Movies'
eND AS TITLE_TYPE,
---- QUERY FOR QUESTION 4/5
CONCAT (RATING_1,'-',RATING_2) AS rating, duration

