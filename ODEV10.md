## Q1

``` sql

SELECT city,country FROM city
LEFT JOIN country ON country.country_id = city.country_id ;

```

## Q2

``` sql

SELECT payment_id,first_name,last_name FROM customer
RIGHT JOIN payment ON payment.customer_id = customer.customer_id ;

```

## Q3

``` sql

SELECT rental_id,first_name,last_name FROM customer
FULL JOIN rental ON RENTAL.customer_id = customer.customer_id ;

```