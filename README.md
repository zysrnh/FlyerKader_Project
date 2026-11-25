# FlyerKader_Project

Poster Countdown Studio untuk kegiatan **Kaderisasi — HIMA Informatika (IDE LPKIA) • Kabinet Aksara Nirmana**.

## Struktur Folder

```text
FlyerKader_Project/
├── index.html          # Poster Studio interaktif (standalone, siap buka di browser / GitHub Pages)
├── assets/
│   ├── logo-hima.png   # Logo HIMA Informatika
│   ├── logo-lpkia.jpg  # Logo IDE LPKIA
│   └── akaab.jpeg      # Logo Kabinet Aksara Nirmana (aktif di Layout 1–5)
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
│   ├── poster-coming-soon-layout3-modern-4x5.png
│   ├── poster-h7-layout4-neubrutalism-4x5.png
│   ├── poster-h7-layout4-glass-4x5.png
│   ├── poster-h7-layout4-dark-4x5.png
│   ├── poster-h7-layout4-modern-4x5.png
│   ├── poster-coming-soon-layout4-modern-4x5.png
│   ├── poster-h7-layout5-neubrutalism-4x5.png
│   ├── poster-h7-layout5-glass-4x5.png
│   ├── poster-h7-layout5-glass-9x16.png
│   ├── poster-h7-layout5-dark-4x5.png
│   ├── poster-h7-layout5-modern-4x5.png
│   ├── poster-coming-soon-layout5-glass-4x5.png
│   ├── poster-live-report-neubrutalism-4x5.png
│   ├── poster-live-report-layout2-dark-4x5.png
│   ├── poster-live-report-layout3-glass-4x5.png
│   ├── poster-live-report-layout4-modern-4x5.png
│   ├── poster-live-report-layout5-glass-4x5.png
│   └── poster-live-report-layout5-glass-9x16.png
└── archive/            # Eksplorasi desain sebelumnya (H-3)
```

## Fitur di `index.html`

- **Switcher Layout:** `Layout 1 (Countdown Card)`, `Layout 2 (Retro Pop-up)`, `Layout 3 (Bubble Pop — Biru HIMA IF)`, `Layout 4 (IG Feed Stack)`, dan `Layout 5 (Pinned Note — Mading Pin 3D)`
- **3 Logo Resmi Terintegrasi:** `HIMA Informatika`, `IDE LPKIA`, dan `Kabinet Aksara Nirmana` terpasang di seluruh Layout 1–5 (plus opsional override logo ke-3 di Layout 2)
- **Mode / Preset Konten:** `H-7`, `H-3`, `H-1`, `HARI H`, **`COMING SOON`**, dan **`LIVE REPORT (Frame Bolong 1–5)`** — bagian tengah frame otomatis transparan (`RGBA alpha = 0`) siap ditempel foto/story di Instagram/Canva/CapCut, lengkap dengan field **Label Live** (`LIVE REPORT`, `ON AIR`, dll) & **Judul / Topik Live** yang bisa diubah-ubah serta opsional upload foto preview/composite
- **Switcher Style (Semua Layout & Mode):** `Neubrutalism` (default), `Glassmorphism`, `Dark Code`, dan `Modern Clean`
- **Multi-Rasio IG:** `4:5 Feed (1080x1350)`, `9:16 Story (1080x1920)`, dan `1:1 Square (1080x1080)`
- **Edit Teks & Logo Live:** Judul acara, tanggal, jam, lokasi, CTA, IG handle, serta upload logo custom ke-3 di Layout 2
- **Export PNG 1080px:** Menggunakan native HTML5 Canvas 2D renderer tanpa library eksternal (otomatis mendukung transparansi alpha di mode Live Report)
