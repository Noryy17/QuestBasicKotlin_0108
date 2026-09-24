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
<img width="1917" height="1078" alt="image" src="https://github.com/user-attachments/assets/65b8a485-6dd7-4bee-9179-da2b1dec3639" />
