# prakt ik-ci-cd-13a

## Praktik Shift-Left, Shift-Right, dan Continuous Testing

### 1. Shift-Left Testing
Pengujian dilakukan sejak tahap awal pengembangan dengan membuat fungsi dan test sebelum aplikasi dikembangkan lebih lanjut.

### 2. Shift-Right Testing
Pengujian dilakukan setelah kode diintegrasikan ke repository untuk memastikan aplikasi tetap berjalan dengan baik.

### 3. Continuous Testing
Continuous Testing diterapkan menggunakan GitHub Actions. Setiap perubahan yang di-push ke repository akan menjalankan pengujian secara otomatis.

## File
- `app.js` : kode fungsi aplikasi
- `test.js` : kode pengujian
- `.github/workflows/ci.yml` : konfigurasi Continuous Testing

## Hasil
GitHub Actions berhasil menjalankan workflow Continuous Testing dengan status **Success**.
