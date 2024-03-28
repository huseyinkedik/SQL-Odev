1- actor ve customer tablolarında bulunan first_name sütunları için tüm verileri sıralayalım.
```
SELECT customer.first_name, actor.first_name FROM actor
FULL JOIN customer ON actor.actor_id=customer.customer_id;
```
2- actor ve customer tablolarında bulunan first_name sütunları için kesişen verileri sıralayalım.
```
SELECT customer.first_name, actor.first_name FROM actor
INNER JOIN customer ON actor.actor_id=customer.customer_id;
```
3- actor ve customer tablolarında bulunan first_name sütunları için ilk tabloda bulunan ancak ikinci tabloda bulunmayan verileri sıralayalım.
```
SELECT customer.first_name, actor.first_name FROM actor
LEFT JOIN customer ON actor.actor_id=customer.customer_id;
```
4- İlk 3 sorguyu tekrar eden veriler için de yapalım.
```
SELECT customer.first_name FROM customer
UNION ALL 
SELECT actor.first_name FROM actor;
```
