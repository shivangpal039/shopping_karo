# Database Schema

## Users_Schema

- avatar
- _id
- name
- email
- password
- address
- phone
- role (customer, admin, delivery partner)
- browsing_history
- purchase_history

## Products_Schema

- _id
- name
- description
- price
- category
- stock_quantity
- image_url

## Orders_Schema

- _id
- user_id
- products (array of product IDs and quantities)
- total_price
- shipping_address
- billing_address
- payment_method
- order_status (pending, processing, shipped, delivered)
- delivery_partner_id (if assigned)

