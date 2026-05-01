# Skill: Publish Artikel ke Blogger

## Tujuan
Mempublish artikel review yang sudah digenerate ke blog Blogger.

## Yang Dibutuhkan
- Blogger ID (angka panjang dari URL dashboard)
- Google OAuth credentials
- Token yang sudah disetup

## Proses Publish
1. Generate artikel menggunakan skill generate-artikel.md
2. Generate meta title dan description
3. Tentukan label/kategori artikel
4. Publish via Blogger API v3

## Label yang Digunakan
- Pakaian Dalam Wanita
- Perlengkapan Bayi
- Skincare & Beauty
- Hewan Peliharaan
- Review Produk
- Rekomendasi Shopee

## Jadwal Publish
- 1-2 artikel per hari
- Jangan publish lebih dari 5 artikel per hari (limit API)
- Selalu delay 15 detik antar publish

## SEO Tips
- Judul artikel max 60 karakter
- Meta description max 155 karakter
- Gunakan keyword long-tail yang spesifik
- Contoh: "bra wanita seamless untuk ibu menyusui" bukan "bra wanita"
