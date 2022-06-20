# Dashboard Tingkat Pengangguran Terbuka (TPT)

## Pendahuluan
  Permasalahan mengenai ketenagakerjaan dan pengangguran hingga saat ini masih menjadi perhatian utama di setiap negara, salah satunya Indonesia. Menurut Nanga (2001), pengangguran merupakan suatu keadaan dimana seseorang yang tergolong dalam angkatan kerja sedang tidak memiliki pekerjaan dan secara aktif sedang mencari pekerjaan. Pengangguran terbuka meliputi mereka yang tidak punya pekerjaan dan mencari pekerjaan, mereka yang tidak punya pekerjaan dan mempersiapkan usaha, mereka yang tidak punya pekerjaan dan tidak mencari pekerjaan karena merasa tidak mungkin mendapat pekerjaan, serta mereka yang sudah punya pekerjaan tetapi belum mulai bekerja (BPS).
  
  Setiap tahun Badan Pusat Statistik (BPS) mengeluarkan publikasi terkait keadaan ketenagakerjaan di Indonesia sebanyak dua kali, yaitu pada bulan Februari dan bulan Agustus. Publikasi tersebut memuat beberapa variabel terkait ketenagakerjaan, salah satunya yaitu Tingkat Pengangguran Terbuka (TPT). TPT merupakan persentase jumlahpengangguran terhadap jumlah angkatan kerja (BPS). Pada Agustus tahun 2021, BPS mencatat Tingkat Penganffuran Terbuka (TPT) di Indonesia sebesar 6,49%. Akan tetapi sangat disayangkan bahwasanya tidak semua data yang ada pada publikasi tersebut tidak memiliki visualisasi. Selain itu, data-data yang ditampilkan juga memiliki variabel atau dimensi lebih dari satu (multidimensi). Sehingga visualisasi data yang ditambilkan juga hanya terbatas pada buku elektronik ataupun infografis yang hanya dapat ditampilkan secara statis, dimana pengguna tidak dapat melakukan interaksi terhadap visualisasi data yang ada. 
  
  Dari permasalahan tersebut maka dibutuhkan suatu visualisasi data interaktif yang dapat menampilkan berbagai data dalam bentuk visualisasi. Menurut Vitaly Friedman (2008), tujuan utama dari visualisasi data adalah kemampuannya untuk memvisualisasikan data, mengkomunikasikan informasi secara lebih jelas dan efektif. Selain itu juga dengan adanya visualisasi data akan lebih menarik pengguna untuk membaca publikasi tersebut. Dengan adanya visualisasi data yang interaktif juga diharapkan mampu memudahkan pengguna untuk memahami data-data terkait Tingkat Pengangguran Terbuka (TPT), dan juga data-data mengenai faktor-faktor yang mempengaruhi Tingkat Pengangguran Terbuka (TPT).
  
  Berdasarkan uraian di atas, maka pada penelitian ini akan mengimplementasikan visualisasi data interaktif publikasi ketenagakerjaan di Indonesia terutama pada hal Tingkat Pengangguran Terbuka (TPT). Selain itu, berpedoman pada penelitian terkait faktor-faktor yang mempengaruhi tingkat pengangguran, juga akan dibuat visualisasi data mengenai faktor-faktor yang mempengaruhi tingkat pengangguran di Indonesia. Sehingga dirumuskan tujuan pada penelitian ini yaitu untuk mengimplementasikan visualisasi data interkatif pada publikasi Tingkat Pengangguran Tebuka (TPT) per provinsi di Indonesia, serta faktor-faktor yang mempengaruhinya. Selain itu juga bertujuan untuk mengetahui jenis visualisasi data interaktif yang sesuai untuk data Tingkat Pengangguran Terbuka (TPT) dan faktor-faktor yang mempengaruhinya.

## Penelitian Terkait
  Nadiar Ahmad Syaripul dan Adam Mukharil Bachtiar pada tahun 2016 melakukan penelitian dengan judul Visualisasi Data Interaktif Data terbuka Pemerintah Provinsi DKI Jakarta : Topik Ekonomi dan Keuangan Daerah. Tujuan penelitian ini adalah membuat visualisasi data yang tepat dari data yang diberikan. Metode yang digunakan pada penelitian ini melalui 4 tahap, yaitu analysis, design strategy, implementation, dan evaluation dengan batasan masalah sebanyak 12 data pada topik ekonomi dan keuangan daerah. Sedangkan proses visualisasi data yang diterapkan pada penelitian ini melalui 7 tahapan, yaitu acquire, parse, filter, mine, represent, refine, dan interact. Hasil yang diperoleh pada penelitian ini merupa statistik yang ditampilkan salam bentuk bar chart atau pie chart. Selain itu juga dilakukan analisis dan visualisasi data menggunakan K-Means untuk melakukan pengelompokan data ke dalam bentuk dua atau lebih kelompok. Kemudian dilakukan post kuesioner dan didapatkan sebanyak 83,6% responden dapat membaca analisis visual dan mengambil insight dari data, sebanyak 14,0% responden dapat membaca analisis visual tetapi tidak dapat mengambil insight, dan sebesar 2,4% responden tidak dapat membaca analisis visual.
  
  Riza Firdhania dan Fivien Muslihatinningsih melakukan penelitian yang berjudul Faktor-Faktor yang Mempengaruhi Tingkat Pengangguran di Kabupaten Jember. Penelitian ini bertujuan untuk menjelaskan hubungan antara jumlah penduduk, inflasi, upah minimum, pertumbuhan ekonomi, dan indeks pembangunan manusia terhadap tingkat pengangguran di Kabupaten Jember. Metode analisis yang digunakan dalam penelitian ini adalah analisis deskriptif dan analisis regresi linear berganda. Hasil yang diperoleh dari penelitian ini adalah secara simultan variabel jumlah penduduk, inflasi, upah minimum, pertumbuhan ekonomi, dan indeks pembangunan manusia berpengaruh signifikan terhadap tingkat pengangguran di Kabupaten jember. Berdasar pada penelitian ini, pada pembuatan visualisasi data kali ini akan ditampilkan visualisasi data terkait variabel Indeks Pembangunan Manusia (IPM), jumlah penduduk, dan upah minimum regional.

# Kajian Literatur

A. Tingkat Pengangguran Terbuka (TPT)

BPS menjelaskan bahwa Tingkat Pengangguran Terbuka (TPT) merupakan persentase jumlah pengangguran terhadap Angkatan Kerja. Angkatan Kerja sendiri merupakan penduduk yang berusia kerja (15 tahun ke atas) yang bekerja atau punya pekerjaan namun sementara sedang tidak bekerja, dan pengangguran. Yang termasuk dalam pengangguran sendiri yaitu penduduk yang aktif mencari pekerjaan, penduduk yang sedang mempersiapkan usaha atau pekerjaan baru, penduduk yang tidak mencari pekerjaan karena merasa tidak mungkin mendapat pekerjaan, dan juga penduduk yang tidak aktif mencari pekerjaan dengan alasan sudah mempunyai pekerjaan tetapi belum mulai bekerja. Tingkat Pengangguran Terbuka (TPT) dapat dihitung menggunakan formula sebagai berikut.

TPT=PP/PAK×100%

dimana :
TPT = Tingkat Pengangguran Terbuka (%)
PP	= jumlah pengangguran (orang)
PAK = jumlah angkatan kerja (orang)
TPT sendiri biasanya digunakan untuk mengindikasikan besarnya persentase angkatan kerja yang termasuk dalam pengangguran.

B. Indeks Pembangunan Manusia (IPM)

IPM diperkenalkan oleh United Nations Development Programme (UNDP) pada tahun 1990 dan dipublikasikan berkala dalam laporan tahunan Human Development Report (HDR). IPM merupakan indikator penting untuk mengukur keberhasilan dalam upaya membangun kualitas hidup manusia. IPM menjelaskan bagaimana penduduk dapat mengakses hasil pembangunan dalam memperoleh pendapatan, kesehatan, pendidikan, dan sebagainya. IPM dibentuk oleh tiga dimensi dasar, yaitu : umur panjang dan hidup sehat, pengetahuan, dan standar hidup layak. Selain itu, IPM juga bermanfaat untuk menentukan peringkat atau level pembangunan suatu wilayah/negara. Bagi Indonesia sendiri, IPM merupakan data strategis karena selain sebagai ukuran kinerja pemerintah, IPM juga digunakan sebagai salah satu alokator penentuan Dana Alokasi Umum (BPS). Pada penelitian ini, digunakan data IPM tahun 2020 yang dihitung menggunakan metode baru. 

Metode baru ini dinilai lebih unggul karena menggunakan indikator yang lebih tepat dan dapat membedakan dengan baik. Metode baru bekerja dengan memasukkan rata-rata lama sekolah dan angka harapan lama sekolah, sehingga dapat diperoleh gambaran yang lebih relevan dalam pendidikan dan perubahan yang terjadi. Selain itu PNB menggantikan PDB karena lebih menggambarkan pendapatan masyarakat pada suatu wilayah. Untuk mewujudkan pembangunan manusia yang baik, ketiga dimensi harus memperoleh perhatian yang sama besar karena sama pentingnya (BPS). 

C. Penduduk

Menurut BPS, Penduduk merupakan semua orang yang berdomisili di wilayah geografis Republik Indonesia selama enam bulan atau lebih. Selain itu mereka yang berdomisili kurang dari enam bulan tetapi bertujuan untuk menetap juga dikategorikan sebagai penduduk.  Akan tetapi pada pelaksanaan SP2020 terdapat pembaharuan konsep penduduk menjadi semua orang yang berdomisili di wilayah NKRI selama satu tahun atau lebih atau mereka yang berdomisili kurang dari satu tahun tetapi bertujuan untuk menetap. Jumlah penduduk dinyatakan dalam ribuan jiwa tau jutaan jiwa. Selain jumlah penduduk hasil sensus, terdapat juga jumlah penduduk hasil proyeksi. 

D. Upah Minimum Regional

Upah Minimum Regional (UMR) adalah suatu standar minimum yang digunakan oleh para pengusaha untuk memberikan upah kepada karyawan atau buruh, di dalam lingkungan usaha atau kerjanya (BPS). UMR yang dimaksud adalah Upah Minimum Provinsi pada tahun 2020. 

# Metodologi
  Metode yang digunakan dalam penelitian ini adalah metode analisis deskriptif. Analisis deskriptif adalah statistik yang digunakan untuk menganalisis data dengan cara mendeskripsikan atau menggambarkan data yang telah terkumpul sebagaimana adanya tanpa bermaksud membuat kesimpulan yang bersifat umum atau generalisasi (Sugiyono, 2017:147). Langkah-langkah yang akan digunakan dalam penelitian ini adalah sebagai berikut : 
  
•	Studi literatur

Informasi yang akan dibutuhkan dalam dashboard ini yaitu beberapa informasi mengenai Tingkat Pengangguran Terbuka (TPT), Indeks Pembangunan Manusia (IPM), jumlah penduduk, dan upah minimum regional.

•	Pengumpulan data

Data yang digunakan pada penelitian ini berupa data tentang Tingkat Pengangguran Terbuka (TPT) dari tahun 2010 hingga tahun 2021, khususnya data bulan Agustus pada setiap tahunnya. Selain itu juga digunakan beberapa variabel yang diadopsi dari penelitian oleh Riza Firdhania dan Fivien Muslihatinningsih. Data tersebut yaitu data Indeks Pembangunan Manusia (IPM) tahun 2020, jumlah penduduk berdasar hasil proyeksi pada tahun 2020, dan data upah minimum regional tahun 2020.

•	Pemilihan tipe dashboard dan desain dashboard

Pada tahap ini bertujuan untuk menentukan teknologi yang akan digunakan dalam pembuatan dashboard dan mengimplementasikan desain dashboard. Visualisasi pada proyek ini akan ditampilkan dalam sebuah dashboard informasi web. Tools yang akan digunakan untuk membuat dashboard informasi web ini adalah Tableau. Kemudian dashboard yang telah dibuat akan dipublikasikan secara online melalui github pages. 
Selain itu, dilakukan proses pembuatan desain mockup dashboard yang menandakan bagaimana antarmuka (interface) dan peletakan komponen-komponen dashboard. Proses desain dashboard ini diperuntukkan dalam bentuk web.

•	Uji coba dan evaluasi

Uji coba dan evaluasi dilakukan dalam dua tahap yaitu mengevaluasi kesesuaian antara tampilan web dengan desain yang telah dibuat dan proses validasi data antara data representatif dalam dashboard dengan data mentah yang digunakan sebagai sumber datanya. 

•	Dashboard Maintenance

Tahap ini merupakan tahap akhir dari proses pengembangan sebuah dashboard. Pada tahap ini dilakukan perawatan berupa perubahan-perubahan yang perlu dilakukan sebagai tindakan dari hasil evaluasi dampak.

# Hasil dan Pembahasan
Hasil dari penelitian ini berupa sebuah website visualisasi data interaktif yang menampilkan visualisasi publikasi Tingkat Pengangguran Terbuka (TPT) beserta faktor-faktor yang mempengaruhi TPT. Data yang digunakan berupa data TPT pada bulan Agustus tahun 2010 hingga tahun 2021, jumlah penduduk hasil proyeksi  tahun  2020, indeks pembangunan manusia tahun 2020, dan upah minimum regional tahun 2020.

Pada halaman awal terdapat judul dashboard beserta hasil visualisasi data yang ditampilkan. Tampilan dari visualisasi data tersebut berbentuk memanjangg ke bawah sehingga untuk mendapatkan hasil visualisasi data yang lain dapat dilakukan dengan menggeser scroll bar ke bawah. 
Pada halaman tersebut juga terdapat tombol menu.

Apabila tombol menu tersebut diklik, akan menampilkan beberapa pilihan yaitu Konsep, dan Download data. Kemudian apabila bagian Download data di-hover akan menampilkan beberapa menu terkait data-data yang digunakan dalam visualisasi data pada penelitian ini. Ketika bagian Konsep diklik atau dibuka, pengguna akan diarahkan menuju halaman website BPS dimana pada halaman tersebut terdapat konsep atau definisi dari Tingkat Pengangguran Terbuka, dan juga siapa saja yang termasuk dalam kategori pengangguran. Kemudian untuk bagian download data, apabila salah satu data dibuka atau dipilih, pengguna juga akan diarahkan ke masing-masing sumber data yang digunakan dalam pembuatan visualisasi data ini. Selain itu, visualisasi data pada penelitian ini memiliki fitur interaktif yang berbeda-beda kegunaannya. Fitur-fitur interaktif yang digunakan antara lain selection, detail on demand, zoom, dan search. 

Fitur selection yang digunakan dalam visualisasi ini digunakan untuk memilih waktu data yang ingin ditampilkan. Tujuannya agar pengguna dapat fokus untuk melihat data yang ingin ditampilkan. Fitur lainnya yang ada pada visualisasi data pada penelitian ini yaitu fitur detail on demand. Fitur ini digunakan untuk menampilkan detail berdasarkan keingginan pengguna dengan cara menyorot provinsi pada choropleth map, titik-titik tahun pada line chart, dan balok-balok pada bar chart. Ketika bagian tersebut disorot oleh pengguna, visualisasi data akan menampilkan detail dari informasi tersebut. 

Selain itu, pada visualisasi data juga terdapat fitur zoom. Akan tetapi fitur ini hanya terdapat pada visualisasi data choropleth map. Pada visualisasi data ini fitur zoom digunakan untuk memperbesar atau memperkecil peta Indonesia yang digunakan. Fitur ini dapat digunakan dengan cara menekan icon zoom pada sebelah kiri atas pada peta atau dengan cara menggunakan scroll menggunakan mouse. Begitu pula dengan fitur search yang juga hanya terdapat pada visualisasi data choropleth map. Melalui fitur search ini pengguna dapat mencari lokasi suatu daerah provinsi yang ada di peta Indonesia tersebut dengan memanfaatkan icon kaca pembesar pada sebelah kiri atas 
choropleth map. 

Jenis visualisasi data yang digunakan dalam melakukan visualisasi data TPT ini sebanyak 3 jenis, yaitu chotopleth map, line chart, dan bar chart. 

A.	Choropleth Map

Choropleth Map digunakan untuk menampilkan data dalam bentuk peta. Setiap daerah pada peta tersebut akan ditampilkan menggunakan warna-warna yang berbeda kecerahannya. Hal ini bertujuan untuk memudahkan pengguna membedakan data antar daerah. Choropleth Map pada visualisasi ini akan menampilkan Tingkat Pengangguran Terbuka (TPT) per provinsi di Indonesia, dimana semakin tua (gelap) warna yang ditampilkan, maka semakin tinggi TPT di provinsi tersebut. Sebaliknya, apabila warna yang ditampilkan semakin cerah maka tingkat TPT di daerah tersebut semakin rendah. 
Pada choropleth map ini juga menggunakan beberapa fungsi interaktif, antara lain selection, zoom, detail on demand, dan search. Fitur selection digunakan untuk memilih waktu data tahun berapa yang ingin ditampilkan, kemudian fitur zoom digunakan untuk memperbesar atau memperkecil peta. Selanjutnya fitur detail on demand digunakan untuk menampilkan informasi dari provinsi yang disorot, dan fitur search digunakan untuk mencari atau menampilkan provinsi mana yang akan dilihat secara detail.

B.	Line Chart
 
Line Chart digunakan untuk menampilkan data yang memiliki trend, baik bulanan, triwulan, semester, maupun data tahunan. Pada visualisasi data kali ini line chart digunakan untuk menampilkan rata-rata TPT untuk setiap tahun. 
Pada line chart digunakan fitur interaktif berupa detail on demand. Dengan adanya fitur ini, apabila kursor diarahkan ke garis pada tahun tertentu, maka akan muncul informasi mengenai rata-rata TPT pada tahun tersebut. 

C.	Bar Chart
 
Bar Chart pada visualisasi data ini digunakan untuk menampilkan data dari masing-masing variabel-variabel yang mempengaruhi pengangguran. Variabel-variabel yang ditampilkan yaitu Indeks Pembangunan Manusia (IPM), jumlah penduduk hasil proyeksi, dan upah minimum regional. Data yang ditampilkan pada visualisasi data kali ini merupakan data tahun 2020. Dari masing-masing variabel, tampilan bar chart diurutkan menurut besarnya nilai, dimana nilai tertinggi akan menempati posisi paling atas. 
Fitur interaktif yang digunakan pada bar chart berupa detail on demand. Fitur ini dapat digunakan pengguna untuk menyorot balok yang ditampilkan. Apabila balok tersebut disorot, maka akan muncul detail informasi terkait provinsi dengan urutan yang diinginkan.

# Kesimpulan
Pada penelitian ini, peneliti berhasil mengimplementasikan visualisasi data interaktif pada data Tingkat Pengangguran Terbuka (TPT) dan faktor-faktor yang mempengaruhi TPT melalui 3 jenis visualisasi data interaktif yaitu choropleth map, line chart, dan bar chart. 
Pada penelitian ini juga peneliti menyadari masih terdapat banyak kekurangan. Oleh karena itu, peneliti memiliki beberapa saran yang dapat dilakukan untuk penelitian selanjutnya, yaitu perlu adanya evaluasi tampilan visualisasi ini kepada pihak lain. Selain itu juga perlu adanya database yang mampu mengintegrasikan antara data yang dikeluarkan oleh BPS dan juga visualisasi data ini, sehingga akan memudahkan dalam memperbarui tampilan visualisasi.

# Link Halaman Proyek Visualisasi Data
https://amnaismawati.github.io/

# Tentang Penulis
Nama  : Amna Ismawati

NIM   : 221910693

Kelas : 3SD1
