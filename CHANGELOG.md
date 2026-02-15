[1.0.0] - 2026-02-15
Added
-Halaman Daftar Ruangan (index.html): UI untuk menampilkan kartu ruangan secara dinamis dari API.
-Halaman Form Peminjaman (peminjaman.html): Formulir pengajuan sewa ruangan dengan validasi waktu.
-Tabel Riwayat Peminjaman: Integrasi data untuk memantau status peminjaman (Pending, Approved, Rejected).
-Admin Status Control: Tombol aksi khusus admin (Approve/Reject) dengan integrasi PATCH API.
-Sistem Styling Terpusat: Menggunakan style.css untuk desain modern, responsif, dan fungsionalitas status badge.

Fixed
-Sinkronisasi Data Tujuan: Memperbaiki pemetaan properti Purpose dari backend ke frontend sehingga data tampil dengan benar di tabel.
-Format Waktu: Penyesuaian tampilan waktu menggunakan toLocaleString() agar mudah dibaca pengguna.

Technical Notes
-Backend: .NET 10 Web API dengan PostgreSQL.
-Frontend: HTML5, Pure CSS, dan Vanilla JavaScript (Fetch API).