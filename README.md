
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
