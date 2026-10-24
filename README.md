# Ruang Latihan TOEFL ITP

Website latihan TOEFL ITP berbasis satu halaman (HTML + CSS + JavaScript murni, tanpa build).

Fitur:
- **Listening** (Part A, B, C) dengan audio dari Text-to-Speech bawaan browser
- **Structure & Written Expression** per skill (kerangka Longman)
- **Reading** dengan teks bacaan dan penanda paragraf
- **Simulasi tes penuh** dengan timer dan konversi skor ITP
- **Flash card kosakata** dengan sistem kotak Leitner
- Riwayat skor dan progres tersimpan di browser (`localStorage`) masing-masing pengguna

## Menjalankan secara lokal

Cukup buka `index.html` di browser (Chrome atau Edge disarankan agar suara Listening tersedia).

## Deploy ke GitHub Pages

1. Buat repository baru di GitHub, misalnya `toefl-itp`.
2. Unggah isi folder ini (`index.html`, `README.md`, `.nojekyll`) ke repository tersebut.
3. Buka **Settings → Pages**, pada **Source** pilih **Deploy from a branch**, branch `main`, folder `/ (root)`, lalu **Save**.
4. Setelah 1–2 menit, situs dapat diakses di `https://<username>.github.io/toefl-itp/`.

## Catatan

- Audio Listening memakai Web Speech API, jadi kualitas dan jenis suara bergantung pada browser dan sistem operasi pengguna.
- Soal-soal di dalamnya disusun orisinal untuk latihan, bukan salinan dari buku atau tes resmi.
