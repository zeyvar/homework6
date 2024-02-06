# homework6
aggregate fonksiyonlar ödev 6

--SORU 1
SELECT ROUND(AVG(rental_rate),3) FROM film

cevap'2.980'

--SORU 2
SELECT COUNT(*) FROM film
where title LIKE'C%'

cevap '92'

-- SORU 3
SELECT MAX(length) FROM film
WHERE rental_rate=0.99

cevap'184'

--SORU 4
SELECT COUNT(replacement_cost) from film
where length>150

cevap '242'
