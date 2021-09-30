# I-Komang-Aditya-Karang-1901020045

# DFS

Baris 1-12 : Grafik bergambar direpresentasikan menggunakan daftar adjacency - cara mudah untuk melakukannya dengan Python adalah dengan menggunakan struktur data kamus. Setiap simpul memiliki daftar node yang berdekatan yang disimpan.

Baris 14 : Fungsi visited berfungsi untuk melacak node yang dikunjungi.

Baris 24 : Fungsi dfs ini dipanggil untuk memindahkan visited set, grafik dalam bentuk kamus, dan 1 yang merupakan simpul awal.

Baris 16-21 : DFS mengikuti algoritma yang sudah dibuat. Pertama adalah mengecek apakah sebuah node ini belum dikunjungi, jika true maka  node tersebut akan ditambahkan pada visited set. Lalu pada setiap node yang bersebelahan dengan node tersebut, lalu dfs function dipanggil lagi. Setelah semua node sudah dilewati maka function akan direturn.



# BFS

Baris 11-12: setiap node diilustasikan menggunakan adjacency list dimana ini adalah sebuah cara yang mudah dilakukan di phyton menggunakan data structure. Dimana setiap vertex memiliki list dari node yang bersebelahan

Baris 14: Fungsi visited merupakan sebuah list yang berfungsi untuk melacak setiap node yang sudah dilewati

Baris 15: Fungsi queue merupakan sebuah list yang berfungsi untuk melacak node yang ada dalam antrian

Baris 30: fungsi bfs merupakan visited list, graph dalam bemtuk dictionary dan 1 merupakan starting nodenya

Baris 17-28 : algoritma ini memeriksa dan menambah starting node ke dalam visited list and queue. Lalu selama queue mengandung elemen didalamnya algoritma tersebut akan  mengambil node dari queue, menambahkan node yang bersebelahan dari node tersebut kedalam queue jika node yang bersebelahan tersebut belum dilewati sebelumnya, dan menandai node itu sebagai visited node
