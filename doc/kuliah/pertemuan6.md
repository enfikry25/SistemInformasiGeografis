**Rangkuman Pertemuan 6 Sistem Informasi Geografis**

 <p align="center"> 
<img src="../../img/GIS6.png" width="400px"> 
</p>
 

Latar Belakang Masalah

Sistem informasi geografis terdapat shapefile, shapefile disini kita bisa menambahkan, mengedit, menghapus dan melihat

Cara membuat data geometri shapefile yaitu:

1. --Buka python di command prompt
2. --import shapefile
3. --sf = shapefile.Writer(shapeType=1)
4. --sf.shapeType -&gt; untuk mengecek
5. --sf.field(&#39;NAMA&#39;,&#39;B&#39;,&#39;30&#39;)
6. --sf.field(&#39;PEMILIK&#39;,&#39;B&#39;,&#39;30&#39;)
7. --sf.record(&#39;ANU&#39;,&#39;Udin&#39;)
8. --sf.point(10,10,0,0) -&gt; disini point bisa diganti line atau polygon sesuai keinginan
9. --sf.save(&#39;anu.shp&#39;) -&gt; untuk menyimpan

Cara Mengedit data geometri shapefile yaitu:

1. --Buka python di command prompt
2. --import shapefile
3. --sf = shapefile.Editor(shapefile=&#39;anu.shp&#39;)
4. --sf.point(19,19,0,0)
5. --sf.record(&#39;Ani&#39;,&#39;Budi&#39;)
6. --sf.save(&#39;anu&#39;)

Cara menghapus data geometri shapefile yaitu:

1. --Buka python di command prompt
2. --import shapefile
3. --e = shapefile.Editor(&#39;anu.shp&#39;)
4. --e.shape(1) -&gt; record ke berapa
5. --e.delete(1)
6. --e.save(&#39;anu&#39;)

Cara menampilkan data geometri shapefile yaitu:

1. --Buka python di command prompt
2. --import shapefile
3. --sf = shapefile.Reader(&#39;anu.shp&#39;)
4. --sf.record() -&gt; semua record
5. --sf.record(0) -&gt; record ke 1
6. --sf.record(1) -&gt; record ke 2
7. --sf.shapes()(0).points -&gt; menampilkan

Penutup

Kesimpulan

Semuanya dapat kita lakukan bila kita praktikum sendiri bagaimana cara membuat, mengedit, menghapus dan menampilkan data shapefile menggunakan python.

Saran

Saran dari saya pelajari cara membuat, mengedit, mengpahus dan menampilkan pada data shapefile lebih dalam lagi, agar kita tau lebih dalam dan melakukan praktikum mandiri.

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

1. smallseotools - Link  [https://drive.google.com/open?id=0B84lVJ2VqAfRQWFOTGlkNTdFd2c](https://drive.google.com/open?id=0B84lVJ2VqAfRQWFOTGlkNTdFd2c)
2.  searchenginereports - Link  [https://drive.google.com/open?id=0B84lVJ2VqAfRVnlCeDlxREl5eVk](https://drive.google.com/open?id=0B84lVJ2VqAfRVnlCeDlxREl5eVk)