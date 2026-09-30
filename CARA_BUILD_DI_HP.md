# Cara Membuat APK Ojol Santuy dari HP

## Cara paling mudah: GitHub

1. Buat akun/login di GitHub.
2. Buat repository baru, misalnya `ojol-santuy-game`.
3. Upload **seluruh isi ZIP ini**, bukan file ZIP-nya.
4. Pastikan folder `.github/workflows/build-apk.yml` ikut ter-upload.
5. Buka tab **Actions**.
6. Pilih workflow **Build Ojol Santuy APK**.
7. Tekan **Run workflow**.
8. Tunggu sampai proses selesai dengan tanda centang hijau.
9. Buka hasil workflow tersebut.
10. Pada bagian **Artifacts**, download **Ojol-Santuy-APK**.
11. Ekstrak ZIP hasil download.
12. Di dalamnya terdapat `app-debug.apk`.
13. Buka APK tersebut di HP dan izinkan instalasi dari sumber yang diizinkan Android jika diminta.

Workflow ini menggunakan Java 17, Gradle 8.7, dan Android Gradle Plugin 8.6.1.
