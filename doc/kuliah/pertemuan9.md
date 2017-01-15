##Rangkuman Pertemuan 9 Sistem Informasi Geografis

##“Web Service Geospasal & Open Geospatial Consortium"

##Latar Belakang<br>
1.	Apa yang di maksud Web Map Service (WMS)?
2.	Apa yang di maksud Web Coverage (WCS)?
3.	Apa yang di maksud Web Coverage Processing Service (WCPS)?
4.	Apa yang di maksud Open GIS Location Service (OpenLS)?

##Geospasial Web Services Menurut Jenis<br> 
Untuk refeerensi dan implementasi sesuai standar OGC. implementasi referensi yang berfungsi penuh, dan orang-orang terhadap yang lain dievaluasi. Implementasi compliant standar berkaitan dengan perangkat lunak server-side, dan dianggap berfungsi penuh sebagai diuji. pelaksanaannya dapat dipertimbangkan, tetapi tidak dijamin, untuk beroperasi dengan produk standar OGC dilaksanakan dengan baik lainnya.

##1. WEB MAP SERVICE (WMS)<br>
WMS meenyediakan pengguna dengan sarana untuk melayani peta georeferensi tersedia dari server GIS melalui web. Server menggunakan implementasi WMS 1,0 menghasilkan peta, menjawab pertanyaan dasar, dan berkomunikasi fungsi mereka ke program lain melalui GetMap, GetFeatureInfo dan GetCapabilities interface. Melalui antarmuka GetFeatureInfo, pengguna dapat mengambil atribut Info yang berkaitan dengan fitur dipetakan. WMS diimplementasikan di lebih dari 280 produk. Jika pengguna meminta peta dengan kotak yang sama melompat-lompat, sistem referensi spasial, dan ukuran output, mereka dapat menghasilkan peta komposit dibangun dari sumber yang terletak di jaringan WMS didistribusikan. 

##2. Web Coverage Service (WCS)<br> 
WCS, raaster standar pelayanan OGC ini, mengambil "coverage" atau informasi geospasial yang berkaitan dengan fenomena multidimensi pada titik-titik dalam ruang yang berbeda-beda di wilayah geografis. Setiap WCS menyediakan akses ke informasi "cakupan grid" sederhana atau melalui tiga operasi: GetCapabilities, DescribeCoverage, dan GetCoverage. Informasi (tersedia data dan metadata), meskipun tidak ditampilkan oleh WCS, dapat digambarkan oleh WMS, digunakan dalam multi-nilai pertanggungan, atau digunakan dalam model ilmiah. fungsinya memfasilitasi subsetting, scaling, proyeksi ulang, dan encoding format grid data. 
 
##3. Web Coverage Processing Service (WCPS)<br> 
WCPS adalah perpaanjangan dari WCS v. 1.1.2 dan didasarkan pada WCPS bahasa standar antarmuka (http://www.opengeospatial.org/standards/wcps).The permintaan izin pengolahan bahasa protokol-independen "coverage" atau informasi geospasial digital multi-dimensi yang bervariasi secara spasial dan / atau temporal. Hal ini memungkinkan, ekstraksi, pengolahan, dan fungsi analisis yang berkaitan dengan sensor, gambar dan data statistik yang diwakili oleh pertanggungan. Hal ini diduga menjembatani WCS dan WPS. Sejak WCS terbatas coverage segiempat, data multi-dimensi tersedia di titik-titik grid. Interpolasi dapat memberikan data antara titik-titik grid. Petascope (http://www.petascope.org) adalah implementasi referensi dari WCPS.

##4. Web Features Services (WFS)<br>
The WFS antarmuka meemungkinkan pengguna untuk mengakses dan memanipulasi informasi fitur geospasial dari sumbeer jaringan terdistribusi. operasi dasar termasuk GetCapabilities, DescribeFeatureType dan operasi GetFeature. operasi yang lebih kompleks yang tersedia melalui antarmuka layanan WFS-T dijelaskan di bawah.

##5. Open GIS Location Service (OpenLS)<br> 
OpenLS merupakan standar antar muka yang terdiri dari satu set layanan dasar dan lebih kompleks. Layanan inti antara lain layanan direktori, layanan gateway, layanan lokasi utilitas (untuk geocode dan membalikkan geokode,), layanan presentasi, dan layanan rute. Layanan direktori membantu pelanggan mengakses tempat terrdekat atau khusus. Layanan gerbang mengambil lokasi dari terminal mobile (perangkat).

##Kesimpulan
Jadi, Web Service geospasial (GWS) membantu pengguna menemukan, akses, dan kadang-kadang memanipulasi data yang menarik di web dinamis dari jaringan terdistribusi. GWS dirancang untuk mengumpulkan data sekali dan memperbarui atau mengeditnya secara real time.

##Saran
Selanjutnya untuk mendalami GWS dengan membaca sumber-sumber yang tersedia di buku maupun internet, dan melakukan praktikum mandiri.
<br>
*	Nama		: Entol Achmad Fikry Ilhamy
*	NPM			: 1144115
*	Kelas		: 3C
*	Prodi		: D4 Teknik Informatika
*	Mata Kuliah	: Sistem Informasi Geografis 
*	Kampus		: Politeknik Pos Indonesia

Link Matakuliah : http://kampus.awangga.net/assignments/sisteminformasigeografis2016

Link Github : https://github.com/enfikry25/SistemInformasiGeografis

Referensi : http://magic.lib.uconn.edu/help/help_OGC.html

Scan Plagiarisme :
*	https://drive.google.com/open?id=0B84lVJ2VqAfRcGxzd2d2bzFIVTg
*	https://drive.google.com/open?id=0B84lVJ2VqAfRUV9tWkxHZlVEXzA