SCRATCH HELP — PANDUAN DEPLOY VERCEL

Paket berisi versi Scratch Help tanpa antrean bantuan.

1. Ekstrak ZIP ini di komputer.
2. Buat repository GitHub bernama scratch-help. Centang Add a README file.
3. Buka repository > Add file > Upload files.
4. Seret seluruh ISI folder hasil ekstrak (bukan file ZIP) ke halaman upload.
   Pastikan index.html, app.js, vercel.json dan folder assets berada di tingkat teratas repository.
5. Klik Commit changes.
6. Login Vercel dengan akun GitHub. Klik Add New > Project.
7. Import repository scratch-help. Jika belum muncul, izinkan aplikasi Vercel mengakses repository itu.
8. Gunakan konfigurasi:
   Project Name: scratch-help (atau nama lain jika sudah digunakan)
   Framework Preset: Other
   Root Directory: ./ (tingkat teratas repository)
   Build Command: kosong (Override aktif bila diperlukan)
   Output Directory: .
   Install Command: biarkan default
   Environment Variables: tidak diperlukan
   File vercel.json telah menyertakan konfigurasi framework, build, dan output.
9. Klik Deploy. Tunggu hingga berhasil, lalu buka domain Production yang diberikan Vercel.
10. Uji dari mode samaran: materi, empat tahap praktik, pencarian error, dan cek diskon.

PERUBAHAN BERIKUTNYA
Edit atau unggah file pengganti ke repository yang sama, lalu commit pada branch Production (umumnya main).
Vercel akan membuat deployment pembaruan otomatis jika integrasi Git terhubung.

DOMAIN
Nama scratch-help.vercel.app adalah contoh; ketersediaan ditentukan Vercel.
Domain milik sendiri dapat ditambahkan melalui Settings > Domains setelah deploy berhasil.

CATATAN
Web ini berupa HTML/CSS/JavaScript statis; tidak membutuhkan database atau proses build.
Deploy ke Vercel membuat salinan hosting baru. Tautan Sites lama tetap terpisah.
