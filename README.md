Buka situs Git di google dan ketik (git-scm.com)
Kemudian unduh Git sesuai dengan arsitektur komputer yang kita milik 64 bit atau 32 bit
Setelah diunduh kemudian instal Git
Klik (Next) hingga proses penginstalan terakhir
Sampai dipenginstalan terakhir pilih (View Release Notes), kemudian klik tombol Finish
Setelah Git terinstal di windows, Buka CMD
Ketik Perintah git --version
Kemudian membuat Global Config dengan memasukan perintah(git config --globsl user.name "Muhamad Freddy") dan (git config --globsl user.email "Muhamadfredy31")
Buatlah folder baru dengan nama Lab1
Kemudian klik kanan folder Lab1 dan pilih Git Bash
Ketik perintah (mkdir latihan1)
Trus ketik perintah (cd latihan1)
setelah itu membuat repository Local dengan mengetik perintah (git init)
Kemudian membuat file repository bernama README.md dengan mengetik perintah (echo "#Latihan 1" >> README.md)
Membuat file baru dalam README.md dengan mengetik perintah(git add README.md)
Untuk merubah penyimpanan ke dalam database ketik perintah (git commit -m "File pertama saya")
Setelah itu buka situs http://github.com dan buatlah akun terlebih dahulu.
Kemudian klik tombol (start a project)
Atau dapat klik (icon +) dan klik New Repository
Setelah itu isi nama Repositoryory (Latihan1), lalu klik tombol (Create repository)
Salin URL untuk menambahkan Remote Repository
Kemudian buka Git Bash dan ketik perintah (git remote add origin https://github.com/Muhamadfredy31/Latiha1.git)
Selanjutnya untuk mengirim perubahan dari local repository ke server dengan mengetik perintah (git push -u origin mater) 
Lalu tunggu hingga 100% semua, apabila sudah 100% artyinya repository local sudah berhasil di pindahkan ke server
Untuk melihat hasilnya pada server, buka halaman website github.com
kemudian mengclone repository dengan mengetik perintah (git clone https://github.com/Muhamadfredy31/Latiha1.git)