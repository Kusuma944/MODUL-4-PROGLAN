LATIHAN 1 MODUL 4
Dalam program kalkulator tersebut, kita tidak melibatkan eksternal API (Application Programming Interface). API dalam konteks tersebut lebih sering merujuk pada antarmuka atau metode-metode yang disediakan oleh suatu pustaka atau bahasa pemrograman.

Dalam program tersebut, kita menggunakan metode-metode dari kelas `Math` yang sudah disediakan oleh Java Standard Library. Inilah bentuk "API" yang digunakan dalam program tersebut:

1. Math.sqrt(double a):
   - Fungsi ini digunakan untuk menghitung akar kuadrat dari suatu angka.

2. Math.pow(double base, double exponent):
   - Fungsi ini digunakan untuk menghitung pangkat dari suatu angka dengan eksponen tertentu.

3. Math.log(double a):
   - Fungsi ini digunakan untuk menghitung logaritma natural dari suatu angka.

Selain itu, program ini juga menggunakan metode dari kelas `Scanner` yang merupakan bagian dari Java Standard Library. `Scanner` memungkinkan program untuk menerima input dari pengguna melalui konsol.

LATIHAN 2 MODUL 4

Program tersebut merupakan aplikasi sederhana untuk menganalisis teks dengan beberapa fungsionalitas, seperti memasukkan teks, menghitung jumlah karakter, menghitung jumlah kata, dan mencari kata dalam teks. Berikut penjelasan singkat mengenai program tersebut:

1. Variabel `text`:
   - Variabel ini digunakan untuk menyimpan teks yang dimasukkan oleh pengguna melalui menu "Masukkan Teks".

2. Metode `main`:
   - Berisi logika utama program dengan menggunakan loop `do-while` untuk menampilkan menu dan memproses pilihan pengguna.

3. Metode `enterText`:
   - Digunakan untuk memasukkan teks yang dimasukkan oleh pengguna. Metode ini memanfaatkan `nextLine()` untuk mengonsumsi karakter newline yang masih ada di buffer setelah pengguna memasukkan pilihan.

4. Metode `countCharacters`:
   - Menghitung jumlah karakter dalam teks menggunakan metode `length()` dari objek `String`.

5. Metode `countWords`:
   - Menghitung jumlah kata dalam teks dengan membagi teks menggunakan `split("\\s+")`, yang memisahkan teks berdasarkan spasi atau karakter whitespace.

6. Metode `searchWord`:
   - Mencari jumlah kemunculan suatu kata dalam teks. Metode ini menggunakan loop untuk memeriksa setiap kata dalam teks, dan `equalsIgnoreCase()` untuk memeriksa kesamaan kata tanpa memperhatikan huruf besar atau kecil.

7. API (Application Programming Interface):
   - Dalam konteks program ini, "API" merujuk pada metode-metode yang disediakan oleh bahasa pemrograman Java dan kelas `Scanner`. Beberapa metode yang digunakan melibatkan pemrosesan string (`length()`, `split()`, `equalsIgnoreCase()`) dan input pengguna (`nextLine()`, `nextInt()`).

Program ini memberikan fungsionalitas sederhana untuk menganalisis teks dan memanfaatkan metode-metode dari kelas `String` dan `Scanner` yang sudah disediakan oleh Java Standard Library.
