# Skill: Scrape Produk Terlaris Shopee

## Tujuan
Mencari produk terlaris dari Shopee berdasarkan kategori yang ditentukan.

## Kategori Target
- Pakaian Dalam Wanita (komisi 7%)
- Perlengkapan Bayi (komisi 7%)
- Skincare & Beauty (komisi 7%)
- Aksesoris Hewan Peliharaan (komisi 6%)

## Kriteria Produk Bagus
- Rating minimal 4.5/5
- Minimal 100 terjual
- Minimal 50 review
- Harga Rp 20.000 - Rp 500.000 (sweet spot komisi)

## Output yang Diharapkan
Berikan daftar produk dalam format JSON:
```json
{
  "nama": "nama produk",
  "harga_min": 25000,
  "harga_max": 49000,
  "rating": 4.8,
  "terjual": 15000,
  "kategori": "Pakaian Dalam Wanita",
  "url_shopee": "https://shopee.co.id/...",
  "komisi_estimasi": 3430
}
```

## Catatan
- Fokus pada produk yang sudah terbukti laku (terjual banyak)
- Hindari produk elektronik mahal (komisi kecil)
- Prioritaskan produk dengan foto menarik
