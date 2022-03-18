# Project-create-database-tables-python
This project about learning creating database and tables in python (In Indonesia)

Creating Database: Terdapat variasi untuk membuat database berdasarkan tipe basis datanya. Seperti PostgreSQL dan MySQL yang memiliki tools khusus untuk menginisialisasi ke database. Misalnya saja untuk MySQL kita perlu meng-import package pymysql.
Namun dengan SQLite, hanya dengan perintah create_engine saja kita sudah berhasil untuk membuat database dan file tersebut secara otomatis akan tersimpan di dalam folder projek Python yang kita gunakan.
Creating Table :
Misalkan disini ingin membuat table employees yang memiliki 4 kolom yaitu: id, name, salary dan active. Pertama kita import terlebih dahulu tipe data untuk masing - masing kolom.
Selanjutnya dengan method create_all(), maka perintah query tersebut akan di generate menjadi bentuk tabel ke database employees. Method table_names() digunakan untuk melihat nama tabel apa saja yang ada di database employees.
Creating Tables - Additional Column Options:
Sekarang mari kita memberikan nilai unik dan nullable untuk kolom name. Nilai nullable berfungsi untuk memberikan nilai null jika tidak ada data yang kita input. Lalu juga akan memberikan nilai default untuk kolom salary dan active. Nilai default berfungsi untuk memberikan nilai yang sudah ditentukan hasilnya jika tidak ada data yang kita input.
