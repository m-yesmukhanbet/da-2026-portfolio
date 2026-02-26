# SQL patterns notes (Week 1) — pattern + example

1) Filter rows: WHERE country = 'United States'
2) Sort: ORDER BY year DESC
3) Top N: ORDER BY population DESC LIMIT 5
4) Pagination: ORDER BY title LIMIT 5 OFFSET 5
5) Unique values: SELECT DISTINCT director FROM movies
6) Pattern match: WHERE name LIKE 'A%'   -- starts with A
7) Contains: WHERE title LIKE '%Story%'  -- contains Story
8) List filter: WHERE city IN ('Rome','Milan')
9) Group metric: SELECT country, COUNT(*) FROM cities GROUP BY country
10) Filter groups: ... GROUP BY country HAVING COUNT(*) >= 2
