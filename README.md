# patika_sql_odev4
SELECT DISTINCT replacement_cost FROM film;
SELECT COUNT(DISTINCT replacement_cost) FROM film; --21tane
SELECT COUNT(*) FROM film WHERE title LIKE 'T%' AND rating = 'G'; --9
SELECT COUNT(*) FROM country WHERE country LIKE '_____'; --13
SELECT COUNT(*) FROM city WHERE city ILIKE '%r'; --33
