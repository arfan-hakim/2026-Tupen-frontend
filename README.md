# 2026-Tupen-frontend

🚀 Cara Menjalankan Frontend
Untuk menjalankan aplikasi ini, disarankan menggunakan Live Server agar fitur fetch API berjalan lancar tanpa kendala protokol keamanan browser.

- Menggunakan VS Code (Rekomendasi):
Pastikan ekstensi Live Server oleh Ritwick Dey sudah terinstal di VS Code kamu.
Klik kanan pada file index.html atau peminjaman.html.
Pilih "Open with Live Server".
Aplikasi akan terbuka secara otomatis di browser pada alamat http://127.0.0.1:5500.

-Persyaratan Backend:
Pastikan Backend .NET sudah menyala (dotnet run) dan mendengarkan di http://localhost:5145 agar data ruangan dan riwayat bisa muncul.

📂 Struktur Folder Frontend
Berikut adalah susunan file utama dalam proyek frontend ini:
-index.html: Halaman utama yang menampilkan daftar ruangan yang tersedia dari database.
-peminjaman.html: Halaman formulir untuk mengajukan peminjaman ruangan serta melihat riwayat status peminjaman.
-style.css: File desain utama yang mengatur tata letak (layout), warna, dan animasi tombol (termasuk status badges).
-assets/ (Opsional): Folder untuk menyimpan gambar ruangan atau logo "Tupen.".

🛠️ Integrasi API
Frontend terhubung dengan backend menggunakan JavaScript Fetch API pada endpoint:
-GET /api/Rooms (Daftar ruangan)
-GET /api/Bookings (Riwayat peminjaman)
-POST /api/Bookings (Pengajuan baru)
-PATCH /api/Bookings/{id}/status (Aksi admin Approve/Reject)

