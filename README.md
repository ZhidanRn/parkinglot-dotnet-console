# Parking System

Sistem parkir sederhana yang dibangun dengan menggunakan .NET 8. Proyek ini menggunakan konsol sebagai antarmuka pengguna dan memungkinkan untuk memarkirkan mobil kecil dan motor dalam lot parkir terbatas.

## Fitur

1. **Check-In Kendaraan**
   - Kendaraan yang dapat masuk hanya **Mobil Kecil** dan **Motor**.
   - Kendaraan yang masuk akan tercatat berdasarkan nomor polisi.
   - Perhitungan biaya parkir berdasarkan durasi waktu yang dihabiskan di parkir, dengan biaya per jam.
   - Setiap kendaraan yang masuk akan mendapatkan lot parkir yang tersedia.

2. **Check-Out Kendaraan**
   - Setelah kendaraan keluar (checkout), lot parkir tersebut akan tersedia kembali untuk kendaraan lain.

3. **Laporan**
   - Laporan jumlah lot yang terisi.
   - Laporan jumlah lot yang tersedia.
   - Laporan jumlah kendaraan berdasarkan nomor polisi ganjil/genap.
   - Laporan jumlah kendaraan berdasarkan jenis (mobil atau motor).
   - Laporan jumlah kendaraan berdasarkan warna kendaraan.

## Teknologi

- .NET 8
- C#
- Konsol (Command Line Interface)
- Enum untuk jenis kendaraan (Mobil dan Motor)
  
## Instalasi

1. Pastikan Anda telah menginstal **.NET 8 SDK** di komputer Anda. Anda dapat mengunduhnya di [sini](https://dotnet.microsoft.com/download).
   
2. Clone repository ini ke komputer lokal Anda:

   ```bash
   git clone https://github.com/username/ParkingSystem.git
  ``
3. Masuk ke direktori proyek:
  ```bash
  cd ParkingSystem
  ```
4. Restore dependensi proyek:
   ```bash
   dotnet restore
  ``
5. Build dan jalankan proyek:
  ```bash
  dotnet run
  ```

## Penggunaan
1. Check-In: Input nomor polisi kendaraan dan jenis kendaraan (Mobil atau Motor). Sistem akan menampilkan biaya parkir dan mengalokasikan lot yang tersedia.
2. Check-Out: Setelah kendaraan keluar, masukkan nomor polisi kendaraan untuk membebaskan lot parkir.
3. Laporan: Lihat laporan untuk mengetahui status parkir, jumlah kendaraan berdasarkan jenis, warna, dan nomor polisi ganjil/genap.
