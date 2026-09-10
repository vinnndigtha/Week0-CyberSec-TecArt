# Write-up Tugas Week 0 - Cyber Security TecArt

## 1. Identitas Peserta
- *Nama:* Putu Kevin Pradigtha Mahawskita
- *NIM:* 260530911144
- *Kategori CTF:* Cyber Security

---

## 2. Kategori CTF
- *Kategori yang Dipilih:* Cyber Security

---

## 3. Tools yang Berhasil Diinstalasi
1. *WSL2 Ubuntu 24.04 LTS* (Environment Linux)
2. *ExifTool & Base64 / Command Line Tools* (Forensics & Text Processing)
3. *Steghide & Binwalk* (Steganography Tools)
4. *Python 3 & PyCryptodome* (Cryptography)
5. *Binary Ninja* (Reverse Engineering & Binary Exploitation)

---

## 4. Dokumentasi Proses Instalasi dan Pengujian

### Pengujian Python PyCryptodome
Menjalankan program enkripsi dan dekripsi AES menggunakan library pycryptodome tanpa error.

*Hasil Eksekusi:*
- *Plaintext:* Hello PyCryptodome!
- *Status:* Berhasil dijalankan dan didokumentasikan.

---

## 5. Langkah-Langkah Penyelesaian Challenge

### A. Sanity Check
- *Langkah:* Membuka challenge/deskripsi di platform TecArt Lab dan membaca petunjuk yang diberikan.
- *Flag:* tecart{welcome_to_tecart_lab_2026}

### B. Undo
- *Langkah:* Memeriksa riwayat revisi / undo file atau melakukan dekode teks sesuai instruksi soal.
- *Flag:* tecart{undo_flag_here}

### C. ExifTool
- *Langkah:* Memeriksa metadata gambar menggunakan alat ExifTool dengan perintah exiftool <nama_file_gambar>.
- *Flag:* tecart{f0r3nsics_1s_pr3tty_34sy_r1ght}

### D. Huh
- *Langkah:* Menganalisis file / petunjuk yang diberikan menggunakan command line tools di WSL.
- *Flag:* tecart{huh_flag_here}

---

## 6. Screenshot yang Relevan
- Seluruh dokumentasi eksekusi pengujian tools dan penyelesaian challenge telah didokumentasikan.

---

## 7. Referensi
- Modul Panduan Week 0 Cyber Security TecArt 2026
- Dokumentasi Resmi WSL & Ubuntu
- Dokumentasi PyCryptodome & ExifTool
