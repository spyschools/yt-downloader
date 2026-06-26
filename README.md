# 🎬 YT Downloader

Script Python sederhana untuk mengunduh video dan playlist dari YouTube menggunakan library [`yt-dlp`](https://github.com/yt-dlp/yt-dlp).

---

## ✨ Fitur

- ⬇️ **Download video tunggal** — unduh satu video dengan kualitas terbaik hingga resolusi 1080p
- 📂 **Download playlist** — unduh seluruh video dalam satu playlist secara otomatis
- 🗂️ **Penamaan otomatis** — file disimpan dengan nama judul video; playlist disimpan dalam folder tersendiri

---

## 📦 Requirement

- Python 3.7+
- Library `yt-dlp`

Install dependency:

```bash
$ pip3 install yt-dlp
```

---

## 🚀 Cara Penggunaan

Jalankan script:

```bash
$ git clone https://github.com/spyschools/yt-downloader.git
$ cd yt-downloader
$ chmod +x *
$ python yt-downloader.py
```

Ikuti instruksi di terminal:

1. Masukkan URL video atau playlist YouTube
2. Pilih mode unduhan:
   - `1` → Download Video (satu video)
   - `2` → Download Playlist (seluruh video dalam playlist)

---

## 📁 Struktur Output

| Mode | Lokasi File |
|------|-------------|
| Video | `Judul Video.ext` (di direktori saat ini) |
| Playlist | `Nama Playlist/Judul Video.ext` |

---

## 📝 Contoh

```
=== YT Downloader (yt-dlp) ===
Masukkan URL: https://www.youtube.com/watch?v=xxxxx

Pilih mode:
1. Download Video
2. Download Playlist
Pilih (1/2): 1

⏳ Download video...
✅ Selesai!
```

---

## ⚙️ Konfigurasi Format

Secara default, script mengunduh video dengan format terbaik pada resolusi maksimal **1080p** dan menggabungkannya dengan audio terbaik yang tersedia (`bestvideo[height<=1080]+bestaudio/best`).

---

## 📄 Lisensi

Proyek ini bebas digunakan untuk keperluan pribadi. Pastikan penggunaan sesuai dengan [Ketentuan Layanan YouTube](https://www.youtube.com/t/terms).
