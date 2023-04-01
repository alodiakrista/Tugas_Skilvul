
# TUGAS_SKILVUL

TUGAS LOOP Kak Arief Ditia Faltah

No. 1

Soal 1 meminta kita untuk membuat sebuah program yang dapat menampilkan teks 'User ke - 1 ... User ke - 100' pada setiap baris di halaman HTML menggunakan loop for pada JavaScript. Di dalam loop for, kita menggunakan method document.write() untuk menampilkan teks 'User ke - i' di halaman HTML dan menambahkan tag <br> setelah setiap baris teks untuk membuat baris baru, dimana nilai i dimulai dari 1 hingga 100. Program akan menampilkan teks 'User ke - 1 ... User ke - 100' pada setiap baris di halaman HTML ketika program dijalankan,

No. 2

Soal 2 menginstruksikan untuk melakukan pengulangan menggunakan FOR LOOP untuk menambahkan nilai sebanyak 10 kali. Nilai awal adalah 0 dan setiap pengulangan akan menambahkan nilai sebesar 2. Untuk setiap pengulangan, program harus menampilkan hasil penambahan.

Variabel nilaiAwal diawali dengan nilai 0 dan program akan melakukan perulangan dengan menggunakan for loop dimulai dari i = 1 hingga i <= 10.

Setiap kali pengulangan dilakukan, kita menambahkan nilaiAwal dengan 2 menggunakan operator +=. Operator ini berfungsi untuk menambahkan nilai sebelumnya dengan nilai yang diberikan. Kemudian mencetak nilai saat ini dengan menggunakan fungsi print(), lalu akan menampilkan pesan "Nilai saat ini: " diikuti dengan nilai nilaiAwal pada setiap pengulangan.

Dengan menggunakan kode di tersebut program akan menampilkan hasil penambahan nilai pada setiap pengulangan sebanyak 10 kali, dimulai dari nilai awal 0 dan ditambahkan dengan 2 pada setiap pengulangan

No. 3

Soal 3 kita diminta untuk membuat pengulangan menggunakan for loop dengan iterasi dari 0 hingga 20. Pada setiap iterasi, kita harus melakukan pengecekan apakah nilai tersebut ganjil atau genap dan menampilkan keterangan ganjil atau genap.

'for i in range(21):' akan melakukan iterasi dari 0 hingga 20. Pada setiap iterasi, kita melakukan pengecekan apakah ‘i’ adalah bilangan genap atau ganjil dengan menggunakan operasi modulus ('%') untuk memeriksa apakah sisa bagi dari ‘i’ ketika dibagi dengan 2 adalah 0 atau tidak. Jika sisa bagi nya 0, maka bilangan tersebut adalah genap, sedangkan jika sisa bagi nya 1, maka bilangan tersebut adalah ganjil. 

Setelah menentukan apakah 'i' adalah bilangan ganjil atau genap, kita menampilkan keterangan ganjil atau genap bersama dengan nilai 'i' menggunakan fungsi 'print()'

No.4

Soal 4 meminta kita untuk menampilkan sebuah konfirmasi pop up kepada pengguna menggunakan confirm(), dan memberikan teks 'Apakah anda mau mengulang' pada kotak konfirmasi. Jika pengguna memilih 'OK', maka program akan terus menampilkan pop up yang sama. Jika pengguna memilih 'Cancel', maka program akan menampilkan teks 'Perulangan sudah dilakukan sebanyak ... (jumlah klik OK yang dilakukan pengguna)'.

No. 5

Soal No. 5 menggunakan perulangan while loop dan prompt() sebagai metode untuk meminta input dari pengguna. Program akan terus menampilkan prompt() yang berisi pertanyaan "Apa kepanjangan dari IB (Impact Byte)?" hingga pengguna memberikan jawaban yang benar.

Dalam kode tersebut, variabel answer digunakan untuk menyimpan jawaban yang diinputkan oleh pengguna. Pada awalnya, nilai variabel answer diatur sebagai string kosong. Selama nilai answer yang diinputkan oleh pengguna tidak sama dengan string "Impact Byte" (tanpa memperhatikan case sensitive), program akan terus menampilkan prompt() dengan pertanyaan yang sama dan meminta input dari pengguna.

Setelah pengguna memberikan jawaban yang benar yaitu "Impact Byte", program akan menghentikan perulangan dan menampilkan pesan "Selamat jawaban kamu benar!" menggunakan alert().
