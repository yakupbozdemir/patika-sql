1. `
   SELECT city.city, country.country FROM country
   LEFT JOIN city ON city.country_id = country.country_id;
   `

2. `
   SELECT payment.payment_id, customer.first_name, customer.last_name FROM payment
   RIGHT JOIN customer ON payment.customer_id = customer.customer_id;
   `   

3. `
   Select rental.rental_id, customer.first_name, customer.last_name FROM customer
   FULL JOIN rental ON rental.customer_id = customer.customer_id;
   `   