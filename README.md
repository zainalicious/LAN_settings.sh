# LAN_settings.sh

Script konfigurasi jaringan untuk modul Quectel. Memudahkan pengaturan LAN, DHCP, NAT, dan opsi jaringan lainnya melalui menu interaktif berbasis terminal.

## 📋 Deskripsi

Script ini menyediakan antarmuka teks sederhana untuk memodifikasi file konfigurasi `/etc/data/mobileap_cfg.xml` pada perangkat Quectel. Dengan script ini, Anda dapat mengubah berbagai pengaturan jaringan seperti alamat IP Gateway, rentang DHCP, subnet mask, serta mengaktifkan/menonaktifkan fitur seperti NAT, UPnP, roaming, dan lainnya.

**Peringatan:** Perubahan pengaturan dapat memutus akses jaringan Anda. Pastikan Anda memiliki akses ADB sebagai cadangan.

## 🚀 Instalasi

Ikuti langkah-langkah berikut untuk menginstal script pada modul Quectel melalui **ADB shell** atau **SSH**:

1.  **Akses shell perangkat Quectel** (contoh dengan ADB):
    ```bash
    adb shell
    ```

2.  **Pindah ke direktori tujuan**:
    ```bash
    cd /usrdata/simpleadmin/console/menu/
    ```

3.  **Unduh script menggunakan `wget`**:
    ```bash
    wget https://raw.githubusercontent.com/zainalicious/LAN_settings.sh/main/LAN_settings.sh
    ```

4.  **Beri izin eksekusi**:
    ```bash
    chmod +x LAN_settings.sh
    ```

## 🛠️ Penggunaan

Setelah terinstal, jalankan script dengan perintah:

```bash
./LAN_settings.sh
