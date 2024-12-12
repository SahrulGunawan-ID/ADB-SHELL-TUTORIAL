# ADB-SHELL-TUTORIAL

> English >
Here is a collection of some frequently used `pm` commands on Android to manage packages and applications via ADB: 

> Indonesia >
Berikut adalah kumpulan beberapa perintah `pm` yang sering digunakan di Android untuk mengelola paket dan aplikasi melalui ADB:


1. **Menampilkan semua paket yang terpasang:**
    ```sh
    pm list packages
    ```

2. **Menampilkan semua paket sistem:**
    ```sh
    pm list packages -s
    ```

3. **Menampilkan semua paket yang diinstal oleh pengguna:**
    ```sh
    pm list packages -3
    ```

4. **Menampilkan paket dengan nama tertentu:**
    ```sh
    pm list packages <nama_paket>
    ```

5. **Menginstal aplikasi dari file APK:**
    ```sh
    pm install <path-ke-apk>
    ```

6. **Menghapus aplikasi:**
    ```sh
    pm uninstall <nama_paket>
    ```

7. **Menghapus aplikasi untuk pengguna tertentu:**
    ```sh
    pm uninstall --user <id_pengguna> <nama_paket>
    ```

8. **Mengaktifkan paket:**
    ```sh
    pm enable <nama_paket>
    ```

9. **Menonaktifkan paket:**
    ```sh
    pm disable <nama_paket>
    ```

10. **Menghentikan aplikasi:**
    ```sh
    pm clear <nama_paket>
    ```

11. **Menampilkan info paket:**
    ```sh
    pm dump <nama_paket>
    ```

12. **Menambahkan paket ke daftar paket yang tidak aktif:**
    ```sh
    pm suspend <nama_paket>
    ```

13. **Menghapus paket dari daftar paket yang tidak aktif:**
    ```sh
    pm unsuspend <nama_paket>
    ```

14. **Menampilkan semua aktivitas dalam paket:**
    ```sh
    pm list packages -a <nama_paket>
    ```

15. **Menampilkan semua layanan dalam paket:**
    ```sh
    pm list packages -s <nama_paket>
    ```

16. **Menampilkan semua penerima siaran dalam paket:**
    ```sh
    pm list packages -r <nama_paket>
    ```

17. **Menampilkan semua penyedia konten dalam paket:**
    ```sh
    pm list packages -p <nama_paket>
    ```

18. **Menambahkan aplikasi ke profil pengguna:**
    ```sh
    pm grant <nama_paket> <nama_permission>
    ```
