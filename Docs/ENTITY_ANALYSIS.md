1. USER

Entity

User

Description

Pengguna yang dapat login ke sistem.

Attributes

id

role_id

name

email

password

phone

status

created_at


2. PRODUCT

Entity

Product

Description

Menu yang dijual.

Attributes

id

category_id

name

price

cost

stock

image

status

3. CATEGORY

Entity

Category

Description

Kategori menu.

Attributes

id

name

icon

status

4. COSTUMER

Entity

Customer

Description

Pelanggan.

Attributes

id

name

phone

point

status

5. SUPPLIER

Entity

Supplier

Description

Supplier bahan baku.

Attributes

id

name

phone

address

status

6. ORDER

Entity

Order

Description

Header transaksi.

Attributes

id

invoice

cashier_id

customer_id

payment_method

payment_status

total

discount

tax

grand_total

created_at

7. ORDER ITEM

Entity

Order Item

Description

Detail transaksi.

Attributes

id

order_id

product_id

qty

price

subtotal

8. PAYMENT

Entity

Payment

Description

Pembayaran transaksi.

Attributes

id

order_id

method

amount

status

paid_at

9. INVENTORY

Entity

Inventory

Description

Stok produk.

Attributes

id

product_id

stock

minimum_stock

10. Entity

Stock Movement

Description

Riwayat stok.

Attributes

id

product_id

type

qty

reference

user_id

11. KITCHEN ORDER

Entity

Kitchen Order

Description

Status pesanan dapur.

Attributes

id

order_id

status

start_at

finish_at

12. SETTINGS

Entity

Settings

Description

Konfigurasi toko.

Attributes

id

shop_name

address

phone

logo

qris_image

bank_name

bank_account

account_name

