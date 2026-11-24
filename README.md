# FlyerKader_Project

Poster Countdown Studio untuk kegiatan **Kaderisasi — HIMA Informatika (IDE LPKIA)**.

## Struktur Folder

```text
FlyerKader_Project/
├── index.html          # Poster Studio interaktif (standalone, siap buka di browser / GitHub Pages)
├── assets/
│   ├── logo-hima.png   # Logo HIMA Informatika
│   └── logo-lpkia.jpg  # Logo IDE LPKIA
├── exports/            # Hasil export PNG siap posting
│   ├── poster-h7-feed-4x5.png
│   ├── poster-h7-story-9x16.png
│   ├── poster-h7-dark-4x5.png
│   └── poster-h7-modern-4x5.png
└── archive/            # Eksplorasi desain sebelumnya (H-3)
```

## Fitur di `index.html`

- **Switcher Style:** `Neubrutalism` (default), `Dark Code`, dan `Modern Clean`
- **Multi-Rasio IG:** `4:5 Feed (1080x1350)`, `9:16 Story (1080x1920)`, dan `1:1 Square (1080x1080)`
- **Preset & Edit Teks Live:** `H-7`, `H-3`, `H-1`, `HARI H`, tanggal, jam, lokasi, dan stempel acara
- **Export PNG 1080px:** Menggunakan native HTML5 Canvas 2D renderer tanpa library eksternal
