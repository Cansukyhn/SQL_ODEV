## Q1

``` sql

SELECT AVG (rental_rate) from film;

```

### A1 = 2.9800000000000000

## Q2

``` sql

SELECT COUNT(*) from film
WHERE title LIKE 'C%';

```

### A2 = 92

## Q3

``` sql

SELECT MAX (length) from film
WHERE rental_rate = 0.99;

```

### A3 = 184

## Q4

``` sql

SELECT COUNT (replacement_cost) FROM film
WHERE length > 150;

```

### A4 = 242