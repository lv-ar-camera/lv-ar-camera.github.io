# Louis Vuitton · AR Camera (WebAR)

AR Camera di browser untuk 6 produk **Louis Vuitton**. Scan kartu QR dengan kamera HP (Android atau iPhone),
website terbuka, lalu animasi 3D muncul di atas kartu. Tidak perlu install aplikasi.

**Website:** https://lv-ar-camera.github.io/
**Kartu QR (lihat, download, cetak):** https://lv-ar-camera.github.io/cards/
**Preview tanpa kamera:** https://lv-ar-camera.github.io/?preview=1

| Kartu (`cards/`) | Produk |
|---|---|
| `Card_lv-keepall-50.png` | Keepall Bandoulière 50 |
| `Card_lv-tambour.png` | Tambour Watch |
| `Card_lv-neverfull-mm.png` | Neverfull MM |
| `Card_lv-trainer.png` | LV Trainer Sneaker |
| `Card_lv-malle-courrier.png` | Malle Courrier Trunk |
| `Card_lv-imagination.png` | Imagination Eau de Parfum |

## Isi

- `index.html`, `app.js`, `style.css`: halaman WebAR (MindAR 1.2.5 + three.js 0.160 dari CDN).
- `targets.mind`: data pelacakan 6 kartu (urutan sama dengan `models/products.json`).
- `models/*.glb` + `products.json`: model 3D dan parameter animasi yang diekspor dari project Unity.
- `cards/`: kartu QR + `Kartu-QR-LouisVuitton-A4.pdf` (6 kartu dalam 1 lembar A4).

Model 3D dan kartu adalah prototipe bergaya untuk tugas kuliah, bukan materi resmi Louis Vuitton.
