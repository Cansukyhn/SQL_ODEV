## Q1

``` sql

SELECT rating FROM film
group BY rating;

```

## Q2

``` sql

SELECT replacement_cost , COUNT (*) FROM film
GROUP BY replacement_cost
HAVING COUNT(*) > 50;

```

## Q3

``` sql

SELECT store_id , COUNT(*) FROM customer
GROUP BY store_id;

```

## Q4

``` sql

SELECT country_id , COUNT (*) FROM city
group by country_id
ORDER BY COUNT (*) DESC;

```

### A3  country_id = 44 city = 60