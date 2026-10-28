# SIPRAGA
Aplikasi web yang memfasilitasi proses pengajuan, verifikasi, dan penandatanganan surat oleh warga dan aparat RT/RW secara digital.

# Dependencies
```
npm install express mysql2 body-parser cors nodemon
```
# How to run
```
node server.js
```
# Tech Stack
Frontend: HTML, CSS, dan JavaScript

Backend: Node.js dengan framework Express.js

Database: MySQL

# Users
**Warga**
Warga merupakan pengguna sistem yang mengajukan surat. Beberapa aktivitas yang dapat dilakukan oleh warga dalam sistem ini antara lain:
- Melengkapi data diri, yang menjadi syarat awal untuk dapat mengajukan surat.
- Melihat atau mengunduh template surat, sehingga warga mengetahui format surat yang dibutuhkan.
- Mengajukan permohonan surat kepada RT melalui sistem.
- Melihat status permohonan surat, fitur ini bersifat opsional dan akan muncul setelah warga mengajukan surat.
- Mencetak surat yang sudah disetujui, setelah surat mendapatkan tanda tangan dari RT dan/atau RW.


**RT**
Pengurus RT memiliki peran sebagai verifikator awal dalam proses pengajuan surat. Aktivitas yang dapat dilakukan oleh RT dalam sistem ini meliputi:
- Menerima dan menandatangani surat, apabila permohonan warga dinilai sesuai.
- Verifikasi surat, untuk memastikan data dan tujuan surat benar.
- Menolak surat, jika terdapat kesalahan atau tidak memenuhi syarat.
- Mengelola data KTP/KK warga, sebagai bagian dari proses validasi data.
- Melihat histori surat masuk dan keluar, untuk kebutuhan dokumentasi dan pelacakan arsip surat.


**RW**
Pengurus RW memiliki fungsi sebagai verifikator lanjutan jika dibutuhkan, khususnya untuk surat yang memerlukan otorisasi lebih tinggi. Aktivitas yang dapat dilakukan oleh RW antara lain:
- Melakukan verifikasi lanjutan, setelah surat diverifikasi oleh RT.
- Menandatangani surat, apabila permohonan dianggap layak dan sesuai.
- Menolak surat, bila permohonan tidak memenuhi ketentuan.
- Melihat histori surat masuk dan keluar, guna memantau aktivitas surat-menyurat di lingkungan RW.

**Dokumentasi**

<img width="929" height="423" alt="image" src="https://github.com/user-attachments/assets/3130d69e-7161-4265-a5f9-eac3cd30ee9e" />
<img width="940" height="316" alt="image" src="https://github.com/user-attachments/assets/ac75025d-74b0-4f43-8304-7ddfacee1a68" />
<img width="940" height="398" alt="image" src="https://github.com/user-attachments/assets/c0bc79f4-e36c-46cb-8da1-f920be54376c" />

<img width="886" height="400" alt="image" src="https://github.com/user-attachments/assets/76430339-bf57-4cd0-9575-1138ee59bd3a" />

<img width="886" height="398" alt="image" src="https://github.com/user-attachments/assets/8092ee1b-175d-4f55-9e26-a496ba075f8b" />

<img width="886" height="400" alt="image" src="https://github.com/user-attachments/assets/382028c8-9520-4405-bf55-a0e4f31c9d86" />

<img width="886" height="398" alt="image" src="https://github.com/user-attachments/assets/4eb7b243-2418-4c19-bd60-e91f9e36886a" />

<img width="886" height="400" alt="image" src="https://github.com/user-attachments/assets/fe07b44f-3e39-47a4-a621-1685b8f4cad5" />

<img width="940" height="423" alt="image" src="https://github.com/user-attachments/assets/35ec7a56-9a73-44ff-995d-09679baf086c" />

<img width="886" height="402" alt="image" src="https://github.com/user-attachments/assets/ccd17dfe-b98b-4799-be7d-ca8387b0cd56" />

<img width="886" height="402" alt="image" src="https://github.com/user-attachments/assets/0b34fa3c-be4a-4318-8410-638cd5ea8c21" />

<img width="1052" height="673" alt="image" src="https://github.com/user-attachments/assets/4d386eb3-b32e-40af-adab-5a26d3fdfbac" />

<img width="886" height="402" alt="image" src="https://github.com/user-attachments/assets/c11f0378-4612-4c80-9719-aa7c44868156" />

<img width="886" height="400" alt="image" src="https://github.com/user-attachments/assets/4449bb3f-82f6-4ab3-90b3-cdb9130a2216" />

<img width="886" height="398" alt="image" src="https://github.com/user-attachments/assets/255ab233-8b88-4b3a-a96a-0e793e93d8b2" />

<img width="886" height="398" alt="image" src="https://github.com/user-attachments/assets/84a32220-5126-4d68-a40f-7e2315a36d65" />













