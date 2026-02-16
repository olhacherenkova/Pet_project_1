# Pet_project_1

Дата сет складається з 4 таблиць.
Таблиця cosmetic_products_data складається з полів:
product_id 
product_name
product_category
product_weight_g
product_photos_qty

Таблиця cosmetic_order_data складається з полів:
order_id
order_purchase_date
order_status

Таблиця cosmetics_order_items_data складається з полів:
product_id
seller_id
price
order_id

Таблиця сosmetics_review_data складається з полів:
order_id
review_ratings
review_message
images_attached

Цей SQL-запит формує єдину таблицю, яка поєднує інформацію про замовлення, товари, продавців та відгуки клієнтів у контексті продажів косметики.
Pезультати запиту:
https://drive.google.com/file/d/1A70jCJ6hoWbI5P39V5AavY6oKQaIFWNs/view
