# wbtc

[![GitHub Repo](https://img.shields.io/badge/Source-GitHub-black?logo=github)](https://github.com/xdx57/wbtc)
[![Mirror](https://img.shields.io/badge/Mirror-GitLab-orange?logo=gitlab)](https://gitlab.com/xdx57/wbtc)

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
- download aplikasi termux (di Playstore)
- download aplikasi warp 1.1.1.1 / VPN (di Playstore)
- repository: https://github.com/xdx57/wbtc

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

## Perintah Dasar di Termux

| Perintah      | Keterangan                                      |
|---------------|-------------------------------------------------|
| `ls`          | Lihat isi folder                                |
| `clear`       | Bersihkan layar                                 |
| `cd ..`       | Masuk ke folder induk                           |
| `pwd`         | Tampilkan direktori saat ini                    |
| `rm -rf`      | Hapus folder/file secara paksa **(hati-hati)**  |
| `Ctrl + D`    | Tutup Termux                                    |

> ⚠️ **Catatan:** Gunakan `rm -rf` dengan hati-hati. Data yang terhapus tidak bisa dikembalikan!

---

### 📦 Mirror Project (GitLab)

Repo ini juga tersedia di GitLab:  
🔗 https://gitlab.com/xdx57/wbtc

