# ODEV6
1-  select round(avg(rental_rate),2) from film;

2- select count(title) from film
where title like ('C%');

3- select max(length) from film
where rental_rate=0.99;

4- select distinct(replacement_cost) from film
where length>150;
