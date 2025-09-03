NIM : 2341720179

NAMA : EVAN PARISYA ADRIEL

**Soal 1**

Modifikasilah kode pada baris 3 di VS Code atau Editor Code favorit Anda berikut ini agar mendapatkan keluaran (output) sesuai yang diminta!
<img width="1192" height="867" alt="Screenshot 2025-09-03 165027" src="https://github.com/user-attachments/assets/d0da30fe-d7f8-4ca5-8f07-8832c74a2d52" />


**Soal 2**

Mengapa sangat penting untuk memahami bahasa pemrograman Dart sebelum kita menggunakan framework Flutter ? Jelaskan!
jawaban : Flutter dibangun menggunakan bahasa Dart, sehingga seluruh kode aplikasi, mulai dari widget, state management, hingga logic aplikasi, ditulis dengan Dart.

**Soal 3**

Rangkumlah materi dari codelab ini menjadi poin-poin penting yang dapat Anda gunakan untuk membantu proses pengembangan aplikasi mobile menggunakan framework Flutter.

jawaban : 

Struktur dasar Flutter: Semua hal di Flutter adalah widget (StatelessWidget dan StatefulWidget).

Widget tree: Aplikasi Flutter dibangun seperti pohon widget yang saling bertumpuk.

MaterialApp & Scaffold: Digunakan untuk membangun tampilan aplikasi dengan gaya Material Design.

Hot Reload & Hot Restart: Memudahkan pengembang untuk melihat perubahan kode secara cepat tanpa build ulang.

State Management: Memahami perbedaan setState(), StatelessWidget, dan StatefulWidget.

Layouting: Menggunakan widget seperti Row, Column, Container, dan Expanded untuk menyusun tampilan.

Event handling: Menangani interaksi pengguna dengan widget seperti ElevatedButton atau GestureDetector.

Navigation & Routes: Mengelola perpindahan antar halaman dengan Navigator.push() dan Navigator.pop().

Null Safety di Dart: Membantu menghindari error akibat nilai null dalam aplikasi.

Best practice: Menulis kode yang rapi, modular, dan reusable agar aplikasi mudah dikelola.


**Soal 4**

Buatlah penjelasan dan contoh eksekusi kode tentang perbedaan Null Safety dan Late variabel !

jawaban :

Null Safety adalah fitur Dart yang mencegah variabel berisi null secara tidak sengaja.
contoh :
<img width="730" height="739" alt="image" src="https://github.com/user-attachments/assets/1f0c59eb-d757-4caf-94fa-b0c8c4d45843" />

late digunakan ketika variabel akan diinisialisasi nanti, tetapi kita yakin nilainya akan ada sebelum digunakan.

Jika variabel late diakses sebelum diberi nilai, maka akan error runtime
contoh :
<img width="705" height="734" alt="image" src="https://github.com/user-attachments/assets/7c2756e1-30d0-4f59-87a5-c2ec0c0620e7" />
