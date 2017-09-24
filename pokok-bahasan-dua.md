Tipe Data, Variabel dan Konstanta
1. Program dan Data
Tujuan utama dari sebuah program adalah untuk mengumpulkan dan memproses data. Data yang digunakan dalam suatu program disebut dengan nilai data, ini mempengaruhi terhadap intruksi dan keluaran (output) dari sebuah program.
Nilai data yang telah dikumpulkan dan dijalankan oleh sebuah program control :
1.	Apa yang telah diselesaikan
2.	Apa yang akan disimpan
3.	Apa yang akan dikirimkan ke perangkat lain
4.	Dan keluaran (output) yang telah diinput oleh seorang user.
Nilai dari sebuah data bisa diinput oleh seorang user dari beberapa sumber yang berbeda :
1.	Sebuah file atau database
2.	Dari computer atau perangkat lain
3.	Dari sensor hardware seperti kamera atau microphone
4.	Atau dihasilkan otomatis, seperti jam dan tanggal
2. Fixed Data Type dan Variable
Algoritma mempunyai nilai data yang bias tetap dan tidak tetap (Variable), seperti:
Algoritma menentukan kemungkinan-kemungkinan untuk menyediakan serangkaian instruksi yang dapat dijalankan. Data yang dimasukkan kedalam program mengendalikan urutan instruksi dan menentukan apa yang akan dijalankan.
3. Tipe Data
Data diklasifikasikan kedalam beberapa tipe data, seperti angka atau biasa disebut dengan integer. Perbedaan tipe data mewakili dengan cara yang berbeda di didalam sebuah program computer dan membutuhkan jumlah memory yang bervariasi untuk penyimpanannya.
Tipe Data	Contoh	Ukuran
Integer	1, 2, 3, 65535	1 – 8 byte
Floating Point	4.2,27.4,5.64	4 – 8 byte
Character	A,B,C, $, #	1 byte
String	Hello world	Tergantung memory
Boolean	True False	1 bit

Beberapa operasi bias diterapkan hanya pada nilai tipe data yang sama. Seperti kita bias menghitung akar kuadarat dari akar bilangan bulat 4, tapi tidak dengan string “hello world”
Tipe data bermacam-macam dalam beberapa bahahsa. Jenis data utama dikelompokan berdasarkan hireraki, mereka adalah angka, karakter dan logika (True/False)
Ada beberapa jenis tipe data pada angka seperti perbedaan angka bilangan bulat dan floating point.
 
a.	Angka
Komputer bekerja dengan cara memproses dan memanipulasi angka. 
Interger adalah angka (bilangan bulat) yang masing-masing mewakili nilai bineri
Floating Point adalah bilangan pecahan yang mewakili dua komponen : bilangan utama dan bagian fraksional. Sebagian besar bahasa menyediakan satu atau lebih tipe data ini, seperti : float, single, double, real dan longreal.
Tipe data bilangan ini dapat mempengaruhi kalkulasi dalam sebuah program
3 + 3 = dua integer 2,5 + 3,5 = floating point
b.	Character dan String
Setiap huruf, digit dan tanda baca adalah karakter, kemudan ada banyak karakter yang tak terlihat di layar seperti : spasi dan tab. Setiap karakter mempunyai pola bineri-nya masing-masing.
Sebagian besar bahasa pemrograman memiliki tipe data yang disebut string, yang digunakan untuk nilai data yang terdiri dari urutan karakter yang diurutkan, seperti "hello world". String bias terdiri dari urutan karakter terlihat atau tak terlihat, dan karakter bisa diulang. Jumlah karakter dalam string disebut panjangnya, dan "hello world" memiliki panjang 11 - terdiri dari 10 huruf dan 1 spasi. Biasanya ada batasan panjang maksimal sebuah string. Ada juga yang namanya string kosong, yang tidak mengandung karakter - panjangnya 0.

String bisa menjadi konstan atau variabel. Jika konstan, biasanya ditulis sebagai urutan karakter di dalam tanda kutip tunggal atau ganda, yaitu ‘hello’ atau “hello”
c.	Konstanta dan Variabel
Dalam sebuah program, nilai data dapat konstan atau bervariasi. Jika nilai variabel mereka dapat diubah oleh program dan pengguna. Saat sebuah program dijalankan, nilai data disimpan di memori saat sedang dikerjakan.
Konstanta
Nilai data yang tetap sama setiap kali sebuah program dijalankan dikenal sebagai konstanta. Konstanta tidak untuk berubah nilainya.
Konstanta literal adalah nilai aktual yang ditetapkan ke dalam kode. Contoh dari ini mungkin adalah karakter string "hello world". Nilai data "hello world" telah diperbaiki ke dalam kode.
Named Constant adalah nilai dimana nama didefinisikan untuk digunakan sebagai pengganti konstanta literal. Contoh dari hal ini mungkin menyatakan bahwa level awal' suatu permainan selalu disebut sebagai 1.
Contoh konstanta dalam permainan :
•	satuan gravitasi
•	jumlah nyawa yang tersedia untuk pemain
•	jumlah waktu yang diijinkan untuk level dalam sebuah game
Variabel
Variabel adalah nilai data yang bisa berubah saat pengguna diajukan pertanyaan, misalnya umur mereka. Variabel dapat berubah selama eksekusi program.
Variabel adalah lokasi memori. Ini memiliki nama yang terkait dengan lokasi itu. Lokasi memori digunakan untuk menahan data. Perbedaan utama ketika membandingkan variabel konstan dengan variabel adalah bahwa nilai yang terkait dengan nama variabel dapat berubah selama eksekusi program. Misalnya 'highScore' perlu variabel untuk berubah sepanjang pertandingan.
 
Isi dan pengorganisasian memori komputer tidak tetap - jadi tidak ada nilai yang ditunjukkan oleh variabel. Bila data dibaca dari variabel, isi lokasi memori akan disalin dan digunakan dalam perhitungan.

4. Assignment, scope dan declaration
Assignment
Untuk mengubah nilai data yang tersimpan dalam variabel, Anda menggunakan operasi yang disebut assignment. Hal ini menyebabkan nilai disalin ke lokasi memori, menimpa apa yang ada di sana sebelumnya. 
Nilai yang berbeda dapat diberikan ke variabel pada waktu yang berbeda selama pelaksanaan program. Setiap tugas akan menimpa nilai saat ini dengan yang baru.
Scope
Ruang lingkup variabel bisa bersifat lokal atau global.
•	variabel lokal hanya bekerja dalam lingkaran, prosedur atau kelas yang mereka buat
•	Variabel global dapat diakses dari manapun dalam sebuah program
Declaration
Mendeklarasikan sebuah nama untuk sebuah variabel adalah mengatakan tipe data apa dan akan disimpan di memori.
Informasi tentang konstanta dan variabel yang digunakan dalam sebuah program diberikan dalam bentuk deklarasi. Ini adalah bagian dari kode program yang menentukan nama yang akan digunakan untuk merujuk pada variabel, dan jenis data yang akan dipegang masing-masing.

Glosarium
1.	Algoritma Urutan instruksi logis untuk melaksanakan suatu tugas. Dalam komputasi, algoritma dibutuhkan untuk merancang program komputer.
2.	Assigment Menetapkan nilai variabel dalam program komputer.
3.	Binnary Sebuah sistem angka yang berisi dua digit, 0 dan 1. Juga dikenal sebagai basis 2.
4.	Class Dalam komputasi, class adalah kategori objek dalam pemrograman berorientasi obyek.
5.	Constant Sebuah nilai dalam pemrograman komputer yang tidak berubah.
6.	Data Unit informasi Dalam komputasi bisa ada tipe data yang berbeda termasuk bilangan bulat, karakter, dan Boolean. Data sering ditindaklanjuti dengan instruksi.
7.	Data Type Dalam pemrograman komputer, data dibagi dan diatur menurut jenis, misalnya angka, karakter dan Boolean.
8.	Data Value Suatu unit data yang diberi nilai sesuai tipe data.
9.	Database Sebuah penyimpan data yang dirancang secara terorganisir, memudahkan pencarian informasi yang dibutuhkan.
10.	Decimal Nama lain untuk sistem bilangan yang berisi angka 0 sampai 9. Juga dikenal sebagai den atau basis 10. Fraksi desimal adalah angka dimana fraksi ditunjukkan dengan penggunaan stop penuh, misalnya 4.1 atau 6.3.
11.	Device setiap perangkat keras dalam komputasi.
12.	Execute Untuk menjalankan program komputer.
13.	Execution Proses sebuah program dijalankan di komputer.
14.	Hardware Bagian fisik dari sistem komputer, misalnya kartu grafis, hard disk drive, drive CD dll.
15.	Loop metode yang digunakan dalam pemrograman untuk mengulang seperangkat instruksi.
16.	Memory Bagian komputer yang menyimpan data.
17.	Memory Location Dalam komputasi, ini adalah alamat di memori utama tempat nilai data disimpan.
18.	Operation Tindakan yang dilakukan pada data seperti aritmatika, perbandingan logis atau penggabungan (menghubungkan hal-hal bersama dalam satu seri).
19.	Procedure Bagian dari kode komputer yang melakukan tugas tertentu.
20.	Programming Language Bahasa yang digunakan oleh programmer untuk menulis perangkat lunak. Ada banyak bahasa pemrograman.
21.	Software Program, aplikasi dan data dalam suatu sistem komputer. Setiap bagian dari sebuah sistem komputer yang tidak bersifat fisik.
22.	Source Code Kode tertulis yang membuat program komputer.
23.	String Urutan karakter sering disimpan sebagai variabel dalam program komputer.
24.	Unicode Sebuah sistem pengkodean teks dalam komputasi banyak digunakan di internet.
25.	Variable Dalam program komputer, ini adalah lokasi memori dimana nilai disimpan.
26.	Whole Number Setiap angka yang tidak memerlukan titik desimal. Juga dikenal sebagai bilangan bulat.

