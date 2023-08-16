1. `
   SELECT rating, COUNT(*) FROM film
   GROUP BY rating
   ORDER BY COUNT(*);
   `

2. `
   SELECT replacement_cost, COUNT(*) FROM film
   GROUP BY replacement_cost
   HAVING COUNT(*) > 50
   ORDER BY COUNT(*);
   `   

3. `
   SELECT store_id,Count (*) FROM customer
   GROUP BY store_id;
   `   

4. `
   SELECT country_id, COUNT(*) FROM city
   GROUP BY country_id
   ORDER BY COUNT(*) DESC;
   `   