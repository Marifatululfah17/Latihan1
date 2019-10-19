#Latihan 1
                                        Tutorial membuat file README.md
1.	Langkah pertama kita harus memasang aplikasi git terlebih dahulu dengan mengunjungi website resminya di https://git-scm.com/ .
[image](https://user-images.githubusercontent.com/56728542/67138243-37fb2c00-f1f5-11e9-929f-6fdb9dd9d3f3.png)
2.	Setelah selesai di download dan di install, silahkan dicoba dengan menggunakan CMD dengan mengetikan perintah git –version.

![image](https://user-images.githubusercontent.com/56728542/67138270-90322e00-f1f5-11e9-8447-9d833cc3a4cd.png)
3. mudian pada saat pertama kali kita menggunakan git ,kita perlu melakukan konfigurasi user.name dan user e-mail. Dengan memasukan perintah
![image](https://user-images.githubusercontent.com/56728542/67138293-d12a4280-f1f5-11e9-9a06-dd576f89a678.png)
![image](https://user-images.githubusercontent.com/56728542/67138305-ed2de400-f1f5-11e9-8bf0-6958c1f3ba29.png)
Seperti gambar dibawah:
![image](https://user-images.githubusercontent.com/56728542/67138313-16e70b00-f1f6-11e9-8c6c-b8573599c76f.png)
4.	Kemudian langkah selanjutnya adalah membuat Repositori Local
•	Buat folder di D:\Labs_pemrograman1 di windows explorer
•	Kemudian klik kanan pada folder atau direktori tersebut, lalu pilih git hub here.
![image](https://user-images.githubusercontent.com/56728542/67138330-44cc4f80-f1f6-11e9-8c5e-ac7859c32f80.png)
Sehingga akan muncul gitbash command
•	Kemudian membuat project praktikum pertama dengan nama Latihan1 dengan mengetikan perintah seperti dibawah ini:
$ mkdir latihan1
$ cd latihan1
![image](https://user-images.githubusercontent.com/56728542/67138335-6c231c80-f1f6-11e9-9a55-e0f3fa93a710.png)
Kemudian directory aktif menjadi :d:\labs_pemrograman\Latihan1
•	Kemudian buat repository local, dengan menggunakan perintah
$ git init
![image](https://user-images.githubusercontent.com/56728542/67138343-9674da00-f1f6-11e9-82cd-17bbd5c20405.png)
Selamat,repository baru berhasil diinisialisasi,dengan nama hidden .git
5.	Menambahkan file baru pada repository
DIsini kita akan membuat suatu file bernama README.md . dengan mengetikan perintah
$ echo “#Latihan 1” >> README.md
![image](https://user-images.githubusercontent.com/56728542/67138368-e489dd80-f1f6-11e9-9e38-63703bd0359f.png)
File README.md berhasil dibuat
![image](https://user-images.githubusercontent.com/56728542/67138379-097e5080-f1f7-11e9-990f-72b19c12b2b3.png)

Kemudian untuk menambahkan file README.md  yang baru saja dibuat gunakan perintah
$ git add README.md
![image](https://user-images.githubusercontent.com/56728542/67138391-274bb580-f1f7-11e9-9e87-6348125a6b05.png)
Kemudian untuk menyimpan perubahan yang ada kedalam database repository local yang telah dibuat,gunakan perintah
•	$git commit -m “file pertama saya”
![image](https://user-images.githubusercontent.com/56728542/67138398-46e2de00-f1f7-11e9-845b-ee519f5b471a.png)
Perubahan pun berhasil disimpan!
6.	Membuat repository server dengan menggunakan github.com
![image](https://user-images.githubusercontent.com/56728542/67138441-f7e97880-f1f7-11e9-9b31-cc3a1837600d.png)

Lalu buat akun github
![image](https://user-images.githubusercontent.com/56728542/67138453-21a29f80-f1f8-11e9-9505-3134725a0415.png)
Lalu lengkapi proses registrasinya
![image](https://user-images.githubusercontent.com/56728542/67138457-40a13180-f1f8-11e9-89c6-b6b7f59f51a7.png)
![image](https://user-images.githubusercontent.com/56728542/67138461-5878b580-f1f8-11e9-8c92-04b4347a0825.png)
Lalu klik new repository
![image](https://user-images.githubusercontent.com/56728542/67139502-ddb69700-f205-11e9-9773-a534a72c44d7.png)
Kemudian github akan meminta verifikasi dari e-mail
![image](https://user-images.githubusercontent.com/56728542/67139512-f626b180-f205-11e9-9747-a5e51764d071.png)
Setelah diverifikasi,create a new repository atau buat repository baru
![image](https://user-images.githubusercontent.com/56728542/67139529-24a48c80-f206-11e9-99a2-319381af61bd.png)
kemudian tambahkan remote repository untuk menyimpan setiap perubahan pada local repository, sehingga dapat diakses oleh banyak user. Dengan perintah 
$git remote add origin[url]
![image](https://user-images.githubusercontent.com/56728542/67139543-50c00d80-f206-11e9-8f88-6a38bfc2ef98.png)
•	Setelah menambahkan, langkah selanjutnya adalah mengirimkan perubahan pada local repository ke server gunakan perintah git push.
$git push -u origin master
![image](https://user-images.githubusercontent.com/56728542/67139555-70efcc80-f206-11e9-969c-3c74818ec8ac.png)
Kemudian untuk melihat hasilnya pada server repository buka github.com arahkan kepada repositorynya
![image](https://user-images.githubusercontent.com/56728542/67139571-98df3000-f206-11e9-88fc-7291b909d587.png)
maka perubahan akan terlihat pada tampilan tersebut
Selanjutnya adalah clone repository atau mengcopy repository server
Untuk melakukan cloning, gunakan perintah git clone [url]
![image](https://user-images.githubusercontent.com/56728542/67139578-b44a3b00-f206-11e9-9ccc-75b0bcd7936e.png)
Selamat file README.md selesai dibuat!
![image](https://user-images.githubusercontent.com/56728542/67139592-ce841900-f206-11e9-82f7-22e600571845.png)
![image](https://user-images.githubusercontent.com/56728542/67139598-e3f94300-f206-11e9-8167-f20ffadbe4ea.png)
