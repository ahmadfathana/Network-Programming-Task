#### Kelompok 5
#### Tugas 7 Pemrograman Jaringan
##### Ahmad Fathan Afdhali - 1301164220
##### Yudi Kurniawan - 1301154143


### PHPloy Tool
<p align="justify">
PHPloy merupakan deployment tool Git FTP dan SFTP yang dapat diinstall dengan menggunakan Composer atau PharArchive. PHPloy merupakan file PHP sederhana yang dapat dipanggil melewati bash yang dapat digunakan pada file apa saja. Tools ini bekerja dengan menyimpan file .revision yaitu hash commit yang telah dideploy pada server. Ketika PHPloy dijalankan, PHPloy akan men-download file tersebut dan membandingkannya dengan referensi dari commit di dalamnya dengan commit yang akan kita upload. Setelah itu PHPloy akan menyimpan .revision yang sudah di deploy.
</p>

Cara kerja PHPloy :
<p align="justify">
Pada saat penggunaan PHPloy cara memproses commandnya dengan menggunakan 'php'. Cara kerja phploy adalah melakukan proses upload/delete file .revision yang telah ter commit pada git ke server sehingga tools ini mempermudah developer dalam deployment web project ke live server. Proses ini dilakukan menggunakan command pada terminal dengan perintah-perintah yang telah di definisikan. Berguna melihat perubahan terakhir file.
</p>

### Stack Up Tool
<p align="justify">
Stack Up Tool atau SUP merupakan tool untuk menjalankan script pada beberapa host server namun tidak menggunakan protocol FTP. Koneksi ssh di semua server dibutuhkan jika ingin menggunakan tool ini karena Sup menggunakan protocol SSH yang bisa digunakan untuk deployment namun tidak bisa melakukan manajemen file. Semua managemen dilakukan secara eksplisit pada file konfigurasi, yakni “Supfile”.
</p>

Cara kerja Stack Up Tool:
<p align="justify">
Dengan mengkoneksikan seluruh server terhadap SSH lalu melakukan deployment.
</p>
