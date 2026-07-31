AUTHENTICATION

| Tabel            | Fungsi                     |
| ---------------- | -------------------------- |
| users            | Menyimpan akun pengguna    |
| roles            | Daftar role                |
| permissions      | Hak akses                  |
| role_permissions | Relasi role dan permission |


MASTER DATA

| Tabel      | Fungsi        |
| ---------- | ------------- |
| categories | Kategori menu |
| products   | Data produk   |
| units      | Satuan produk |
| suppliers  | Supplier      |
| customers  | Customer      |

INVENTORI

| Tabel                | Fungsi                    |
| -------------------- | ------------------------- |
| inventories          | Stok saat ini             |
| stock_movements      | Riwayat stok masuk/keluar |
| purchase_orders      | Pembelian bahan           |
| purchase_order_items | Detail pembelian          |

SALES

| Tabel           | Fungsi                 |
| --------------- | ---------------------- |
| orders          | Header transaksi       |
| order_items     | Detail transaksi       |
| payments        | Pembayaran             |
| payment_methods | Cash / QRIS / Transfer |

KITCHEN

| Tabel          | Fungsi               |
| -------------- | -------------------- |
| kitchen_orders | Status pesanan dapur |

SYSTEM

| Tabel         | Fungsi                 |
| ------------- | ---------------------- |
| settings      | Pengaturan toko        |
| activity_logs | Log aktivitas pengguna |
