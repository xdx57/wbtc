# wbtc

[![Source](https://img.shields.io/badge/Source-GitHub-black?logo=github)](https://github.com/xdx57/wbtc)
[![Mirror](https://img.shields.io/badge/Mirror-GitLab-orange?logo=gitlab)](https://gitlab.com/xdx57/wbtc)
[![Auto Re-clone](https://img.shields.io/badge/Reclone-Automatis-blue?logo=python)](#)

---

## Cara Install Tools ini Di Handphone Android

### Tahapan:

1. set up termux
   - install git → untuk clone repository
   - install python → bahasa pemrograman
2. clone repository github
3. jalankan program

---

### Yang dibutuhkan:

- Download aplikasi Termux (di Playstore)
- Download aplikasi Warp 1.1.1.1 / VPN (di Playstore)
- Repository utama: [https://github.com/xdx57/wbtc](https://github.com/xdx57/wbtc)
- Mirror GitLab (jika GitHub bermasalah): [https://gitlab.com/xdx57/wbtc](https://gitlab.com/xdx57/wbtc)

---

### Alias:

- `(k)` = ketik
- `(e)` = enter

---

## Langkah-Langkah:

### 1. Set up Termux

> ✅ Install modul yang diperlukan

1. Aktifkan VPN (Warp 1.1.1.1)
2. Buka Termux
3. `(k)` `apt update && apt upgrade -y` `(e)`
4. `(k)` `pkg install python git -y` `(e)`

> ✅ Cek apakah Python dan Git sudah terinstall

1. `(k)` `python -V` `(e)` → cek versi Python
2. `(k)` `git -v` `(e)` → cek versi Git

> ❌ Setelah itu, matikan koneksi VPN (Warp)

---

### 2. Clone Repository GitHub (download tools)

> ✅ Clone repo:

```
(k) git clone https://github.com/xdx57/wbtc (e)
```

> 📝 Optional: cek hasil clone

```
(k) ls (e)
```

> ⚠️ Kalau gagal clone karena folder `wbtc` udah ada:

```
(k) rm -rf wbtc (e)
```

---

### 3. Jalankan Program

> ✅ Masuk ke folder:

```
(k) cd wbtc (e)
```

> ✅ Cek isi folder (opsional)

```
(k) ls (e)
```

> ✅ Jalankan tools:

```
(k) python p.py (e)
```

---

## ⚠️ Tentang Password

Saat pertama kali menjalankan tools ini, kamu akan diminta untuk memasukkan **password**.

- Simpan baik-baik password tersebut.
- Jika kamu lupa password, **tools tidak bisa diakses kembali**.
- Tidak ada sistem reset / lupa password. Jaga baik-baik!
- Rekomendasi: catat di tempat aman atau gunakan password manager.

> 🔐 Keamanan tools ini memang sengaja dirancang untuk menjaga privasi data pengguna.

---

## ♻️ Re-Clone Ulang Jika Versi Python Berubah

Jika kamu upgrade atau downgrade versi Python di Termux, tools ini mungkin tidak berjalan normal. Tapi tenang, proses re-clone ini **dilakukan otomatis oleh sistem** jika terdeteksi versi Python berubah.

Setelah re-clone otomatis, kamu akan **diminta untuk input ulang password**.

> 💡 Ini penting karena beberapa bagian tools bisa tergantung versi Python tertentu.

---

## Perintah Dasar di Termux

| Perintah | Keterangan                     |
| -------- | ------------------------------ |
| `ls`     | Lihat isi folder               |
| `clear`  | Bersihkan layar                |
| `cd ..`  | Masuk ke folder induk          |
| `pwd`    | Tampilkan direktori saat ini   |
| `rm -rf` | Hapus folder/file secara paksa |

| `Ctrl + D`      | Tutup aplikasi Termux |
| --------------- | ------------ |

> ⚠️ **Catatan:** Gunakan `rm -rf` dengan hati-hati. Data yang terhapus tidak bisa dikembalikan!

---

### 📦 Mirror Project (GitLab)

Repo ini juga tersedia di GitLab:\
🔗 [https://gitlab.com/xdx57/wbtc](https://gitlab.com/xdx57/wbtc)

