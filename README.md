-- 1
SELECT * FROM person WHERE salary NOT BETWEEN 2800 AND 2800;
-- 2
SELECT * FROM person WHERE degree LIKE '%MSc%' OR degree LIKE '%Yo%' AND (salary = 3100 OR salary = 2800);
-- 3
SELECT lname, city, salary FROM person WHERE bdate > '1994-01-01';
-- 4
SELECT * FROM person WHERE city LIKE 'T%';
-- 5
SELECT * FROM project WHERE pname LIKE '%RA%';
