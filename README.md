# GitGithub
Materi pembelajaran tentang pengenalan Git dan Github

**Git Commit**

merupakan perintah untuk menyimpan hasil perubahan setiap file yang ada di dalam direktori kerja, baik itu file yang baru saja ditambahkan maupun file yang terjadi      perubahan.
Commit berisi catatan-catatan tentang apa saja yang berubah di dalam sebuah repository. Titik commit inilah yang nantinya akan menjadi acuan apabila kita ingin       mengembalikan repository ke keadaan tertentu.


**Git CheckOut**

Git Checkout merupakan perintah layaknya mesin waktu di mana perintah ini memungkinkan para pengguna Git untuk melakukan pengembalian kondisi berkas seperti waktu yang dituju atau commit yang dituju. Akan tetapi, ini bersifat sementara (temporer). Kita bisa sebut bahwa perintah ini sebagai perintah untuk mengecek kondisi setiap file di setiap commit.
![image](https://user-images.githubusercontent.com/92366497/220066048-a6713b93-3c52-4764-8381-2de279be5b54.png)

**Git Reset**

perintah ini berfungsi untuk mengatur ulang. Maksudnya, perintah ini merupakan perintah untuk mengembalikan suatu kondisi berkas ke commit yang dituju dan menghapus riwayat sesudahnya.
![image](https://user-images.githubusercontent.com/92366497/220066325-d8f3b656-78af-4cc4-91b1-4d137a0d3353.png)

**Git Revert**

Git Revert merupakan perintah yang mirip dengan reset, tetapi fungsinya lebih daripada Git Reset. Perintah ini akan mengembalikan kondisi suatu berkas ke waktu/commit yang dituju tanpa menghapus catatan riwayat commit.
![image](https://user-images.githubusercontent.com/92366497/220066463-3375e839-8c19-4b93-826b-e1b29a19f598.png)

Alur kerja dari Git :
![image](https://user-images.githubusercontent.com/92366497/220066550-0bd9ba79-66da-4666-897a-6a1c0fa4d5e4.png)

Mengenal Repository
* Remote Repository, Remote Repository merupakan tempat penyimpanan berkas-berkas pekerjaan atau kenangan yang kita miliki di dalam server. Anda bisa menggunakan   berbagai layanan penyimpanan berbasis cloud yang sangat populer seperti GitHub, Gitlab, dan BitBucket. Selain itu, jika Anda memiliki server sendiri, Anda juga dapat menginstal layanan Git ke dalam server Anda. Dengan menggunakan Remote Repository, orang lain dapat mengakses repository yang kita simpan dengan mudah.
* Local Repository, Local Repository merupakan tempat penyimpanan lokal yang berada di komputer kita. Local repository ini dapat kita ubah-ubah (hapus, modifikasi, tambah) sesuai dengan keinginan kita sebelum akhirnya nanti di-push ke remote repository.

Ketika Anda memilih repository bersifat Public, repository tersebut akan terbuka dan dapat dilihat oleh orang lain, serta orang lain dapat mengajukan untuk berkontribusi di dalamnya. Sementara itu, jika Anda memilih repository bersifat Private, repository akan bersifat tertutup dan tidak akan bisa dilihat oleh orang lain selain orang-orang yang diundang sebagai Collaborator.
![image](https://user-images.githubusercontent.com/92366497/220066757-1d3cfaba-811f-40ac-8d51-bd1e24120065.png)


Terdapat 3 hal yang dapat diinisialisasi ketika membuat repository baru di GitHub. Berikut detailnya:
* Add a README file atau penambahan README File pada repository baru. Ketika repository telah dibuat, GitHub secara otomatis membuatkan file Readme ke dalam repository. Berkas README ini nantinya dapat Anda ubah untuk keperluan penjelasan lebih detail terhadap apa yang ada di dalam repository tersebut.
* Add .gitignore atau penambahan berkas .gitignore pada repository. Ketika repository telah terbuat, file .gitignore akan tercipta sesuai dengan pilihan template .gitignore yang dipilih.
* Choose a license atau penambahan berkas license pada repository. Ketika membuat repository, Anda bisa memilih lisensi untuk repository tersebut sehingga proyek yang ada di dalamnya dapat digunakan secara bebas oleh orang lain. Tentunya dengan syarat dan ketentuan yang berlaku sesuai dengan lisensi yang kita pilih ya. Biasanya penambahan lisensi diperuntukan bagi para pengguna Git yang biasa membuat proyek software atau aplikasi yang bersifat open source di repository mereka.
Membuat Readme di Github :
* Simbol (#), untuk heading
* Simbol (==), untuk heading
* Simbol (--), untuk sub-heading
* Simbol (*tulisan*), untuk teks bercetak miring
* Simbol (-), untuk membuat list

![image](https://user-images.githubusercontent.com/92366497/220067027-c375e44f-eaac-4679-b3c3-aa36694f015b.png)
* Bagian tag version berfungsi untuk membuat nama versi. Biasanya nama versi dituliskan dengan huruf v, lalu diikuti dengan nomor versi. Contohnya, seperti v1.0, v1.0.0, dan sejenisnya. Jika pembuatan release file digunakan untuk proyek aplikasi, sebaiknya penamaan dari tag version menggunakan semantic versioning.
* Bagian release title atau judul dari versi rilis berfungsi sebagai judul rilis yang menjelaskan secara singkat versi rilis yang akan dibuat.
* Bagian description atau deskripsi versi rilis berfungsi untuk menuliskan deskripsi detail dari versi rilis yang akan dibuat.
* Bagian Attach binaries berfungsi untuk tempat mengunggah file binary, contohnya file-file hasil compile program, compressed file source code, atau file dokumentasi. Biasanya attach binaries digunakan para pengguna Git yang membuat release file untuk proyek aplikasi.
* Bagian checkbox pre-release berfungsi untuk menandai bahwa pembuatan rilis ini bersifat pra rilis atau masih dalam bentuk beta. Bagian ini biasa digunakan para pengguna Git yang sedang dalam pengembangan proyek aplikasi di repository GitHub.

![image](https://user-images.githubusercontent.com/92366497/220067234-723ef187-d035-489d-9378-ff478ca8e93f.png)
Pada gambar di atas kita bisa melihat releasefile yang telah berhasil dibuat. 
* Pada bagian kanan atas terdapat button edit dan delete yang berfungsi untuk mengedit file release ataupun menghapus jika diperlukan.
* Lalu, di samping kiri ada detail dari versi rilis, mulai dari tag version ke berapa, versi rilis pada kode commit apa, dan ada juga tombol compare. Tombol compare berfungsi untuk melakukan komparasi antara satu versi rilis dengan versi rilis lainnya.
* Selanjutnya, di bagian tengah terdapat tampilan dari release title, deskripsi tentang release file, dan Assets. Pada bagian assets akan menyediakan tautan untuk mengunduh proyek sesuai versi yang telah dibuat, biasanya dalam bentuk zip atau tar.gz.


*Git Branch*

Branching adalah teknik untuk memisahkan cabang utama ke cabang lain dengan tujuan agar cabang utama tetap bisa dijaga kondisinya.
![image](https://user-images.githubusercontent.com/92366497/220154823-4ce62028-0de2-4f46-a8d8-6f7954b84179.png)

Pada ilustrasi di atas terdapat 3 branch, yaitu:

* Master, yaitu branch (cabang) utama yang seharusnya tidak memiliki bug atau apa pun yang berhubungan dengan kesalahan dalam pengodean/coding. Umumnya, cabang inilah yang dipakai sebagai production atau versi stabil.
* Fitur baru, yaitu branch untuk menambah fitur baru. Semua commit yang berhubungan dengan fitur baru akan di-push ke branch ini.
* Bug fixing, yaitu branch yang digunakan untuk memperbaiki bug yang terjadi. Cabang bug fixing dibuat terpisah untuk menghindari kesalahan penulisan pada kode perbaikan yang dapat menyebabkan cabang utama menjadi memiliki lebih banyak bug.
