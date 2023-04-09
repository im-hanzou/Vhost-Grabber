Vhsot Config Grabber Anti Pegel 
--------------

Config Grabber adalah sebuah program sederhana yang bertujuan untuk mencari informasi konfigurasi database pada website. Program ini bekerja dengan cara melakukan HTTP request ke website dan melakukan pencarian menggunakan regular expression untuk mencari informasi database seperti nama database, username, password, dan host.

### Cara Penggunaan

1.  Pastikan Python 3 dan modul requests, re, dan termcolor telah terinstall di komputer Anda.
2.  Unduh file program Config Grabber atau salin kode program dari file `vhostgrab.py`.
3.  Buka terminal atau command prompt, lalu arahkan ke direktori tempat Anda menyimpan file program Config Grabber.
4.  Jalankan program dengan perintah `python vhostgrab.py`.
5.  Masukkan URL website yang ingin Anda cek, lalu tunggu hingga program selesai bekerja.
6.  Hasil dari program akan disimpan pada file `results.txt` dan jika ada website yang tidak bisa diambil konfigurasinya, maka website tersebut akan disimpan pada file `manual.txt`.
7.  Jika ingin memeriksa lebih dari satu website, jalankan program lagi dari awal dengan mengulangi langkah nomor 4.

### Note : yang diambil hanya joomla dan wordpress 
