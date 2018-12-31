# Perancangan-SI
PERANCANGAN SISTEM INFORMASI

Perancangan sistem informasi merupakan pengembangan sistem baru dari sistem lama yang ada, dimana masalah-masalah yang terjadi pada sistem lama diharapkan sudah teratasi pada sistem yang baru.
Sekarang dibahas:
-	Siklus hidup
-	Analisis Perancangan

SIKLUS HIDUP PENGEMBANGAN SISTEM INFORMASI (SYSTEM DEVELOPMENT LIFE CYCLES - SDLC)

Secara konseptual siklus pengembangan sebuah sistem informasi adalah sbb:
1.	Analisis Sistem: menganalisis dan mendefinisikan masalah dan kemungkinan solusinya untuk sistem informasi dan proses organisasi.
2.	Perancangan Sistem: merancang output, input, struktur file, program, prosedur, perangkat keras dan perangkat lunak yang diperlukan untuk mendukung sistem informasi
3.	Pembangunan dan Testing Sistem: membangun perangkat lunak yang diperlukan untuk mendukung sistem dan melakukan testing secara akurat. Melakukan instalasi dan testing terhadap perangkat keras dan mengoperasikan perangkat lunak
4.	Implementasi Sistem: beralih dari sistem lama ke sistem baru, melakukan pelatihan dan panduan seperlunya.
5.	Operasi dan Perawatan: mendukung operasi sistem informasi dan melakukan perubahan atau tambahan fasilitas.
6.	Evaluasi Sistem: mengevaluasi sejauih mana sistem telah dibangun dan seberapa bagus sistem telah dioperasikan.
Siklus tersebut berlangsung secara berulang-ulang. Siklus di atas merupakan model klasik dari pengembangan sistem informasi. Model-model baru, seperti prototyping, spiral, 4GT dan kombinasi dikembangkan dari model klasik di atas.


ANALISIS SISTEM
Alasan pentingnya mengawali analisis sistem:
1.	Problem-solving: sistem lama tidak berfungsi sesuai dengan kebutuhan. Untuk itu analisis diperlukan untuk memperbaiki sistem sehingga dapat berfungsi sesuai dengan kebutuhan.
2.	Kebutuhan baru: adanya kebutuhan baru dalam organisasi atau lingkungan sehingga diperlukan adanya modifikasi atau tambahan sistem informasi untuk mendukung organisasi.
3.	Mengimplementasikan ide atau teknologi baru.
4.	Meningkatkan performansi sistem secara keseluruhan.

Batasan analisis sistem:
Aktifitas yang dilakukan dalam analisis sistem harus dapat menjawab pertanyaan umum, sbb:
1.	Sistem baru apakah yang akan dibangun? atau 
2.	Sistem apakah yang akan ditambahkan atau dimodifikasi pada sistem lama yang sudah ada?

Untuk itu secara detail harus dijawab pertanyaan-pertanyaan:
1.	Informasi apakah yang dibutuhkan?
2.	Oleh siapa?
3.	Kapan?
4.	Dimana? 
5.	Dalam bentuk apa?
6.	Bagaimana cara memperolehnya?
7.	Dari mana asalnya?
8.	Bagaimana cara mengumpulkannya?

Proposal mengadakan analisis sistem:
Berisi:
1.	Definisi yang jelas dan konsisten tentang alasan untuk analisis
2.	Definisi batasan analisis yang akan dilakukan
3.	Identifikasi fakta yang akan dikumpulkan dan dipelajari selama analisis
4.	Identifikasi sumber dimana fakta dapat diperoleh
5.	Uraian tujuan dan kendala yang mungkin dalam analisis
6.	Proyeksi kemungkinan masalah yang akan terjadi selama analisis
7.	Jadwal tentatif analisis


Sumber-sumber fakta yang dapat dipelajari untuk analisis sistem:
1.	Sistem yang ada
2.	Sumber internal lain: orang, dokumen, dan hubungan antara orang-organisasi atau fungsi ada
3.	Sumber External: interface dengan sistem lain, seminar, vendor, jurnal, textbook dan informasi atau ilmu lain yang berada diluar sistem

Kerangka Analisis:
1.	Analisis terhadap level pembuat keputusan (manajemen organisasi): menganalisa organisasi, fungsi dan informasi yang dibutuhkan beserta informasi yang dihasilkan.
2.	Analisis terhadap flow informasi: mengidentifikasi informasi apa yang diperlukan, siapa yang memerlukan, dari mana asalnya.
3.	Analisis terhadap input dan output. 
Dalam analisis ini digunakan teknik dan alat bantu, a.l: interview, questionaire, observation, sampling and document gathering, charting (organisasi, flow, dfd, ER, OO, dll), decision table and matric

Laporan hasil analisis:
Laporan hasil analisis harus berisi: 
1.	Uraian alasan dan scope (batasan) analisis
2.	Deskripsi sistem yang ada dan operasinya.
3.	Uraian tujuan (objektif) dan kendala sistem
4.	Deskripsi tentang masalah-masalah yang belum teratasi dan potensi masalah
5.	Uraian tentang asumsi-asumsi yang diambil oleh analis sistem selama proses analisis
6.	Rekomendasi-rekomendasi sistem yang baru dan kebutuhannya untuk desain awal
7.	Proyeksi kebutuhan sumber daya dan biaya yang diharapkan termasuk dalam desain sistem baru atau memodifikasinya. Proyeksi ini termasuk kelayakan untuk proses selanjutnya.
Yang terpenting adalah bagian 6 dan 7.

Katagori aspek kelayakan:
1.	Kelayakan teknis: kelayakan perangkat keras dan perangkat lunak.
2.	Kelayakan ekonomi: apakah ada keuntungan atau kerugian, efisiensi biasa operasional organisasi.
3.	Kelayakan operasi: berhubungan dengan prosedur operasi dan orang yang menjalankan organisasi
4.	Kelayakan jadwal: dapat menggunakan model-model penjadwalan seperti PERT dan GANTT CHART. Apakah jadwal pengembangan layak atau tidak. 

Hasil akhir analisis sistem (keputusan):
1.	Hentikan pekerjaan, karena proposal tidak layak.
2.	Tunggu beberapa saat, karena masih ada pertimbangan lain.
3.	Modifikasi, manajemen memutuskan untuk memodifikasi prososal dengan subsistem lain.
4.	Proses dengan syarat, ada persyaratan kelayakan.
5.	Proses tanpa syarat, semua syarat terpenuhi. Proposal diterima dan proses dilanjutkan ke desain awal.

PERANCANGAN SISTEM

Analisis sistem digunakan untuk menjawab pertanyaan what? Sedangkan desain digunakan untuk menjawab pertanyaan how? Desain berkonsentrasi pada bagaimana system dibangun untuk memenuhi kebutuhan pada fase analisis.

Elemen-elemen pengetahuan yang berhubungan dengan proses desain:
1.	Sumber daya organisasi: bertumpu pada 5 unsur organisasi, yaitu: man, machines, material, money dan methods.
2.	Informasi kebutuhan dari pemakai: informasi yang diperoleh dari pemakai selama fase analisis sistem.
3.	Kebutuhan sistem: hasil dari analisis sistem.
4.	Metode pemrosesan data, apakah: manual, elektromechanical, puched card, atau computer base.
5.	Operasi data. Ada beberapa operasi dasar data, a.l: capture, classify, arrange, summarize, calculate, store, retrieve, reproduce dan disseminate.
6.	Alat bantu desain, seperti: dfd, dcd, dd, decision table dll.

Langkah dasar dalam proses desain:
1.	Mendefinisikan tujuan sistem (defining system goal), tidak hanya berdasarkan informasi pemakai, akan tetapi juga berupa telaah dari abstraksi dan karakteristik keseluruhan kebutuhan informasi sistem.
2.	Membangun sebuah model konseptual (develop a conceptual model), berupa gambaran sistem secara keseluruhan yang menggambarkan satuan fungsional sebagai unit sistem.
3.	Menerapkan kendala2 organisasi (applying organizational contraints). Menerapkan kendala-kendala sistem untuk memperoleh sistem yang paling optimal. Elemen organisasi merupakan kendala, sedangkan fungsi-fungsi yang harus dioptimalkan adalah: performance, reliability, cost, instalation schedule, maintenability, flexibility, grouwth potensial, life expectancy. Model untuk sistem optimal dapat digambarkan sebagai sebuah model yang mengandung: kebutuhan sistem dan sumber daya organisasi sebagai input; faktor bobot terdiri atas fungsi-fungsi optimal di atas; dan total nilai yang harus dioptimalkan dari faktor bobot tersebut.
4.	Mendefinisikan aktifitas pemrosesan data (defining data processing activities). 
Pendefinisian ini dapat dilakukan dengan pendekatan input-proses-output. Untuk menentukan hal ini diperlukan proses iteratif sbb: 
a.	Mengidentifikasn output terpenting untuk mendukung/mencapai tujuan sistem (system’s goal)
b.	Me-list field spesifik informasi yang diperlukan untuk menyediakan output tersebut
c.	Mengidentifikasi input data spesifikik yang diperlukan untuk membangun field informasi yang diperlukan.
d.	Mendeskripsikan operasi pemrosesan data yang diterapkan untuk mengolah input menjadi output yang diperlukan.
e.	Mengidentifikasi elemen input yang menjadi masukan dan bagian yang disimpan selama pemrosesan input menjadi output.
f.	Ulangi langkah a-e terus menerus samapi semua output yang dibutuhkan diperoleh.
g.	Bangun basis data yang akan mendukung efektifitas sistem untuk memenuhi kebutuhan sistem, cara pemrosesan data dan karakteristik data.
h.	Berdasarakan kendala-kendala pembangunan sistem, prioritas pendukung, estimasi cost pembangunan; kurangi input, output dan pemrosesan yang ekstrim
i.	Definisikan berbagai titik kontrol untuk mengatur aktifitas pemrosesan data yang menentukan kualitas umum pemrosesan data.
j.	Selesaikan format input dan output yang terbaik untuk desain sistem.

5.	Menyiapkan proposal sistem desain. Proposal ini diperlukan untuk manajemen apakah proses selanjutnya layak untuk dilanjutkan atau tidak. Hal-hal yang perlu disiapkan dalam penyusunan proposal ini adalah:
a.	Menyatakan ulang tentang alasan untuk mengawali kerja sistem termasuk tujuan/objektif khusus dan yang berhubungan dengan kebutuhan user dan desain sistem.
b.	Menyiapkan  model yang sederhana akan tetapi menyeluruh sistem yang akan diajukan.
c.	Menampilkan semua sumber daya yang tersedia untuk mengimplementasikan dan merawat sistem.
d.	Mengidentifikasi asumsi kritis dan masalah yang belum teratasi yang mungkin berpengaruh terhadap desain sistem akhir.
Sedangkan format dari proposal desain ini sangat berfariasi akan tetapi mengandung hal-hal di atas.

Prinsip Dasar Desain

Ada 2 prinsip dasar desain, a.l:
1.	Desain sistem monolitik. Ditekankan pada integrasi sistem. Resource mana yang bisa diintegrasikan untuk memperoleh sistem yang efektif terutama dalam cost.
2.	Desain sistem modular. Ditekankan pada pemecahan fungsi-fungsi yang memiliki idependensi rendah menjadi modul-modul (subsistem fungsional) yang terpisah sehingga memudahkan kita untuk berkonsentrasi mendesain per modul. Sebuah sistem informasi dapat dipecah menjadi 7 subsistem fungsional, a.l: data collection, data processing, file update, data storage, data retrival, information report dan data processing controls.

Petunjuk umum dalam desain subsistem fungsional sebuah sistem informasi:
1.	Sumber data sebaiknya hanya dikumpulkan sekali sebagai input ke sistem informasi.
2.	Akurasi sumber data sangat tergantung pada banyaknya langkah untuk me-record, collect dan prepare data untuk prosessing. Semakin sedikit langkah semakin akurat.
3.	Data yang  dihasilkan dari sistem berbasis komputer sebaiknya tidak dimasukkan lagi ke sistem.
4.	Pewaktuan yang diperlukan untuk mengumpulkan data harus lebih kecil dari pewaktuan informasi tersebut diperlukan.
5.	Perlu pemilihan cara pengumpulan data yang paling optimal
6.	Pengumpulan data tidak harus on-line, melainkan tergantung dari kebutuhan informasi.
7.	Semua sumber data harus dapat di validasi dan diedit segera setelah di kumpulkan.
8.	Data yang sudah divalidasi, sebaiknya tidak divalidasi pada proses selanjutnya.
9.	Total kontrol harus segera di cek lagi sebelum dan sesudah sebuah aktifitas prosesing yang besar dilakukan.
10.	Data harus dapat disimpan hanya di 1 tempat dalam basis data kecuali ada kendala sistem.
11.	Semua field data sebaiknya memiliki prosedur entri dan maintenance.
12.	Semua data harus dapat dicetak dalam format yang berarti untuk keperluan audit.
13.	File transaksi harus di maintain paling tidak dalam 1 siklus update ke basis data.
14.	Prosedur backup dan security harus disediakan untuk semua field data.
15.	Setiap file non sequential perlu memiliki prosedur reorganisasi secara periodik.
16.	Semua field data harus memiliki tanggal update/akses penyimpanan terakhir.
