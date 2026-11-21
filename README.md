# 3000 Kalimat Bahasa Arab Populer — A1

Buka `index.html`. Isi: menu utama → daftar topik → pelajaran (topik 1–3), dan kuis (`quiz-1.html` … `quiz-32.html`).

## Suara
Secara bawaan suara memakai pembaca suara browser (ar-SA). Jika ingin rekaman asli, taruh file mp3 di folder `audio/` dengan nama:

- `NOMOR.mp3`  → kalimat (laki-laki / bentuk tunggal), contoh `14.mp3`
- `NOMORf.mp3` → bentuk perempuan, contoh `14f.mp3`
- `NOMORa.mp3` → ucapan A pada dialog, contoh `14a.mp3`
- `NOMORb.mp3` → ucapan B pada dialog, contoh `14b.mp3`

NOMOR = nomor kalimat di slide. Jika file tidak ada, otomatis kembali ke suara browser.

## GitHub Pages
Unggah seluruh isi folder ke repo → Settings → Pages → Deploy from branch → `main` / root.

## Membuat suara otomatis (gratis)
1. Pasang Python, lalu jalankan: `pip install edge-tts`
2. Letakkan `make_audio.py` dan `audio_list.csv` di folder yang sama dengan `index.html`
3. Jalankan: `python make_audio.py` → folder `audio/` terisi 2395 file mp3
4. Unggah folder `audio/` ke GitHub.
