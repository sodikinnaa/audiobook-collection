# Audiobook Laravel Pengantar Tidur 🎧😴

Repositori ini berisi generator audiobook pengantar tidur dari e-book **"Belajar Laravel Untuk Pemula"** karya Dadan Hamdani (2015).

## 📁 Struktur Folder
```text
audiobook/
├── books/
│   └── Belajar Laravel Untuk Pemula.pdf   # E-book PDF asli
├── audio/
│   └── Laravel_Pengantar_Tidur.mp3        # File Audiobook MP3 pengantar tidur
├── scripts/
│   └── create_bedtime_audiobook.py        # Script Python pembuat TTS (Voice: Sebastian/actor51)
├── .gitignore
└── README.md
```

## 🛠️ Prasyarat & Cara Menjalankan

1. **Install dependensi Python:**
   ```bash
   pip install edge-tts
   ```

2. **Jalankan script:**
   ```bash
   python3 scripts/create_bedtime_audiobook.py
   ```

Selamat mendengarkan & selamat tidur tanpa bug! 🌙
