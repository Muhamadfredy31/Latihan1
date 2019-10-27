1. Buka situs Git di google dan ketik (git-scm.com).
2. Kemudian unduh Git sesuai dengan arsitektur komputer yang kita milik 64 bit atau 32 bit.
3. Setelah diunduh kemudian instal Git.
4. Klik (Next) hingga proses penginstalan terakhir.
5. Sampai dipenginstalan terakhir pilih (View Release Notes), kemudian klik tombol Finish.
6. Setelah Git terinstal di windows, Buka CMD.
7. Ketik Perintah git --version.
8. Kemudian membuat Global Config dengan memasukan perintah(git config --global user.name "Muhamad Freddy") dan (git config --globsl user.email "Muhamadfredy31").
9. Buatlah folder baru dengan nama Lab.
10.Kemudian klik kanan folder Lab1 dan pilih Git Bash.
11. Ketik perintah (mkdir latihan1).
12. Lalu ketik perintah (cd latihan1).
13 setelah itu membuat repository Local dengan mengetik perintah (git init).
14. Kemudian membuat file repository bernama README.md dengan mengetik perintah (echo "#Latihan 1" >> README.md).
15. Membuat file baru dalam README.md dengan mengetik perintah(git add README.md).
16. Untuk merubah penyimpanan ke dalam database ketik perintah (git commit -m "File pertama saya").
17. Setelah itu buka situs http://github.com dan buatlah akun terlebih dahulu.
18. Kemudian klik tombol (start a project).
19. Atau dapat klik (icon +) dan klik New Repository.
20. Setelah itu isi nama Repositoryory (Latihan1), lalu klik tombol (Create repository).
21. Salin URL untuk menambahkan Remote Repository.
22. Kemudian buka Git Bash dan ketik perintah (git remote add origin https://github.com/Muhamadfredy31/Latiha1.git).
23. Selanjutnya untuk mengirim perubahan dari local repository ke server dengan mengetik perintah (git push -u origin mater). 
24. Lalu tunggu hingga 100% semua, apabila sudah 100% artyinya repository local sudah berhasil di pindahkan ke server.
25. Untuk melihat hasilnya pada server, buka halaman website github.com.
26. kemudian mengclone repository dengan mengetik perintah (git clone https://github.com/Muhamadfredy31/Latiha1.git).
