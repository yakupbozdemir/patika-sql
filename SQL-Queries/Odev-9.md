1. `
   SELECT city.city, country.country FROM country
   INNER JOIN city ON country.country_id = city.country_id;
   `

2. `
   SELECT payment.payment_id, customer.first_name, customer.last_name FROM payment
   INNER JOIN customer ON customer.customer_id = payment.customer_id;
   `   

3. `
   SELECT rental.rental_id, customer.first_name, customer.last_name FROM rental
   INNER JOIN customer ON rental.customer_id = customer.customer_id;
   `   