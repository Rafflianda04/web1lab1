# LatihanVCS
## Belajar dasar git

### Membuat paragraf
kode tag paragraf adalah `<p>`
ini adalah tampilannya
![Gambar 1](screenshot/ss1.png)

# instalasi git
download Git, buka website resminya Git(git-scm.com).

Kemudian unduh Git sesuai dengan arsitektur komputer kita.Kalau menggunakan 64bit, unduh yang 64bit.
Begitu juga kalau menggunakan 32bit.

jika sudah terinstal di windows.untuk mencobanya, silahkan buka CMD atau PowerShell kemudian ketik perintah

git --version `<p>`
 ini adalah tampilannya
![Gambar 2](screenshot/ss2.png)

# Menambahkan Global Config
Pada saat pertama kali menggunakan git, perlu dilakukan konfigurasi

user.name dan user.email

konfigurasi ini bisa dilakukan untuk global repostiry atau individual repository.

apabila belum dilakukan konfigurasi, akan mengakibatkan terjadi kegagalan

saat menjalankan perintah git commit

Config Global Repository
$ git config --global user.name “nama_user”

$ git config --global user.email “nama_user”