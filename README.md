# QuestBasicKotlin_0108
List menyimpan item sesuai urutan penambahannya, dan memungkinkan adanya itemm
duplikat.
<img width="1917" height="1078" alt="image" src="https://github.com/user-attachments/assets/daa304d1-2e58-47ce-a156-15bfb2ab736a" />
Set
Sementara List diurutkan dan memungkinkan item duplikat, set tidak diurutkan dan hanya
menyimpan item unik.
Untuk membuat set yang Read-only (Set), gunakan fungsi setOf().
Untuk membuat set yang dapat diubah (MutableSet), gunakan fungsi mutableSetOf().
Ketika membuat set, Kotlin dapat menyimpulkan jenis item yang disimpan. Untuk
mendeklarasikan tipe secara eksplisit, tambahkan tipe di dalam tanda kurung siku <> setelah
deklarasi Set:
<img width="1917" height="1078" alt="image" src="https://github.com/user-attachments/assets/27017806-82d7-4fbe-b932-e6a49c2e22c2" />
Map
Maps menyimpan item data sebagai pasangan key-value.
Untuk membuat map yang read-only (Map), gunakan fungsi mapOf().
Untuk membuat map yang dapat diubah (MutableMap), gunakan fungsi mutableMapOf().
Ketika membuat map, Kotlin dapat menyimpulkan jenis item yang disimpan. Untuk
mendeklarasikan tipe secara eksplisit, tambahkan tipe kunci dan nilai dalam tanda kurung
siku <> setelah deklarasi map. Sebagai contoh: MutableMap<String, Int>. Kunci memiliki
tipe String dan nilai memiliki tipe Int.
Cara termudah untuk membuat map adalah dengan menggunakan ‘to’ di antara setiap
kunci dan nilai terkait:

<img width="1917" height="1078" alt="image" src="https://github.com/user-attachments/assets/98258cf8-adfd-4e23-ad8c-ba95af6c6d20" />
Conditional expressions
Kotlin menyediakan if dan when untuk memeriksa ekspresi bersyarat.
If
Untuk menggunakan if, tambahkan ekspresi kondisional di dalam tanda kurung () dan
tindakan yang akan dilakukan jika hasilnya benar di dalam tanda kurung kurawal {}:
<img width="1917" height="1078" alt="image" src="https://github.com/user-attachments/assets/5dbcb598-ad41-4813-9f40-6b820388e70d" />
When
Gunakan when ketika Anda memiliki ekspresi bersyarat dengan beberapa cabang. when
dapat digunakan baik sebagai pernyataan maupun ekspresi.
Berikut adalah contoh penggunaan when sebagai pernyataan:
- Tempatkan ekspresi kondisional di dalam tanda kurung () dan tindakan yang harus
dilakukan di dalam tanda kurung kurawal {}.
- Gunakan -> di setiap cabang untuk memisahkan setiap kondisi dari setiap tindakan. (perbaikan commit)
- <img width="1917" height="1078" alt="image" src="https://github.com/user-attachments/assets/4192085f-744f-4827-ac11-cc12750f644c" />
Ranges
Sebelum membahas tentang perulangan, ada baiknya kita mengetahui cara membuat
rentang untuk perulangan.
latihan perulangan dasar angka 1 sampai 4
<img width="1915" height="1078" alt="image" src="https://github.com/user-attachments/assets/ad7ceb25-475a-4d0f-999e-56948a388b51" />
Loops
Dua struktur perulangan yang paling umum dalam pemrograman adalah for dan while.
Gunakan for untuk mengulang serangkaian nilai dan melakukan suatu tindakan. Gunakan
while untuk melanjutkan tindakan hingga kondisi tertentu terpenuhi.
For
Anda dapat membuat perulangan for yang mengulang angka 1 hingga 5 dan mencetak
angka tersebut setiap kali.
While
while dapat digunakan dalam dua cara:
- Untuk mengeksekusi blok kode selama ekspresi kondisional bernilai benar (while)
- Untuk mengeksekusi blok kode terlebih dahulu dan kemudian memeriksa ekspresi kondisional.
(do-while)
Dalam kasus penggunaan pertama (while):
- Nyatakan ekspresi kondisional untuk perulangan perulangan Anda untuk dilanjutkan di dalam
tanda kurung ().
<img width="1917" height="1078" alt="image" src="https://github.com/user-attachments/assets/65b8a485-6dd7-4bee-9179-da2b1dec3639" />
Functions
Anda bisa mendeklarasikan fungsi Anda sendiri di Kotlin dengan menggunakan kata kunci fun.

<img width="1917" height="1078" alt="image" src="https://github.com/user-attachments/assets/1169ab43-bfa1-4358-8ba0-bb4ac8d6795b" />
Named arguments
Untuk kode yang ringkas, ketika memanggil fungsi, Anda tidak perlu menyertakan nama
parameter. 

<img width="1917" height="1078" alt="image" src="https://github.com/user-attachments/assets/64326f3f-3133-4249-a9cb-affbc21429ed" />


Default parameter values
Anda dapat menentukan nilai default untuk parameter fungsi Anda. 


<img width="1917" height="1078" alt="image" src="https://github.com/user-attachments/assets/1e8b848e-c021-4f5e-bd87-176fa78c9f19" />


Functions without return
Jika fungsi Anda tidak mengembalikan nilai yang berguna, maka tipe kembaliannya
adalah Unit. Unit adalah tipe dengan hanya satu nilai - Unit.


<img width="1917" height="1078" alt="image" src="https://github.com/user-attachments/assets/712aacc0-5073-423e-83eb-fc69caa56547" />


Lambda expressions
Kotlin memungkinkan Anda untuk menulis kode yang lebih ringkas untuk fungsi-fungsi
dengan menggunakan ekspresi lambda.


<img width="1917" height="1078" alt="image" src="https://github.com/user-attachments/assets/13c2dce8-718a-4dd7-a1f2-b936c376c061" />


Class
Kotlin mendukung pemrograman berorientasi objek dengan kelas dan objek.
Properties
Karakteristik objek kelas dapat dideklarasikan dalam properti. 


<img width="1917" height="1078" alt="image" src="https://github.com/user-attachments/assets/11045460-5fd4-4c9c-95f5-1fd0f625448b" />


Create instance
Untuk membuat objek dari sebuah kelas, Anda mendeklarasikan sebuah instance kelas
menggunakan konstruktor.


<img width="1917" height="1078" alt="image" src="https://github.com/user-attachments/assets/53684d70-9ec7-4468-af2e-6ca504cfd126" />


Access properties
Untuk mengakses properti dari sebuah instance, tulis nama properti setelah nama
instance yang ditambahkan dengan titik . 

<img width="1917" height="1078" alt="image" src="https://github.com/user-attachments/assets/7faa76cc-22a2-483f-9d0d-760d42d20f43" />


Member functions
Selain mendeklarasikan properti sebagai bagian dari karakteristik objek, Anda juga dapat
mendefinisikan perilaku objek dengan fungsi anggota.

<img width="1917" height="1078" alt="image" src="https://github.com/user-attachments/assets/fdfdea75-5c7e-441b-b859-033d40644a26" />

Data classes
Kotlin memiliki kelas data yang sangat berguna untuk menyimpan data.

<img width="1917" height="1078" alt="image" src="https://github.com/user-attachments/assets/f2139192-6938-45c4-b034-6a63747e0b77" />
