[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/tbEHDGEc)
# Git and Github Introduction

| Nama  | Division        | Sub-Division  |
| ----- | ---------- | ---------- |
| Nibras Faros Siahaan | ELC | Microcontroller |

## Cara Menggunakan Git dan Github
### 1. Unduh dan pasang Git pada PC/Laptop
    https://git-scm.com/downloads
### 2. Buat Akun Github
    https://github.com/join
### 3. Mengatur Git Bash atau Terminal
    git config --global user.name (masukkan username)
    git config --global user.email (masukkan email)
### 4. Membuat SSH Keys di GitHub
#### 1) Buka GitHub dan Masuk Ke Settings -> "SSH and GPG keys" -> "New SSH Key"
#### 2) Untuk Membuat Kunci, Buka Git Bash dan Masukkan Perintah Berikut:
     ssh-keygen -t ed25519 -C (masukkan email)
     >> Kemudian tekan enter 2 kali
#### 3) Salin SSH key yang Telah Dibuat dengan Perintah Berikut:
     clip < ~/.ssh/id_ed25519.pub
#### 4) Tempelkan Untuk Memasukkan Kunci Yang Telah Disalin ke Bagian Key di Pengaturan New SSH Key di GitHub

    
## Membuat Repositori
### 1. Buka Laman Github
    https://github.com
    Lakukan Log-in dengan akun yang telah dibuat
### 2. Isikan Nama Repositori yang Diinginkan Lalu Pilih "Public" Setelah Itu Pilih "Create Repository"
    Lakukan centang pada "Add a README file"
### 3. Pilih Menu "Code" Lalu Pilih "SSH" Setelah Itu Salin Link SSH
    Contoh Link : git@github.com:(namapengguna)/(namarepositori).git


## Push File dari Lokal ke Github
### 1. Buat Folder dengan Nama yang Sama dengan Nama Repositori lalu Buka Folder yang telah dibuat
### 2. Buat File Baru untuk Diunggah ke Github
### 3. Klik Kanan pada Mouse Lalu Pilih "Open Git Bash here"
### 4. Lalu Masukkan Command Berikut pada Git Bash
    git init
   	git remote add origin (link SSH yang telah di salin)
   	git branch -M main
    (Untuk memastikan folder lokal sama dengan folder di github maka ketik : git pull origin (branch yang ingin didownload))
### 5. Untuk Mengunggah File pada Folder Lokal, Masukkan Command Berikut pada Git Bash
    git add .
    git commit -m "(deskripsi bebas)"
    git push origin (branch yang akan ingin diunggah)

## Membuat Branch Baru Menggunakan Git 
### 1. Buka Git Bash pada File yang Terhubung dengan Repositori
### 2. Masukkan Command Berikut Pada Git Bash
    git checkout -B (nama branch yang diinginkan)
### 3. Untuk Pindah Branch Dapat Memasukkan Command Berikut
    git branch -d (nama branch yang ingin dihapus)

## Menghapus Branch Menggunakan Git
### 1. Lakukan Pindah Branch dengan Command Berikut
    git checkout (nama branch yang diinginkan)
### 2. Hapus Branch yang Diinginkan dengan Command Berikut
    git branch -d (nama branch yang ingin dihapus)

## Menggabungkan Brench
### 1. Pindah ke branch yang ingin digabung:
    git checkout (nama branch)
### 2. Gabungkan branch lain ke branch saat ini:
    git merge nama-branch-lain

## Kloning Repositori
### 1. Masuk ke Git Bash pada Folder yang diinginkan
### 2. Masukkan Command Berikut:
    git clone https://github.com/(namapengguna)/(namarepositori).git

## Melihat riwayat Commit
### 1. Masuk ke Git Bash pada Folder yang diinginkan
### 2. Untuk melihat riwayat commit dalam repository:
    git log

## Early Procedure

Kunjungi https://git-scm.com/downloads dan download sesuai platform dan juga pilih varian yang sesuai dengan device

## Create Repository

## Push File from Local to Github

## Create New Branch in Github 

## Delete Branch in Github

## Merging Branch in Github

## Other Procedure
