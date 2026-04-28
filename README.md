**API Automation Testing - Katalon Studio**
Projek ini dibuat untuk memenuhi tugas pengujian API otomatis menggunakan Katalon Studio. Di sini saya melakukan testing pada beberapa endpoint REST API untuk memastikan fungsinya berjalan dengan benar.


Saya fokus pada verifikasi respon API, seperti:
Status Code: Memastikan respon yang balik sesuai (misal: 200, 201, atau 204).
Response Body: Cek apakah data yang muncul sudah benar dan tidak ada yang kurang.
Method: Mengetes fungsi GET, POST, PUT, dan DELETE.

**Detail Skenario**
Berikut daftar tes yang saya lakukan:
**GET** List Users: Cek apakah daftar user bisa dipanggil.
**POST** Create User: Simulasi tambah user baru dan pastikan datanya tersimpan.
**PUT** Update User: Tes edit data user yang sudah ada.
**DELETE** User: Memastikan fungsi hapus data berjalan lancar.

**Cara Pakai**
Kalau mau coba running di lokal:
Clone repo ini: git clone https://github.com/maharanindya/Katalon-TaskAPI-MaharaniAnindyaSalsabila.git
Buka Katalon Studio, lalu Open Project.
Pilih folder hasil clone tadi.
Masuk ke folder Test Suites, pilih salah satu, dan klik Run.
