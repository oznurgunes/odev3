1)country tablosunda bulunan country sütunundaki ülke isimlerinden 'A' karakteri ile başlayıp 'a' karakteri ile sonlananları sıralayınız.<br><code>
select*from country
where country like 'A%a';</code><br>
2)country tablosunda bulunan country sütunundaki ülke isimlerinden en az 6 karakterden oluşan ve sonu 'n' karakteri ile sonlananları sıralayınız.<br><code>
select *from country
where country like '%n';</code><br>
3)film tablosunda bulunan title sütunundaki film isimlerinden en az 4 adet büyük ya da küçük harf farketmesizin 'T' karakteri içeren film isimlerini sıralayınız.<br><code>
select *from film
where title ilike '%t%t%t%t%';</code><br>
4)film tablosunda bulunan tüm sütunlardaki verilerden title 'C' karakteri ile başlayan ve uzunluğu (length) 90 dan büyük olan ve rental_rate 2.99 olan verileri sıralayınız.<br><code>
select *from film
where title like 'C%' and length>=90 and rental_rate=2.99;</code><br>

