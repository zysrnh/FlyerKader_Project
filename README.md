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
│   ├── poster-h7-glass-4x5.png
│   ├── poster-h7-dark-4x5.png
│   ├── poster-h7-modern-4x5.png
│   ├── poster-h7-layout2-neubrutalism-4x5.png
│   ├── poster-h7-layout2-neubrutalism-9x16.png
│   ├── poster-h7-layout2-glass-4x5.png
│   ├── poster-h7-layout2-dark-4x5.png
│   ├── poster-h7-layout2-modern-4x5.png
│   ├── poster-coming-soon-neubrutalism-4x5.png
│   ├── poster-coming-soon-glass-4x5.png
│   ├── poster-coming-soon-layout2-neubrutalism-4x5.png
│   ├── poster-coming-soon-layout2-glass-4x5.png
│   ├── poster-h7-layout3-neubrutalism-4x5.png
│   ├── poster-h7-layout3-modern-4x5.png
│   ├── poster-h7-layout3-glass-4x5.png
│   ├── poster-h7-layout3-dark-4x5.png
│   └── poster-coming-soon-layout3-modern-4x5.png
└── archive/            # Eksplorasi desain sebelumnya (H-3)
```

## Fitur di `index.html`

- **Switcher Layout:** `Layout 1 (Countdown Card)`, `Layout 2 (Retro Pop-up)`, dan `Layout 3 (Bubble Pop — Biru HIMA IF)`
- **Mode / Preset Konten:** `H-7`, `H-3`, `H-1`, `HARI H`, dan **`COMING SOON` (tersedia di Layout 1, 2, maupun 3 — tanpa tanggal/lokasi)**
- **Switcher Style (Semua Layout & Mode):** `Neubrutalism` (default), `Glassmorphism`, `Dark Code`, dan `Modern Clean`
- **Multi-Rasio IG:** `4:5 Feed (1080x1350)`, `9:16 Story (1080x1920)`, dan `1:1 Square (1080x1080)`
- **Edit Teks & Logo Live:** Judul acara, tanggal, jam, lokasi, CTA, IG handle, serta upload logo ke-3 opsional di Layout 2
- **Export PNG 1080px:** Menggunakan native HTML5 Canvas 2D renderer tanpa library eksternal
