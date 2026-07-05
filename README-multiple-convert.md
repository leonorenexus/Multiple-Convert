# ⚡ MULTIPLE CONVERT

Hy There 🫵 Selamat datang di project ke sekian, **Pai Leonore**.

> _"satu file masuk, format apapun keluar — gak lewat server manapun."_

![status](https://img.shields.io/badge/status-live-f5a623?style=flat-square)
![stack](https://img.shields.io/badge/stack-HTML%20%2F%20JS-7c3aed?style=flat-square)
![backend](https://img.shields.io/badge/backend-none-22d3ee?style=flat-square)
![privacy](https://img.shields.io/badge/privacy-100%25%20client--side-ff2fb2?style=flat-square)

---

## // WHAT IS THIS

Sebuah image converter + resizer yang jalan sepenuhnya di browser. Gak ada file yang pernah kekirim ke server manapun — semua proses convert dan resize terjadi langsung di HP/browser lu lewat Canvas API.

---

## // KONVERSI YANG DIDUKUNG

Setiap pasangan format punya jalurnya sendiri:

| Dari | Ke | Status |
|---|---|---|
| SVG | PNG | ✅ Didukung |
| SVG | JPG | ✅ Didukung |
| SVG | WEBP | ✅ Didukung |
| PNG | JPG | ✅ Didukung |
| PNG | WEBP | ✅ Didukung |
| JPG | PNG | ✅ Didukung |
| JPG | WEBP | ✅ Didukung |
| WEBP | PNG | ✅ Didukung |
| WEBP | JPG | ✅ Didukung |
| PNG | SVG | ❌ Gak didukung |
| JPG | SVG | ❌ Gak didukung |

> **Kenapa raster (PNG/JPG) gak bisa jadi SVG?**
> SVG itu format vector (garis & bentuk matematis), sedangkan PNG/JPG itu raster (kumpulan pixel). Ubah pixel jadi vector butuh proses "tracing" yang kompleks (bukan sekadar ganti ekstensi) — di luar scope tool ini. Semua converter online sejenis punya batasan yang sama.

---

## // FITUR RESIZE

- Input **width** & **height** manual (px)
- Toggle **lock aspect ratio** — ubah salah satu, yang lain auto-nyesuain, gak gepeng
- Quality slider (khusus output JPG/WEBP — PNG selalu lossless)

---

## // KENAPA TANPA BACKEND

| Aspek | Keterangan |
|---|---|
| Privasi | File gak pernah ninggalin device lu |
| Kecepatan | Convert instant, gak nunggu upload/download ke server |
| Biaya | Gratis selamanya, gak ada quota API |
| Uptime | Selama browser jalan, tool ini jalan — gak tergantung status server manapun |

Login/gate di halaman awal itu **cosmetic doang** — gak ada akun atau database beneran, cuma tampilan biar konsisten sama identitas Leonore Tech Team.

---

## // STACK

| Layer | Tech |
|---|---|
| Frontend | Plain HTML / CSS / JS (no build step) |
| 3D Background | Three.js |
| Image Processing | Canvas API (native browser) |
| Hosting | Vercel / GitHub Pages |

---

## // STRUCTURE

```
└── index.html     # seluruh app — UI, convert logic, resize, nebula bg
```

---

## // PART OF THE LEONORE STACK

Satu lagi tool dari deretan project yang dibangun 100% dari HP, tanpa PC, tanpa Android Studio — bareng [VAULT](#), [COSMIQ DEPLOY](#), [MediaLink Pro](#), dan [DRAGONIC LAS VEGA](#).

---

<sub>⚡ built by <b>Pai Leonore</b> & Leonore Tech Team — Renn · Raa · Void · Leora · Daemon</sub>
