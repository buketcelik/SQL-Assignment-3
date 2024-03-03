# SQL-Assignment-3
1.	SELECT country FROM country
WHERE country LIKE 'A%a';

2.	SELECT country FROM country
WHERE country LIKE '%_ _ _ _ _n';

3.	SELECT title FROM film
WHERE title ILIKE '%T%T%T%T%';

4.	SELECT * FROM film
WHERE (length >90 AND rental_rate = 2.99) AND title LIKE 'C%';
