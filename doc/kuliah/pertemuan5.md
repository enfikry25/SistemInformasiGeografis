**Rangkuman Pertemuan 5**  **Sistem Informasi Geografis**

 <p align="center"> 
<img src="../../img/GIS5.png" width="400px"> 
</p>
 

Latar Belakang Masalah

Pada sistem informasi geografis (GIS) terdapat data geospasial, didalam data geospasial ini ada 2, data vektor dan data raster. Kedua vektor dan data raster memiliki sistem referensi spasial. Ini adalah lintang dan bujur yang menentukan letak dimana posisi bumi.

Cara menambahkan record :

Import Shapefile a = shapefile.writer()

SHP file Geometri

a.point(x,y) a.poly([x,y],[x,y])

DBF file Table

a.field(&#39;namafolder&#39;,&#39;C&#39;,&#39;4&#39;) a.record(&#39;BDG&#39;)

Disimpan dengan Method

a.save(&#39;file.shp&#39;)

Menambahkan data :

1. Poin : poly([a,b], [c,d])
2. Polygon : field(&#39;kota&#39;,&#39;C&#39;,&#39;4&#39;)

Membuat Attribute :

a.field(&#39;Kota&#39;,&#39;C&#39;,&#39;4&#39;) a.record(&#39;Bandung&#39;)

Menyimpan Shapefile :

a.save(&#39;namafile&#39;)

Parameter Writer :

-.Shapefile Poin : a.point(&#39;10&#39;,&#39;12&#39;)

-.Shapefile Polygon : a.poly(ports = ([3.5], [5,5] , [5,7] ))

-.Shapefile Polyline : a.ports([3.5], [5,5] , [3,5], shapetype.shapefile.polyline)

Penutup

Kesimpulan

Jadi jenis data spasial memberikan informasi bahwa komputer membutuhkan untuk merekonstruksi data spasial. Kita dapat menggunakan attribut yang sudah disediankan dalam paramater writer ada yaitu, .shapefile point, .shapefile polygon, .shapefile polyline.

Saran

Saran dari saya terus pelajari shapefile lebih dalam lagi, agar kita tau lebih baik dan melakukan praktikum mandiri.

- Nama : Entol Achmad Fikry Ilhamy
- NPM : 1144115
- Kelas : 3C
- Prodi : D4 Teknik Informatika
- Mata Kuliah : Sistem Informasi Geografis

Referensi :

Link Github : [https://github.com/enfikry25/SistemInformasiGeografis](https://github.com/enfikry25/SistemInformasiGeografis)

Referensi :

1. [http://sigitprabowoo.blogspot.co.id/2013/06/sistem-informasi-geografis-ringkasan-sig.html](http://sigitprabowoo.blogspot.co.id/2013/06/sistem-informasi-geografis-ringkasan-sig.html)

Scan Plagiarisme

1. smallseotools - Link  [https://drive.google.com/open?id=0B84lVJ2VqAfRNVY3T3ZIVXlKd2c](https://drive.google.com/open?id=0B84lVJ2VqAfRNVY3T3ZIVXlKd2c)
2. searchenginereports - Link  [https://drive.google.com/open?id=0B84lVJ2VqAfRWllhTzN2cG0talU](https://drive.google.com/open?id=0B84lVJ2VqAfRWllhTzN2cG0talU)