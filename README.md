TokoApp – Aplikasi Manajemen Toko

TokoApp merupakan aplikasi desktop berbasis Java yang dikembangkan untuk membantu pengelolaan operasional toko. Aplikasi ini menggunakan JavaFX sebagai antarmuka pengguna dan MySQL sebagai database untuk menyimpan serta mengelola data toko.

## Teknologi yang Digunakan
- Java 17
- JavaFX 21
- MySQL
- MySQL Connector/J 8.0.33
- Apache Maven

## Persyaratan Sistem
Sebelum menjalankan aplikasi, pastikan sudah menginstal:
- JDK 17 atau versi yang kompatibel
- Apache Maven
- MySQL Server atau XAMPP

## Cara Menjalankan Aplikasi

1. Clone repository:
   git clone https://github.com/USERNAME/TokoApp.git

2. Masuk ke direktori project:
   cd TokoApp

3. Jalankan aplikasi menggunakan Maven:
   mvn clean javafx:run

## Screenshot Aplikasi
![Dashboard](screenshots/dashboard.png)

![Produk](screenshots/Daftar.png)

### Halaman Transaksi
![Transaksi](screenshots/Detail.png)


## Struktur Project
- `src/main/java` – Menyimpan source code Java.
- `src/main/resources` – Menyimpan resource aplikasi seperti file FXML dan CSS (jika digunakan).
- `pom.xml` – Konfigurasi dependency dan Maven.
- `nbactions.xml` – Konfigurasi action untuk menjalankan project melalui NetBeans.

## Pengembang
Project ini dikembangkan sebagai bagian dari pembelajaran dan penerapan pemrograman berorientasi objek serta pengelolaan database.
