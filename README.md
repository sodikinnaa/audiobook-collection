# 📚 Collection of Audiobooks (Koleksi Audiobook E-Book) 🎧😴

Repositori ini adalah koleksi e-book yang dikonversi menjadi **Audiobook MP3** (termasuk versi pengantar tidur/bedtime story) menggunakan Text-To-Speech. Setiap e-book memiliki folder tersendiri.

---

## 📁 Struktur Repositori

```text
audiobook-collection/
├── laravel-untuk-pemula/
│   ├── Belajar Laravel Untuk Pemula.pdf   # E-book PDF
│   ├── Laravel_Pengantar_Tidur.mp3        # Audiobook MP3 Pengantar Tidur
│   └── create_bedtime_audiobook.py        # Script Python Generator TTS (Voice: Sebastian/actor51)
├── [ebook-lainnya]/                      # Folder e-book berikutnya...
├── .gitignore
└── README.md
```

---

## 📖 Daftar E-Book & Audiobook

### 1. Belajar Laravel Untuk Pemula
- **Penulis**: Dadan Hamdani (2015)
- **Lokasi Folder**: [`laravel-untuk-pemula/`](./laravel-untuk-pemula/)
- **Voice Preset**: Sebastian (`actor51`) - *Warm & Soothing*
- **Cara Menjalankan Generator**:
  ```bash
  pip install edge-tts
  python3 laravel-untuk-pemula/create_bedtime_audiobook.py
  ```

---

Selamat mendengarkan & selamat tidur tanpa bug! 🌙
