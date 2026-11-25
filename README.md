# 🎵 Libra Music — Mobile Music Streaming App

Aplikasi streaming musik modern berbasis **Flutter** dengan pemutaran di latar belakang (*background playback*), lirik lagu sinkron (*karaoke style*), integrasi YouTube Audio Engine, dan antarmuka *Cyber-Glassmorphism* yang elegan.

---

## ✨ Fitur Utama

- 🎧 **Pemutaran Latar Belakang & Kunci Layar**: Musik tetap berputar mulus tanpa jeda saat layar HP dimatikan atau saat membuka aplikasi lain.
- 🎛️ **Floating Mini Player**: Bilah musik melayang di bagian bawah dengan kontrol lengkap (play/pause, favorit, next, dan garis progres neon).
- 📜 **Lirik Lagu Realtime (Synchronized Lyrics)**: Tampilan lirik lagu sinkron per detik otomatis dari LRCLIB.
- 🔍 **Pencarian YouTube & Database Lokal**: Fitur pencarian cerdas dengan saran otomatis Google Suggest dan jutaan katalog lagu YouTube.
- 💖 **Koleksi & Riwayat Putar**: Simpan lagu favorit kamu dan lihat kembali riwayat lagu yang telah didengarkan.
- 🎨 **Desain Modern Libra**: Tampilan gelap futuristik dengan aksen *Emerald Glow* (`#10B981`) dan *Midnight Slate*.

---

## 🚀 Memulai (Quick Start)

Untuk mulai menjalankan aplikasi di komputer lokal kamu:

```bash
# 1. Clone repositori ini
git clone https://github.com/Libra2694/Libra-Music.git
cd Libra-Music

# 2. Ambil dependensi
flutter pub get

# 3. Jalankan aplikasi
flutter run
```

---

## 🤝 Panduan Kolaborasi Tim

Tertarik untuk berkontribusi atau coding bareng? Silakan baca panduan lengkap alur kerja Git, struktur folder, dan standar kode di file:
👉 **[KOLABORASI.md](KOLABORASI.md)**

---

## 🛠️ Teknologi yang Digunakan

- **Framework**: [Flutter](https://flutter.dev) (Dart 3)
- **Audio Engine**: `youtube_player_flutter`, `just_audio`, `just_audio_background`
- **Webview Engine**: `flutter_inappwebview` (Custom background lifecycle)
- **Lyrics API**: [LRCLIB](https://lrclib.net)
- **Cache & Image**: `cached_network_image`
