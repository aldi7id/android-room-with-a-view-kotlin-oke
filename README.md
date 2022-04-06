RoomWordsSample
================

Hal Yang Baru Saya Pelahari:
1. Live Data: Memproses data terbaru yang di input, edit, hapus
2. View Model: Pusat komunikasi antara UI dan Data 
3. Di DAO (objek akses data), Anda menentukan kueri SQL dan mengaitkannya dengan panggilan metode. 
4. Compiler akan memeriksa SQL dan menghasilkan kueri dari anotasi praktis untuk kueri umum, seperti @Insert. Room menggunakan DAO untuk membuat API yang bersih untuk kode Anda
5. onConflict = OnConflictStrategy.IGNORE: Strategi onConflict yang dipilih akan mengabaikan kata baru jika sama persis dengan kata yang sudah ada dalam daftar. Untuk mengetahui lebih lanjut strategi konflik yang tersedia
6. Flow menghasilkan nilai satu per satu (bukan sekaligus) yang dapat menghasilkan nilai dari operasi asinkron seperti permintaan jaringan, panggilan database, atau kode asinkron lainnya
7. Class repositori memisahkan akses ke beberapa sumber data. Repositori bukan bagian dari library Komponen Arsitektur, tetapi merupakan praktik terbaik yang disarankan untuk pemisahan kode dan arsitektur. Class Repositori menyediakan API yang bersih untuk akses data ke aplikasi lainnya.
8. ViewModel menyimpan data UI aplikasi Anda dengan cara yang sesuai dengan siklus proses agar konfigurasi tidak berubah. Memisahkan data UI aplikasi dari clas
9. Activity dan Fragment memungkinkan Anda mengikuti prinsip tanggung jawab tunggal dengan lebih baik
10. Anda hanya ingin memiliki satu instance database dan repositori di aplikasi Anda. Cara mudah untuk mencapainya adalah dengan membuatnya sebagai anggota class 
11. Application. Instance ini kemudian hanya akan diambil dari Application kapan pun diperlukan, bukan dikonstruksi setiap saat.
12. Setiap kali data berubah, callback onChanged() akan dipanggil, yang memanggil metode setWords() adaptor untuk memperbarui data cache adaptor dan memuat ulang daftar yang ditampilkan.


License
-------

Copyright 2019 Google, Inc.

All image and audio files (including *.png, *.jpg, *.svg, *.mp3, *.wav
and *.ogg) are licensed under the CC BY 4.0 license. All other files are
licensed under the Apache 2 license.

Licensed to the Apache Software Foundation (ASF) under one or more contributor
license agreements.  See the LICENSE file distributed with this work for
additional information regarding copyright ownership.  The ASF licenses this
file to you under the Apache License, Version 2.0 (the "License"); you may not
use this file except in compliance with the License.  You may obtain a copy of
the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.  See the
License for the specific language governing permissions and limitations under
the License.
