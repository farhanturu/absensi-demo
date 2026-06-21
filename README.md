# Absensi Karyawan

> Sistem Absensi Karyawan dengan Geofencing, Real-time Map, dan Dashboard Lengkap

![Status](https://img.shields.io/badge/v2.0-new-brightgreen?style=flat-square)
![Geofencing](https://img.shields.io/badge/geofencing-active-blue?style=flat-square)
![Map](https://img.shields.io/badge/map-Leaflet-green?style=flat-square)
![Mobile](https://img.shields.io/badge/mobile-responsive-purple?style=flat-square)

## 🔴 Live Demo

### **[→ https://farhanturu.github.io/absensi-demo/](https://farhanturu.github.io/absensi-demo/)**

| Role | Email | Password |
|------|-------|----------|
| Admin | admin@company.com | admin123 |
| User | budi@company.com | password123 |

## Fitur v2.0

- **Geofencing** — Absen hanya dalam radius yang ditentukan admin
- **Real-time Map** — Peta lokasi kantor & lokasi check-in karyawan
- **Admin Settings** — Atur lokasi kantor, radius, nama lokasi
- **Click to Set** — Klik peta untuk set lokasi kantor
- **GPS Validation** — Validasi lokasi sebelum check-in
- **Dashboard** — Statistik lengkap (admin & user)
- **Riwayat** — Kalender mingguan dengan warna status
- **Cuti** — Pengajuan & persetujuan cuti
- **Laporan** — Rekap absensi per tanggal (admin)
- **Export CSV** — Download data absensi
- **Karyawan** — CRUD karyawan (admin)
- **Dark Theme** — UI modern dengan gradient
- **Mobile First** — Responsive di semua device
- **Logo Custom** — SVG logo dengan gradient

## Cara Pakai

1. Buka demo link
2. Login (admin atau user)
3. **Admin:** Buka Pengaturan → atur lokasi kantor & radius
4. **User:** Buka Absen → aktifkan GPS → Check In
5. GPS harus dalam radius kantor untuk bisa absen

## Pengaturan Geofencing (Admin)

1. Login sebagai admin
2. Buka menu **Pengaturan**
3. **Klik peta** untuk set lokasi kantor
4. Atur **radius** (50-5000 meter)
5. Klik **Simpan Pengaturan**
6. Karyawan hanya bisa absen dalam radius tersebut

## Tech Stack

- HTML5, CSS3, Vanilla JavaScript
- Leaflet.js (peta interaktif)
- Geolocation API (GPS)
- localStorage (database)
- CartoDB Dark Tiles (basemap)

## Struktur

```
absensi-demo/
├── index.html    # Full app (single file)
└── README.md     # Dokumentasi
```

## License

MIT

---

*Built by PaongLabs AI Agent*
