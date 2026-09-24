# QuestBasicKotlin_0108
List menyimpan item sesuai urutan penambahannya, dan memungkinkan adanya item
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
