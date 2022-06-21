# 221911164-3SD1-Visdat
(Projek UAS take home mata kuliah Visualisasi Data kelas 3SD1 tahun ajaran 2021/2022)

<h2><b>DASHBOARD INTERAKTIF VISUALISASI DATA STATISTIK PENDIDIKAN INDONESIA</b></h2>

<h3><b>Abstrak</b></h3>

<p align="justify">Ringkasan— Sarana dan prasarana pendidikan merupakan salah satu faktor yang memengaruhi kualitas pendidikan. Hasil dan capaian proses pendidikan dapat dilihat dari beberapa indikator, diantaranya Angka Melek Huruf (AMH). Rata-rata lama sekolah, dan tingkat penyelesaian sekolah. Secara umum, penelitian ini bertujuan untuk membuat dashboard interaktif dari visualisasi data statistik pendidikan Indonesia tahun 2019,2020,2021 serta melakukan evaluasi dashboard. Data yang digunakan merupakan data sekunder yang bersumber dari publikasi bps, web BPS, dan web Kemendikbud, serta data primer yang bersumber dari hasil kuesioner responden. Anlisis yang digunakan yaitu deskriptif dan inferensia. Visualisasi yang digunakan adalah choropleth map, pie map chart, stacked bar chard, diagram sunburst, dan bubble map. Visualisasi digabungkan dalam sebuah dashboard interaktif. Berdasarkan hasil evaluasi, dengan jumlah responden 10, didapatkan skor 90 sehingga mendapatkan nilai huruf A yang artinya sangat baik. Berdasarkan uji Mann-Whitney dapat disimpulkan bahwa bahwa tidak ada perbedaan persepsi penilaian antara kedua kelompok responden. Dimana kelompok responden terbagi menjadi dua yaitu kelompok lingkup pendidikan dan  kelompok masyarakat masyarakat umum.</p>

<p align="justify">Kata Kunci— pendidikan, dashboard, visualisasi, system usability scale, mann-whitney</p>

<h3><b>Tujuan Penelitian</b></h3>

1. <p align="justify">Membuat visualisasi data interaktif menggunakan tableau tentang sarana dan prasarana pendidikan yang meliputi jumlah sekolah berdasarkan jenjang pendidikan dan provinsi di Indonesia, jumlah perpustakaan di Indonesia, dan kondisi ruang kelas di Indonesia tahun 2019-2021 sehingga bisa diperoleh gambaran perkembangan sarana dan prasarana pendidikan Indonesia dengan lebih cepat dan menarik.</p>
2. <p align="justify">Membuat visualisasi data interaktif tentang hasil dan capaian proses pendidikan yang meliputi beberapa indikator, yaitu angka melek huruf anak usia ≥15 tahun berdasarkan provinsi, rata-rata lama pendidikan anak usia ≥15 tahun berdasarkan provinsi, serta tingkat penyelesaian pendidikan menurut jenjang pendidikan dan provinsi di Indonesia tahun 2019-2021 sehingga bisa diperoleh gambaran persebaran hasil dan capaian proses pendidikan di tiap provinsi Indonesia dengan cepat dan menarik.</p>
3. <p align="justify">Membangun dashboard interaktif untuk visualisasi data sarana dan prasarana pendidikan serta hasil dan capaian proses pendidikan tahun 2019-2021 yang mampu menyajikan visualisasi data interaktif secara komprehensif.</p>
4. <p align="justify">Untuk mengetahui penilaian terhadap dashboard interaktif visualisasi data statistik pendidikan Indonesi oleh pengguna yang terbagi menjadi dua kelompok pengguna.</p>
5. <p align="justify">Untuk mengetahui perbedaan persepsi penilaian dashboard interaktif visualisasi data statistik pendidikan Indonesia oleh dua kelompok pengguna.</p>

<h3><b>Metodologi Penelitian</b></h3>
<p align="justify">Berikut diagram alur penelitian Dashboard Interaktif Visualisasi Data Statistik Pendidikan Indonesia. </p>

![AlurPenelitian](AlurPenelitian/AlurPenelitian.png)
<p align="center">Gambar 1. Alur Penelitian</p>

<p align="justify"><b>A. Metode Pengumpulan Data</b></p>

<p align="justify">Data yang digunakan dalam penelitian ini merupakan data sekunder dan primer. Data sekunder merupakan data yang diperoleh melalui media perantara atau secara tidak langsung. Dalam penelitian ini, digunakan enam data sekunder yang berasal dari beberapa sumber. Pertama, yaitu data jumlah sekolah berdasarkan jenjang pendidikan SD,SMP, SMA/SMK menurut provinsi di Indonesia yang bersumber dari Data Pokok Pendidikan Direktorat Jendral Pendidikan Anak Usia Dini, Pendidikan Dasar dan Pendidikan Menengah, Kementrian Pendidikan, Kebudayaan, Ristek dan Teknologi semester ganjil untuk tahun 2019/2020, 2020/2021, 2021/2022. Data dapat diakses pada link https://dapo.kemdikbud.go.id/sp. Data kedua dan ketiga yaitu data persentase ruang kelas menurut jenjang pendidikan dan kondisi serta data jumlah perpustakaan sekolah negeri menurut jenjang pendidikan yang bersumber dari publikasi BPS, yaitu Potret Pendidikan Statistik Pendidikan Indonesia Tahun 2019, Statsitik Pendidikan Indonesia Tahun 2020, dan Statistik Pendidikan Indonesia Tahun 2021. Data keempat yaitu angka melek huruf penduduk umur 15-59 tahun menurut provinsi, kelima data rata-rata lama sekolah penduduk umur ≥15 tahun menurut provinsi, data keenam yaitu data tingkat penyelesaian pendidikan menurut jenjang pendidikan dan provinsi. Data keempat, kelima, dan keenam bersumber dari web Badan Pusat Statistik yang dapat diakses pada link https://bps.go.id/.</p>

<p align="justify">Data primer merupakan data yang diperoleh secara langsung yang dikumpulkan dengan metode pengumpulan data, seperti pengisian kuesioner dan lain sebagainya. Dalam penelitian ini, data primer didapatkan dari pengisian kuesioner system usability scale untuk evaluasi dashboard interaktif visualisasi data statistik pendidikan Indonesia. </p>

<p align="justify"><b>B.	Pemilihan Chart dan Pembuatan Visualisasi</b></p>
<p align="justify">Terdapat berbagai jenis chart yang dapat digunakan untuk memvisualkan data. Pemilihan chart disesuaikan dengan jenis data dan kategori yang digunakan.  Untuk melakukan visualisasi data tersebut, peneliti menggunakan tools Tableau.</p>

<p align="justify"><b>C.	Pembuatan Desain dan Publikasi Dashboard</b></p>

<p align="justify">Dashboard merupakan tampilan visual dari informasi penting untuk mencapai satu atau banyak tujuan; dikonsolidasikan dan diatur pada satu layar sehingga informasi dapat dimonitor secara sekilas. Esensi dari dashboard yaitu menyajikan informasi untuk mencapai suatu tujuan tertentu yang berada pada satu layar utuh. Dashboard memiliki mekanisme tampilan yang kecil, ringkas, jelas, dan intuitif. Penataan ruang: tempat yang paling penting dilihat dari kiri atas (jika bahasanya ditulis ke kiri kanan) lalu atur tampilan berikut seperti pola huruf Z dengan informasi paling penting mengikuti pola dari atas ke bawah, kiri ke kanan</p>

<p align="justify">Dashboard yang di desain dengan baik dapat menyajikan data yang terorganisir dengan baik, terkondensasi, spesifik dan disesuaikan untuk pembaca dan tujuan dari organisasi, serta ditampilkan dengan media yang ringkas agar pesan dashboard tersebut tersampaikan dengan jelas. Pembuatan desain dashboard menggunakan tools Tableau. Dashboard dipublikasikan menggunakan server Tableau Publik.</p>

<p align="justify"><b>D.	Evaluasi Dashboard Interaktif</b></p>

<p align="justify">Penelitian ini menggunakan System Usability Scale (SUS) untuk mengevaluasi dashboard interaktif visualisasi data statistik pendidikan Indonesia. Setiawan dan Ravianto (2020), menyebutkan bahwa, System Usability Scale (SUS) adalah kuesioner yang dapat digunakan untuk mengukur usablity sistem pada komputer dari sudut pandang subjektif para pengguna. SUS banyak digunakan untuk mengukur kegunaan dan memiliki beberapa kelebihan. </p>

<p align="justify">Secara teknis, SUS memiliki 10 butir pertanyaan yang dikemas dalam bentuk kuesioner, tetapi dalam pengembangannya bisa dimungkinkan dibuat dalam bentuk gambar yang dinamakan PictorialSUS [11], namun dalam penelitian ini hanya menggunakan kuesioner. Pertanyaan pada kuesioner system usability scale dapat dilihat pada Tabel 1.</p>

![Kuesioner](GambarTabel/Tabel1.png)