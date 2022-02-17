# Q1

SELECT city, country 
FROM city
INNER JOIN country on city.country_id = country.country_id;

#Q2

SELECT payment_id, first_name, last_name 
FROM customer
INNER JOIN payment on customer.customer_id = payment.customer_id;

#Q3
SELECT rental_id, first_name, last_name 
FROM rental
INNER JOIN customer on rental.customer_id = customer.customer_id
