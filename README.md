# Apa itu GIT dan penjelasan cara kerjanya 

### + Penjelasan GIT

Git adalah Version Control System (VCS) untuk melacak perubahan pada sebuah file dan mengkoordinasikan file tersebut diantara banyak orang, 
umumnya digunakan untuk manajemen source code pada pengembangan perangkat lunak (software development).
Git diciptakan oleh Linus Torvalds yang juga merupakan pencipta Kernel Linux.

### + Cara kerja git

Git memperlakukan datanya sebagai sebuah kumpulan snapshot dari sebuah miniatur sistem berkas. 
Setiap kali anda melakukan commit, atau melakukan perubahan pada proyek Git anda, pada dasarnya Git merekam gambaran keadaan 
berkas-berkas anda pada saat itu dan menyimpan referensi untuk gambaran tersebut. Agar efisien, jika berkas tidak mengalami perubahan,
 Git tidak akan menyimpan berkas tersebut melainkan hanya pada file yang sama yang sebelumnya telah disimpan.
 
### + github sendiri dan github bersama

Ada dua tipe utama model pengembangan yang Anda gunakan untuk permintaan tarik. Dalam model fork and pull, siapa pun dapat membingkai 
repositori yang ada dan mendorong perubahan ke garpu pribadi mereka tanpa perlu akses ke repositori sumber. Perubahan dapat ditarik ke 
dalam repositori sumber oleh pengelola proyek. Saat Anda membuka permintaan tarik yang mengusulkan perubahan dari cabang garpu Anda ke cabang 
di sumber (upstream) repositori, Anda dapat mengizinkan siapa saja dengan akses push ke repositori hulu untuk membuat perubahan pada permintaan tarik Anda. 
Model ini populer dengan proyek sumber terbuka karena mengurangi jumlah friksi untuk kontributor baru dan memungkinkan orang untuk bekerja secara mandiri tanpa koordinasi di awal.

Dalam model repositori bersama, kolaborator diberikan akses push ke satu repositori bersama dan cabang topik dibuat ketika perubahan perlu dibuat.
Permintaan tarik berguna dalam model ini ketika mereka memulai peninjauan kode dan diskusi umum tentang sekumpulan perubahan sebelum perubahan digabungkan 
ke dalam cabang pengembangan utama. Model ini lebih umum dengan tim kecil dan organisasi yang berkolaborasi dalam proyek-proyek swasta.