# SQL_Odev_9
--1--
SELECT city,country FROM city

INNER JOIN country ON city.city_id=country.country_id;

--2--
SELECT payment_id, first_name, last_name FROM customer

INNER JOIN payment ON payment.customer_id=customer.customer_id;-

--3--
SELECT rental_id, first_name, last_name FROM customer

INNER JOIN rental ON customer.customer_id=rental.customer_id;
