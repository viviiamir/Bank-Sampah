<<<<<<< HEAD
# Bank-Sampah
Membuat Aplikasi Bank Sampah

# Tutorial Build with Android Studio
https://youtu.be/3ogycbzUy8Y

# Tutorial Build with Step by Step
https://rivaldi48.blogspot.com/2021/12/tutorial-membuat-aplikasi-bank-sampah-dengan-android-studio.html

<img src="https://blogger.googleusercontent.com/img/a/AVvXsEiZD0EB5ueAk-m827elL2fsG2-9wemIa-JAVIbZIwGHGFnKV7w9nDirRsMTCnBDD1IejcnSkc0S1o-0H5u1113oYYMywG7UYkmr1Y6qLQqLj_8Q0xVgrhnELNo_-3dADWcLCEB_P2izJ9OXOu5ySMdaJZb9UpITN1P8tJ67766alZsjmM71S13OGm7Qew=s1280" data-canonical-src="https://blogger.googleusercontent.com/img/a/AVvXsEiZD0EB5ueAk-m827elL2fsG2-9wemIa-JAVIbZIwGHGFnKV7w9nDirRsMTCnBDD1IejcnSkc0S1o-0H5u1113oYYMywG7UYkmr1Y6qLQqLj_8Q0xVgrhnELNo_-3dADWcLCEB_P2izJ9OXOu5ySMdaJZb9UpITN1P8tJ67766alZsjmM71S13OGm7Qew=s1280" style="max-width:100%;">

****If you use the Source Code, please make sure to credit and backlink to [Azhar Rivaldi](https://rivaldi48.blogspot.com/)***

## 👇 Click For Support Me :
<a href="https://sociabuzz.com/azharrvldi_/donate"> 
<img src="https://github.com/AzharRivaldi/AzharRivaldi/blob/master/Support%20Here.png" width="200" height="200"></a>

## 📄 License

```
Copyright (C) Azhar Rivaldi

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

```
=======
 **Bank Sampah**

Aplikasi Android "Bank Sampah" adalah solusi untuk mengelola proses penjemputan sampah dari pengguna. Aplikasi ini memungkinkan pengguna untuk meminta penjemputan sampah, melihat riwayat transaksi, dan memeriksa saldo mereka.

-----

### 🛠️ **Prasyarat**

Pastikan Anda telah menginstal perangkat lunak berikut di komputer Anda sebelum melanjutkan:

  * **Git:** Digunakan untuk mengkloning (mengunduh) repositori dari GitHub.
  * **Android Studio:** Lingkungan pengembangan terpadu (IDE) resmi untuk membuat aplikasi Android.
  * **Java Development Kit (JDK):** Diperlukan oleh Gradle untuk membangun proyek.

-----

### ⚙️ **Teknologi & Struktur Proyek**

#### **Teknologi yang Digunakan**

| Komponen | Deskripsi |
| :--- | :--- |
| **Bahasa** | Kotlin |
| **SDK** | Menggunakan Android Gradle Plugin `7.0.3`  |
| **DB** | Database lokal untuk menyimpan data riwayat dan transaksi. |
| **UI** | Material Design + XML layout  |
| **Logika** | Manajemen data untuk penjemputan sampah, riwayat, dan saldo pengguna. |

#### **Struktur File Penting**

  * `MainActivity.kt` → Mengelola tampilan menu utama aplikasi.
  * `InputDataActivity.kt` → Berisi halaman untuk mengisi formulir data penjemputan sampah. 
  * `RiwayatActivity.kt` → Menampilkan total saldo dan daftar riwayat transaksi pengguna. 
  * `JenisSampahActivity.kt` → Menyajikan informasi mengenai berbagai jenis sampah. 
  * `/layout/*.xml` → Kumpulan file desain antarmuka (UI) untuk setiap halaman aplikasi. 
  * `database` → Direktori yang berisi logika dan model untuk pengelolaan database aplikasi.

-----

### 🚀 **Panduan Instalasi (Developer)**

Berikut adalah langkah-langkah untuk menginstal dan menjalankan aplikasi "Bank Sampah":

**1. Kloning Repositori**
Buka terminal atau command prompt Anda, lalu jalankan perintah berikut untuk mengunduh kode sumber:

```bash
git clone https://github.com/viviiamir/Bank-Sampah.git
```

**2. Buka Proyek di Android Studio**

  * Luncurkan Android Studio.
  * Dari jendela selamat datang, pilih **File → Open**.
  * Arahkan ke direktori tempat Anda mengkloning repositori `Bank-Sampah`, pilih folder tersebut, dan klik **OK**.

**3. Sinkronisasi Gradle**
Setelah proyek terbuka, Android Studio akan secara otomatis menyinkronkan proyek dengan file Gradle. Proses ini akan mengunduh semua dependensi yang diperlukan yang tercantum dalam file `build.gradle` dari repositori yang ditentukan di `settings.gradle`.  Pastikan Anda memiliki koneksi internet yang stabil.

**4. Konfigurasi SDK (Jika Diperlukan)**
Biasanya, Android Studio akan menangani lokasi Android SDK secara otomatis. Namun, jika terjadi kesalahan, pastikan file `local.properties` menunjuk ke lokasi SDK yang benar di komputer Anda. Contoh isi file `local.properties` adalah sebagai berikut:

```properties
sdk.dir=C\:\\Users\\user\\AppData\\Local\\Android\\Sdk
```

*Gantilah path di atas dengan lokasi direktori SDK Android Anda.*

**5. Jalankan Aplikasi**

  * **Pilih Perangkat:** Di bilah alat atas Android Studio, pilih perangkat target. Anda dapat menggunakan emulator Android atau menghubungkan perangkat fisik melalui USB (pastikan mode *USB debugging* telah diaktifkan).
  * **Jalankan:** Klik ikon **▶️ (Run 'app')** untuk memulai proses build dan instalasi.

Aplikasi akan diinstal dan dijalankan secara otomatis pada perangkat yang Anda pilih.

-----

### 👥 **Kontributor**

  * Fitrah Qoyyumi Amir (221001036)
  * Lina Anggraeni (221001042)
  * Septia Salbuanda (221001061)

-----

### 📝 **Catatan**

  * Aplikasi ini menyimpan semua data secara lokal di perangkat.
  * Untuk panduan dalam format video atau tutorial langkah-demi-langkah, Anda dapat merujuk ke tautan yang tersedia di dalam file `README.md`.
>>>>>>> 12e6886644174ba1fcbeacbad9a9fc5c0108e49b
