# LAN_settings.sh

<div align="center">

**Script konfigurasi jaringan interaktif untuk modul Quectel**

[![GitHub stars](https://img.shields.io/github/stars/zainalicious/LAN_settings.sh)](https://github.com/zainalicious/LAN_settings.sh/stargazers)
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

</div>

## 📋 Tentang Script

Script ini menyediakan antarmuka terminal **(CLI)** yang mudah digunakan untuk memodifikasi file konfigurasi `/etc/data/mobileap_cfg.xml` pada perangkat Quectel. Dengan menu berwarna dan interaktif, kamu bisa mengubah berbagai pengaturan jaringan dengan aman.

**🎨 Fitur Unggulan:**
-   **Tampilan interaktif** dengan kode warna yang berubah-ubah (random color)
-   **Validasi input** untuk mencegah kesalahan konfigurasi
-   **Auto-install dependensi** (`xmlstarlet`) jika belum tersedia
-   19 opsi konfigurasi lengkap untuk LAN, DHCP, NAT, dan WAN

> ⚠️ **Peringatan Penting!**  
> Perubahan pengaturan dapat memutus akses jaringan. Pastikan kamu memiliki akses **ADB** sebagai cadangan sebelum menggunakan script ini. Gunakan dengan penuh tanggung jawab!

## 🚀 Cara Instalasi di Modul Quectel

Ikuti langkah-langkah berikut melalui **ADB shell** atau **SSH**:

1. Akses perangkat Quectel
```bash
adb shell
# atau
ssh user@ip_modem_quectel
```

2. Masuk ke direktori tujuan

```bash
cd /usrdata/simpleadmin/console/menu/
```

3. Download script

```bash
wget https://raw.githubusercontent.com/zainalicious/LAN_settings.sh/main/LAN_settings.sh
```

4. Beri izin eksekusi

```bash
chmod +x LAN_settings.sh
```
