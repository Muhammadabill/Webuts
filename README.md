## Webuts
## Muhamad Nabil Satriya Suntara
## 312410365
## Agung Nugroho, S.Kom., M.Kom
## Pemrograman Web
Struktur folder: (sesuai soal)

index.html (login) dashboard.html (role-based: Admin/User) stok.html (admin only) checkout.html (user only) tracking.html (user only) css/style.css js/data.js <-- file data sesuai yang Anda berikan (tdk diubah) js/script.js assets/logo.png img/... Akun contoh (ada di data.js):

User: rina@gmail.com / rina123

User: agus@gmail.com / agus123

Admin: mufidazulfi@gmail.com / mufidazulfi123

Petunjuk singkat:

Buka index.html, login dengan salah satu akun di atas.

Setelah login, akan diarahkan ke dashboard. Navigation menyesuaikan role:
<img width="1880" height="862" alt="Screenshot 2025-11-07 164809" src="https://github.com/user-attachments/assets/42df759c-92ff-42d7-b42f-c6304632f257" />

Admin: lihat menu "Informasi Stok / Katalog" (stok.html) untuk kelola buku.
<img width="1869" height="872" alt="Screenshot 2025-11-07 164650" src="https://github.com/user-attachments/assets/2d3578b9-872b-4329-a89e-d902d49fa7c1" />

User: gunakan "Pemesanan" (checkout.html) dan "Tracking" (tracking.html).
<img width="1874" height="769" alt="Screenshot 2025-11-07 164717" src="https://github.com/user-attachments/assets/ebdc2770-59a6-4da4-8013-5f7ef369bb58" />

<img width="1879" height="432" alt="Screenshot 2025-11-07 164825" src="https://github.com/user-attachments/assets/bd00d1a0-66d9-496e-94c3-a8a38ac2035c" />
Semua aksi bersifat simulasi (client-side). Data tersimpan hanya di memori halaman (sessionStorage).
