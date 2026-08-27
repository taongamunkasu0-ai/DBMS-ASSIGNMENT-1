Primary Keys: category_id, product_id, customer_id, sale_id, sale_item_id.

Foreign Keys: products.category_id, sales.customer_id, sale_items.sale_id, sale_items.product_id.

'sale_items' records the many-to-many relationship between sales and products, including quantities and prices.
