# run-a-scan-using-Nmap-on-Windows
Untuk menjalankan pemindaian menggunakan Nmap di Windows, Anda dapat mengikuti langkah-langkah berikut:
## 1. Unduh dan Pasang Nmap:

### > Kunjungi situs web resmi Nmap: https://nmap.org/download.html.
### > unduh versi stabil terbaru untuk Windows.
### > Jalankan penginstal dan ikuti petunjuk yang muncul untuk menginstal Nmap di sistem Windows Anda.
![image](https://github.com/firmansultoni/run-a-scan-using-Nmap-on-Windows/assets/113542409/07505b13-639f-4d18-af4e-a44f2ed44287)
## 2. Buka Command Prompt:
### > Tekan Win + R untuk membuka dialog Run.
### > Ketik cmd dan tekan Enter untuk membuka Command Prompt.
![image](https://github.com/firmansultoni/run-a-scan-using-Nmap-on-Windows/assets/113542409/25af0fdc-036a-40e4-a17f-eaf62feb1c28)
## 3. Cari situs yang akan di uji coba dan cari tahu alamat ip nya dengan CMD :
### > Kode perintah  `ping nasa.gov` 
### > Alamat ip  `23.22.39.120`
![image](https://github.com/firmansultoni/run-a-scan-using-Nmap-on-Windows/assets/113542409/05144470-0248-4bd0-b7ef-0b39ad8d19c2)
## > Jalankan Pemindaian Nmap: 
### > Copy alamat ip ke NMAP dan mulai scan
![image](https://github.com/firmansultoni/run-a-scan-using-Nmap-on-Windows/assets/113542409/2c503d93-0c51-4ecf-bc55-ac598d919dab)

# Penjelasan dari Hasil Output Scanning 
## Port Terbuka:

### Port 21/tcp: Diidentifikasi sebagai menjalankan layanan FTP.
### Port 53/tcp: Menjalankan layanan DNS (Unbound).
### Port 80/tcp: Menjalankan layanan HTTP dengan nginx 1.18.0 (Ubuntu). Judul HTTP menunjukkan pengalihan ke https://www.nasa.gov/.
### Port 443/tcp: Menjalankan layanan SSL/HTTP dengan nginx 1.18.0 (Ubuntu). Judul HTTP menunjukkan bahwa permintaan HTTP murni dikirim ke port HTTPS.

## Informasi Perangkat/Sistem Operasi:

### Tipe perangkat diidentifikasi sebagai WAP (Wireless Access Point) atau ponsel.
### Menjalankan versi kernel Linux 2.4.X dan 2.6.X.
### Detail sistem operasi yang mungkin mencakup Tomato 1.28 (Linux 2.4.20), firmware Tomato (Linux 2.6.22), dan ponsel Sony Ericsson U8i Vivaz.

## Informasi Layanan:

### Server web menggunakan nginx 1.18.0 di Ubuntu.
### Judul HTTP menunjukkan pengalihan ke situs web NASA untuk port 80 dan permintaan HTTP murni dikirim ke port HTTPS (443).


