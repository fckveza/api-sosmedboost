# API SosmedBoost

![Status](https://img.shields.io/badge/status-active-success)
![License](https://img.shields.io/github/license/fckveza/api-sosmedboost)

# 🌐 Social Media Booster API

API powerful untuk **meningkatkan follower, api YouTube, api follower,api view tiktok,api like tiktok free, like tiktok api, instagram followers,api instagram like, instagram like, like, view, komentar, dan engagement** di berbagai platform media sosial populer seperti **TikTok, Instagram, YouTube, Facebook, Twitter/X, dan lainnya**.

Dengan API ini, developer maupun pelaku bisnis bisa mengintegrasikan layanan **SMM (Social Media Marketing)** langsung ke aplikasi, website, atau sistem mereka.

---

## 🚀 Fitur Utama

- ✅ **Multi-Platform**: TikTok, Instagram, YouTube, Facebook, Twitter/X, Telegram, dan lain-lain.
- ✅ **Order Otomatis**: Tambah follower, like, view, komentar, subscriber hanya dengan satu request API.
- ✅ **Cek Saldo & Order**: Lihat saldo akun & status pesanan secara real-time.
- ✅ **Detail Layanan**: Ambil informasi layanan (harga, minimum order, kategori, dll).
- ✅ **Mudah Digunakan**: Mendukung request berbasis JSON dengan API Key & Secret Key.

---

#Base URL

https://sosmedboost.com/api/service

## 📌 Endpoint yang Tersedia

| Endpoint             | Deskripsi                                                                 |
| -------------------- | ------------------------------------------------------------------------- |
| `layanan`            | Mendapatkan semua daftar layanan (follower, like, view, dll).             |
| `get-layanan-detail` | Melihat detail spesifik layanan (harga, kategori, minimum, maximum, dll). |
| `get-balance`        | Mengecek saldo akun API Anda.                                             |
| `get-order-detail`   | Melihat status order berdasarkan ID transaksi.                            |
| `order-product`      | Membuat pesanan baru (contoh: beli follower, like, view, dll).            |

---

## 🔑 Autentikasi

Setiap request harus menggunakan header berikut:

```http
apiKey: YOUR_API_KEY
secretKey: YOUR_SECRET_KEY
Content-Type: application/json
```
