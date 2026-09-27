# Catatan Keuangan — Build APK online

Proyek Android sederhana untuk Catatan Keuangan. Workflow GitHub Actions disertakan agar APK debug dapat dibuat di server GitHub.

## Membuat APK
1. Buat repository GitHub baru dan unggah seluruh isi folder proyek ini (termasuk folder tersembunyi `.github`).
2. Pastikan nama branch utama adalah `main`.
3. Buka tab **Actions** pada repository dan pilih workflow **Build APK**.
4. Tekan **Run workflow** jika workflow belum berjalan otomatis.
5. Setelah proses selesai, buka hasil run yang berhasil dan unduh artifact **CatatanKeuangan-debug-apk**.
6. Ekstrak ZIP artifact untuk memperoleh `app-debug.apk`, lalu pindahkan ke HP dan pasang.

APK ini adalah APK debug untuk pengujian, bukan rilis Play Store. Build belum dijamin berhasil sampai workflow selesai; jika gagal, lihat log pada langkah yang berwarna merah.
