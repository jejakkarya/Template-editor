# Template Editor · Jejak Karya

Editor slide carousel Instagram untuk Jejak Karya. Semuanya jalan di browser: tulis teks, upload foto atau objek PNG, atur ukuran dan warna, lalu download PNG per slide atau ZIP semua slide.

Buka versi GitHub Pages-nya: https://jejakkarya.github.io/template-editor/

## Template

- **Teks Saja**: teks utama di tengah, plus catatan kaki.
- **Teks + List**: judul dan bullet list yang rapi otomatis.
- **Teks + Foto**: judul di atas, foto dengan sudut membulat di tengah (bisa zoom dan geser).
- **Teks + Objek**: judul, objek PNG transparan tanpa bingkai, dan teks quote di bawahnya.

## Cara format teks

| Tulis | Hasil |
|---|---|
| `*kata*` | Tebal + warna sorot (default biru Jejak Karya) |
| Blok kata → klik bulatan warna | Ganti warna kata itu aja |
| Blok kata → "Tebal…" | Ganti ketebalan kata itu aja |
| Blok kata → "Miring" | Miringkan kata itu aja |
| `\*` | Tanda bintang biasa |
| Enter | Baris baru (Enter 2x = jarak paragraf) |

## Catatan

- Hasil editan tersimpan di browser masing-masing (IndexedDB), jadi nggak ikut pindah ke perangkat lain.
- Jumlah slide bebas: tambah, duplikat, hapus, dan geser urutan lewat thumbnail.
- Peringatan muncul kalau teks nabrak logo, catatan kaki, atau keluar canvas.
- Font: Plus Jakarta Sans dan Gabarito (lisensi OFL), plus Futura CXB dan FootSans dari Trivia Editor.
