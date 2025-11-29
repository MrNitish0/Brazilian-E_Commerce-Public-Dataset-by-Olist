# Brazilian-E_Commerce-Public-Dataset-by-Olist
  Brazilian E-Commerce Public Dataset by Olist:
https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce?resource=download
________________________________________
📦 What the dataset contains
It’s real transactional data from a large Brazilian e-commerce marketplace (Olist) covering 2016–2018. It has 100k+ orders, spread across multiple linked tables (CSV files).
Main tables:

1.	orders
o	Order ID, customer ID, order status, timestamps (purchase, approval, shipping, delivery, estimated delivery).
o	Key for analyzing order lifecycle.

2.	customers
o	Customer ID, ZIP code, city, state.
o	Enables demographic and regional segmentation.

3.	products
o	Product ID, category, dimensions, weight.
o	Enables category analysis and logistics insights (big/heavy products).

4.	sellers
o	Seller ID, ZIP, city, state.
o	Useful for marketplace supply-side analysis.

5.	order_items
o	Each item in an order, linked with price, freight value, seller ID, product ID.
o	Key for revenue calculations and logistics cost analysis.

6.	order_payments
o	Payment method, installments, payment value.
o	Lets you analyze consumer payment behaviors.

7.	order_reviews
o	Review scores, comments, timestamps.
o	Useful for customer satisfaction analysis.

8.	geolocation
o	Maps Brazilian ZIP codes to coordinates.
o	Lets you create maps of customer/seller distribution.

9.	product_category_translation
o	English translations of Portuguese category names.

