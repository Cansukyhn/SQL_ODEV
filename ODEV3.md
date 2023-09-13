## Q1

``` sql

SELECT * FROM country
WHERE country LIKE 'A%a';

```

## Q2

``` sql

SELECT * FROM country
WHERE country LIKE '_____n%';

```

## Q3

``` sql

SELECT * FROM film
WHERE title ILIKE '%T%T%T%T';

```

## Q4

``` sql

SELECT * FROM film
WHERE title LIKE 'C%'AND length >90 AND rental_rate=2.99;

```