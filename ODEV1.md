## Q1

``` sql

SELECT title , description FROM film;

```

## Q2

``` sql

SELECT * FROM film
WHERE length > 60 AND length <75;

```


## Q3

``` sql

SELECT * FROM film
WHERE rental_rate=0.99 AND (replacement_cost=12.99 OR replacement_cost=28.99) ;

```


## Q4

``` sql

SELECT first_name , last_name FROM customer
WHERE first_name = 'Mary';

```

## Q5

``` sql

SELECT * FROM film
WHERE not length > 50  AND( rental_rate !=2.99 AND rental_rate !=4.99);

```