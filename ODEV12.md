## Q1

``` sql

SELECT COUNT(*) FROM film
WHERE length >
(select  avg (length) FROM film);

```

## Q2

``` sql

SELECT COUNT(*) FROM film
WHERE length =
(select  max (length) FROM film);

```

## Q3

``` sql

(SELECT * FROM film
 WHERE rental_rate =(select min (rental_rate) FROM film)
ORDER BY rental_rate)
UNION
(SELECT * FROM film
 WHERE replacement_cost =(select min (replacement_cost) FROM film)
ORDER BY rental_rate);

```

## Q4

``` sql

SELECT customer_id,count(*) FROM payment
group by customer_id
order by count desc;
```