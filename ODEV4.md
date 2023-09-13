## Q1

``` sql

SELECT DISTINCT replacement_cost FROM film;

```

## Q2

``` sql

SELECT COUNT (DISTINCT replacement_cost) FROM film;

```

## Q3

``` sql

SELECT COUNT (*) FROM film
WHERE title LIKE 'T%'AND rating='G';

```

## Q4

``` sql

SELECT COUNT (*) FROM COUNTRY
WHERE country LIKE '_____';

```

## Q5

``` sql

SELECT COUNT (*) FROM city
WHERE city ILIKE '%R';

```