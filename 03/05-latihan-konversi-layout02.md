# Latihan 2

## Persiapan

Bukalah project **Aplikasiku** pada starter code yang sudah disediakan, dalam
project ini sudah disediakan screen layout desain serta asset yang akan
digunakan untuk membuat aplikasi.

## Screen Layout Desain

Screen layout desain sudah disediakan di dalam starter code layout ini. Layout
dapat Anda lihat pada folder `design`. Untuk melihat isi folder design, ganti
view pada Android Studio menjadi `project`

![folder design](images/03folderdesign2.png)

## Cara Import Drawable

Untuk mengubah desain layout menjadi layout android xml, diperlukan asset berupa
potongan gambar yang sudah disesuaikan ukurannya. Resolusi asset pada Android
mulai dari `hdpi`, `mdpi`, `xdpi`, `xxhdpi`, dan `xxxhdpi`. Untuk semua layout
pada folder design sudah dipotongkan dan disiapkan gambarnya di dalam starter
code.

Jika anda ingin mengetahui proses import drawable, sebagai informasi tambahan
proses untuk memasukkan aset gambar ke folder `res` pada Android Studio
dilakukan dengan cara berikut,

1. Buka tab Resource Manager
   ![resource manager](images/03resourcemanager.png)
2. Klik tombol `+`
   ![resource manager plus](images/03resourcemanagerplus.png)
3. Pilih menu import drawables
   ![import drawable](images/03imagedrawable.png)
4. Select semua folder kemudian klik open
   ![import](images/03importhdpo.png)
5. Pilih gambar yang akan di import kemudian klik import
   ![import again](images/03importhem.png)

## Cara Import Custom Font

Pada starter code juga sudah disediakan dua varian custom font yang dapat
digunakan pada layout android. Untuk mengimport custom font dilakukan dengan
langkah langkah berikut,

1. Klik kanan pada folder `res` kemudian pilih **New -> Android Resource Directory**

![import font](images/03resourcedirectory.png)

2. Pada Resource type, pilih `font`
   ![font](images/03fontfolder.png)

3. Copy dan paste custom font yang Anda miliki ke dalam folder font yang Anda
   buat sebelumnya.

   > **Catatan**: Font yang Anda copy kedalam folder harus menggunakan huruf
   > kecil dan disambungkan dengan menggunakan underscore jika lebih dari satu
   > suku kata.
