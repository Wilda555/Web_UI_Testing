# Web UI Testing Framework

## Tujuan Proyek

Proyek ini adalah kerangka kerja pengujian Web UI yang menggunakan Cucumber, Java, Gradle, dan Selenium. 
Tujuannya adalah untuk memberikan kerangka kerja yang terstruktur dan mudah digunakan untuk membuat otomatis pengujian 
pengguna web. Dengan kerangka kerja ini, Develop dan Qa dapat menulis dan menjalankan tes otomatis 
yang memverifikasi aplikasi sehingga dapat berjalan sesuai dengan yang diharapkan.

## Fitur Utama

- Modularitas : Untuk memisahkan proyek sehingga terbentuk beberapa modul
- Keterbacaan : Menggunakan sintaks Gherkin untuk mendefinisikan kasus uji dalam bahasa alami yang mudah dimengerti.
- Otomatisasi : Menggunakan Selenium untuk meng-otomatiskan interaksi dengan browser web.
- Manajemen Dependensi : Menggunakan Gradle untuk mengelola tugas build serta tes.
- Pelaporan : Mendukung pelaporan hasil tes secara otomatis.

## Struktur Proyek

- `src/test/java/features` : Untuk file-file pada fitur gherkin
- `src/test/java/helper/JSONSchemaData` : Berisi file bantuan untuk Json
- `src/test/java/page` : file kelas pada page
- `src/test/java/runners`: Kelas runner untuk mejalankan tes
- `src/test/java/stepdefenitions`: Berisi untuk langkah-langkah pada cucumber

## Tools yang diperlukan

Tools yang digunakan yaitu:
- Java JDK new version 
- IntelIJ Idea
- Gradle
- Browser yang didukung Selenium 

## Push to github

1. **Repositori**:
   `git clone https://github.com/Wilda555/Web_UI_Testing_19.git`
   
