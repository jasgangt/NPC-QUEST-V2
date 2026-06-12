<div align="center">

```
███╗   ██╗███████╗██╗  ██╗██╗   ██╗███████╗
████╗  ██║██╔════╝╚██╗██╔╝██║   ██║██╔════╝
██╔██╗ ██║█████╗   ╚███╔╝ ██║   ██║███████╗
██║╚██╗██║██╔══╝   ██╔██╗ ██║   ██║╚════██║
██║ ╚████║███████╗██╔╝ ██╗╚██████╔╝███████║
╚═╝  ╚═══╝╚══════╝╚═╝  ╚═╝ ╚═════╝ ╚══════╝
```

# NEXUS — Academic OS
### *Turn Your School Life Into a Mission*

![Version](https://img.shields.io/badge/version-v3.0-00aadd?style=flat-square&logo=none)
![Platform](https://img.shields.io/badge/platform-Web%20%7C%20Mobile-1248cc?style=flat-square)
![Language](https://img.shields.io/badge/built%20with-HTML%20%2F%20CSS%20%2F%20JS-cc44ff?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-00cc88?style=flat-square)
![Storage](https://img.shields.io/badge/storage-localStorage-dd2244?style=flat-square)

---

> **NEXUS Academic OS** adalah aplikasi manajemen belajar bergaya **cyberpunk / military-tech** yang mengubah kegiatan sekolah menjadi sebuah pengalaman seperti game. Atur jadwal, selesaikan misi tugas, naikkan rank, dan kelola perlengkapan sekolahmu — semua dalam satu platform.

</div>

---

## ⬇️ Download

<div align="center">

### 📦 [DOWNLOAD NEXUS v1.0.0 — MediaFire](https://www.mediafire.com/file/8ld56b5ye78wftj/NPC_QUEST_V2_v1.0.0.7z/file)

> Format: `.7z` — Extract lalu buka `school-quest.html` di browser HP/PC kamu

</div>

---

## 🖥️ Preview

```
┌─────────────────────────────────────────┐
│  NEXUS  ACADEMIC OS v3     MON 12.JUN   │
│  ◈ GOLD II                    340 XP    │
│  ████████████░░░░░░░░░░░░░░░░           │
├──────────────────────────────────────── ┤
│  // JADWAL                              │
│  [ SENIN ] [ SELASA ] [ RABU ] ...      │
│                                         │
│  ▌ Matematika        07:00 → 08:30      │
│  ▌ Fisika            08:30 → 10:00      │
│  ▌ Bahasa Indonesia  10:15 → 11:45      │
│                                         │
│  + INSERT PELAJARAN                     │
└─────────────────────────────────────────┘
```

---

## ✨ Fitur Utama

### 📅 Jadwal Pelajaran
- Atur jadwal **per hari** (Senin–Sabtu)
- Tambah mata pelajaran dengan **nama**, **jam mulai–selesai**, dan **warna label** custom
- Otomatis highlight hari ini dengan tag `NOW`
- Data tersimpan permanen, tidak hilang saat browser ditutup

---

### 🎯 Sistem Misi / Tugas
- Tambah tugas dengan **5 tingkat kesulitan**:

  | Level | Label | XP Reward | Deskripsi |
  |-------|-------|-----------|-----------|
  | 1 | 🟢 **EASY** | +5 XP | Latihan ringan |
  | 2 | 🔵 **NORMAL** | +15 XP | PR biasa |
  | 3 | 🟠 **MEDIUM** | +25 XP | Agak menantang |
  | 4 | 🔴 **HARD** | +40 XP | Sulit & panjang |
  | 5 | 🟣 **MYTHIC** | +60 XP | Ujian / Boss level |

- Tambahkan **mata pelajaran** dan **deadline** pada setiap tugas
- **Centang tugas** → XP otomatis bertambah
- Tab terpisah untuk tugas **Active** dan **Completed**
- Batalkan centang → XP otomatis berkurang

---

### 🏆 Sistem Rank (FF / ML Style)
Sistem rank berlevel seperti game battle royale — **8 tier, total 20 sub-rank**:

```
⬡  IRON      I → II → III     (0 – 99 XP)
🔶 BRONZE    I → II → III     (100 – 279 XP)
⬢  SILVER    I → II → III     (280 – 499 XP)
🏅 GOLD      I → II → III     (500 – 849 XP)
💠 PLATINUM  I → II → III     (850 – 1349 XP)
💎 DIAMOND   I → II → III     (1350 – 1999 XP)
👑 MASTER                      (2000 – 2499 XP)
🔱 MYTHIC                      (2500+ XP)
```

- XP bar di header bergerak realtime
- Halaman **Rank** menampilkan tier list lengkap dengan badge warna per tier
- Label `CURRENT` menandai tier kamu saat ini
- Statistik: total misi selesai & jumlah Mythic clear

---

### 🎒 Gear / Inventori
- Tambah barang ke inventori dengan **foto kamera langsung** (kamera belakang HP)
- Preview kamera, capture, retake jika tidak puas
- Setiap item tersimpan dengan **foto + nama**
- Tampilan grid 2 kolom
- Hapus item kapan saja

---

### 👤 Profil Operator
- **Setup profil** saat pertama buka (nama, sekolah, kelas, foto)
- Foto profil dari kamera / galeri, muncul di header & halaman profil
- Statistik profil: Total XP, jumlah misi, jumlah gear
- **Edit profil** kapan saja (nama, sekolah, kelas)
- Rank chip realtime di profil
- Tombol **Reset All Data** di danger zone

---

### 💾 Penyimpanan Data Permanen
- Semua data disimpan otomatis via **localStorage**
- Data **tidak hilang** saat browser ditutup atau HP di-restart
- Auto-save setiap ada perubahan (tambah/hapus/centang)
- Status storage ditampilkan di halaman Profil
- Reset data dengan konfirmasi di menu Profil

---

## 🎨 Desain & Teknologi

| Aspek | Detail |
|-------|--------|
| **Tema** | Cyberpunk / Military Tech |
| **Palet Warna** | Hitam pekat · Biru navy · Cyan gelap |
| **Font Utama** | Rajdhani (tegas, lancip) |
| **Font Kode** | Orbitron (tech/military) |
| **Efek** | Scanline overlay, glow subtle, clip-path angular |
| **Platform** | Mobile-first, responsive |
| **Ukuran File** | < 60 KB (single HTML, no dependencies) |
| **Offline** | ✅ 100% berjalan tanpa internet setelah dibuka |

---

## 🚀 Cara Pakai

```bash
# 1. Download file dari link di atas
# 2. Extract file .7z
# 3. Buka school-quest.html di browser HP/PC

# Untuk HP (rekomendasi):
# Buka di Chrome / Safari mobile
# Tap menu browser → "Add to Home Screen"
# App bisa dipakai seperti aplikasi native
```

### Requirements
- Browser modern (Chrome, Safari, Firefox, Edge)
- Tidak butuh instalasi apapun
- Tidak butuh internet setelah pertama dibuka
- Izin kamera diperlukan untuk fitur inventori

---

## 📁 Struktur File

```
NPC_QUEST_V2_v1.0.0/
└── school-quest.html     ← File utama (all-in-one)
```

> Semua CSS, JavaScript, dan HTML berada dalam **satu file** — tidak ada dependensi eksternal selain Google Fonts.

---

## 🗺️ Roadmap

- [ ] Export / Import data (JSON backup)
- [ ] Notifikasi reminder tugas
- [ ] Mode gelap lebih dalam (AMOLED)
- [ ] Statistik mingguan / bulanan
- [ ] Tema warna custom
- [ ] Multiplayer leaderboard

---

## 📜 Lisensi

```
MIT License — Free to use, modify, and distribute.
Dibuat dengan ☕ dan semangat belajar.
```

---

<div align="center">

**NEXUS Academic OS** — *Your School. Your Mission. Your Rank.*

```
// END OF README //
```

</div>
