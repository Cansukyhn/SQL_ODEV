## Q1

``` sql

SELECT city,country FROM country
INNER JOIN city ON city.country_id = country.country_id ;

```

## Q2

``` sql

SELECT payment_id,first_name,last_name FROM payment
INNER JOIN customer ON customer.customer_id = payment.customer_id ;

```

## Q3

``` sql

SELECT rental_id,first_name,last_name FROM rental
INNER JOIN customer ON customer.customer_id = rental.customer_id ;

```