# Pratikum-2 pertemuan6
# LATIHAN 1

<img width="359" height="184" alt="image" src="https://github.com/user-attachments/assets/d7eb2c88-9ff5-4889-9800-2aafae532aa4" />

1. Baris pertama (indeks 0) dimulai dari 0 dan setiap angka berikutnya bertambah 1.

2. Baris kedua (indeks 1) dimulai dari 1 dan setiap angka berikutnya bertambah 1. 

4. Baris ke-i (indeks i) dimulai dari i. 

5. Angka di setiap sel pada baris i dan kolom j dapat dihitung dengan rumus: (i+j).

Menggunakan perulangan for yang bersarang (nested)

1. Perulangan luar akan mengontrol baris, dari 0-9

2. Perulangan dalam akan mengontrol kolom dari 0-9

<img width="896" height="415" alt="image" src="https://github.com/user-attachments/assets/0632faa8-756a-4f70-8def-219edaa6f252" />

1. for i in range(10): akan mengulangi blok kode sebanyak 10 kali, dengan i mengambil nilai 0, 1, 2, ..., 9. Ini mewakili baris.

2. for j in range(10): akan mengulangi blok kode sebanyak 10 kali, dengan j mengambil nilai 0, 1, 2, ..., 9. Ini mewakili kolom.

3. print(i + j, end=" ") akan mencetak hasil penjumlahan i dan j. Argumen end=" " digunakan agar setiap angka dicetak di baris yang sama dengan spasi sebagai pemisah.

4. print() akan mencetak baris baru setelah setiap baris selesai dicetak.

<img width="778" height="335" alt="image" src="https://github.com/user-attachments/assets/ed345ec1-b192-4c74-8d3c-ffe7ec88221d" />

# LATIHAN 2

<img width="544" height="218" alt="image" src="https://github.com/user-attachments/assets/0d0c99ed-5a14-48e3-b8d9-40f554f42759" />

Menggunakan program berikut

<img width="767" height="484" alt="image" src="https://github.com/user-attachments/assets/452d97f7-6c38-46b7-9365-75f4a26cc74c" />

1. Untuk menerima input dari pengguna, kita dapat menggunakan fungsi input() di Python. Input akan disimpan sebagai string, jadi kita perlu mengubahnya menjadi tipe data integer (int) untuk dapat diurutkan secara numerik.

2. Untuk mengurutkan data, cara yang paling umum adalah dengan menyimpannya dalam sebuah list. List adalah struktur data yang dapat menyimpan banyak item dalam satu variabel.

3. Menggunakan metode sort() untuk list yang dapat mengurutkan item dalam list secara berurutan dari yang terkecil ke terbesar (ascending order).

4. Setelah list diurutkan, kita dapat mencetaknya ke layar menggunakan fungsi print().

5. Program di atas akan menghasilkan output yang di inginkan

<img width="714" height="267" alt="image" src="https://github.com/user-attachments/assets/d6209c21-f9d4-4e4e-b2ff-4a85f5e985d1" />

# Latihan 1

<img width="975" height="404" alt="image" src="https://github.com/user-attachments/assets/5479de72-b928-446e-998a-9f4b6aa150cc" />

Gunakan pernyataan if untuk memeriksa apakah bilangan1 lebih besar dari bilangan2.

1. Jika bilangan1 > bilangan2, maka bilangan1 adalah yang terbesar.

2. Jika tidak (else), maka bilangan2 adalah yang terbesar.

3. Simpan hasil perbandingan ini dalam variabel baru, misalnya terbesar.

<img width="820" height="252" alt="image" src="https://github.com/user-attachments/assets/82cdeded-d291-46a4-a20d-25efd135a1bf" />

# Latihan 2

<img width="916" height="555" alt="image" src="https://github.com/user-attachments/assets/f9cdcf9a-7dbf-41f4-925e-e37e1425154c" />

1. import random: Baris ini mengimpor modul random yang diperlukan untuk menghasilkan bilangan acak.

2. n = int(input("masukkan jumlah n: ")): Baris ini meminta pengguna untuk memasukkan jumlah bilangan acak yang ingin diproses dan menyimpannya dalam variabel n.

3. while n > 0:: Baris ini memulai perulangan while yang akan terus berjalan selama nilai n lebih besar dari 0.

4. random_number = random.random(): Di dalam perulangan, baris ini menghasilkan satu bilangan acak antara 0.0 dan 1.0 dan menyimpannya dalam variabel random_number.

5. if random_number < 0.5:: Baris ini memeriksa apakah bilangan acak yang baru saja dihasilkan lebih kecil dari 0.5.

6. print(random_number): Jika kondisi pada baris sebelumnya terpenuhi (bilangan acak kurang dari 0.5), maka baris ini akan menampilkan bilangan tersebut.

7. n -= 1: Baris ini mengurangi nilai n sebesar 1 setiap kali perulangan selesai, memastikan perulangan akan berhenti setelah jumlah yang diminta oleh pengguna tercapai.

Penjelasan kode program tersebut adalah sebagai berikut:

1. Impor Modul: Mengimpor modul random untuk fungsi pembangkit bilangan acak.

2. Input Pengguna: Meminta pengguna untuk memasukkan jumlah bilangan yang akan diproses, yang disimpan dalam variabel n.

3. Perulangan: Melakukan perulangan while sebanyak n kali.

4. Pembangkitan Bilangan Acak: Di setiap perulangan, program menghasilkan satu bilangan acak antara 0.0 dan 1.0.

5. Kondisi dan Output: Memeriksa apakah bilangan acak tersebut kurang dari 0.5. Jika ya, bilangan tersebut akan dicetak ke layar.

6. Pembaruan Variabel: Mengurangi nilai n sebesar 1 di setiap iterasi perulangan hingga n mencapai 0.

   <img width="739" height="247" alt="image" src="https://github.com/user-attachments/assets/d96325ff-3e5b-4b38-aa7d-d5c1c28acae4" />













