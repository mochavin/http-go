# List Repositori go tugas PBKK

1. [Learn Go Basic](https://github.com/mochavin/pbkk-belajar-go)
   - Basic Go programming concepts and exercises

2. [HTTP in Go](https://github.com/mochavin/http-go)
   - Implementation of HTTP server and client using Go

3. [Go Database Access](https://github.com/mochavin/go-database-access)
   - Database operations and management using Go

4. [Gin Framework Introduction](https://github.com/mochavin/intro-gin)
   - Getting started with Gin web framework in Go

# Go Wiki

Go Wiki adalah aplikasi web sederhana yang memungkinkan Anda membuat, mengedit, dan melihat halaman wiki. Aplikasi ini ditulis dalam bahasa pemrograman Go dan menggunakan template HTML untuk rendering halaman.


## Demo

[![Go Wiki Demo](https://github.com/user-attachments/assets/628e8eb6-c60e-4c61-9e25-79541854c05a)](https://github.com/user-attachments/assets/628e8eb6-c60e-4c61-9e25-79541854c05a)

## Fitur

- Membuat halaman wiki baru
- Mengedit halaman wiki yang sudah ada
- Melihat halaman wiki

## Prasyarat

Pastikan Anda telah menginstal Go di sistem Anda. Anda dapat mengunduh dan menginstal Go dari [situs resmi Go](https://golang.org/dl/).

## Cara Menjalankan

1. Clone repositori ini ke direktori lokal Anda:

    ```sh
    git clone https://github.com/mochavin/http-go
    cd http-go/wiki
    ```

2. *Compile* dan jalankan aplikasi:

    ```sh
    go build wiki.go
    ./wiki
    ```

3. Buka browser Anda dan akses:

    ```
    http://localhost:8085/view/TestPage
    ```

## Struktur Proyek

- `wiki.go`: File utama yang berisi logika aplikasi.
- `edit.html`: Template HTML untuk halaman edit.
- `view.html`: Template HTML untuk halaman view.

## Endpoints

- `/view/{PageTitle}`: Melihat halaman dengan judul tertentu.
- `/edit/{PageTitle}`: Mengedit halaman dengan judul tertentu.
- `/save/{PageTitle}`: Menyimpan perubahan pada halaman dengan judul tertentu.

## Contoh Penggunaan

1. Buka browser dan akses `http://localhost:8085/view/TestPage`.
2. Jika halaman tidak ada, Anda akan diarahkan ke halaman edit untuk membuat halaman baru.
3. Tulis konten halaman dan klik "Save".
4. Anda akan diarahkan kembali ke halaman view untuk melihat konten yang baru saja Anda buat.
