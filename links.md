---
layout: "layout"
permalink: /LINKS/
---

# LINKS WEEK01
1. [Pengantar Linux](https://training.linuxfoundation.org/training/introduction-to-linux/)
   Ini  pengantar Linux yang dibuat oleh The Linux Foundation sendiri dan dapat diakses secara gratis juga. Dalam Website Ini mencakup dari Dasar-dasar Linux, Bash Shell, Operasi Jaringan, hingga Prinsip Keamanan Lokal. Ini akan berguna untuk referensi di masa mendatang.

2. [Penggunaan "su -" lebih baik daripada "su"](https://www.linuxquestions.org/questions/linux-newbie-8/command-usermod-not-found-385901/)  
   Perintah su dengan opsi "-" memberi kita path lengkap yang dimiliki root saat masuk ke sistem setelah startup. Perintah su biasa tidak akan melakukan hal seperti menambahkan pengguna baru ke grup sudoer.
   
3. [SSH Config Files](https://www.ssh.com/academy/ssh/config)
   File SSH Config dapat sangat berguna jika kita tidak ingin mengetik perintah ssh yang panjang untuk menggunakan opsi lanjutan dari SSH. SSH juga memungkinkan Anda untuk lebih fleksibel dan Anda dapat menggunakan SSH sesuai keinginan kita. Tetapi kita dapat melakukannya dengan SSH Configs menggunakan opsi ForwardAgent dan ProxyJump. Ini sangat berguna.
   
4. [Git Alias](https://git-scm.com/book/en/v2/Git-Basics-Git-Aliases)  
   Git memiliki alias untuk mempersingkat perintah. Tidak semua machine memiliki alias, hal ini akan sangat membantu jika ada satu yang terpasang di dalam program itu sendiri. salah satu alias yang saya temukan seperti git undo, alias ini memungkinkan kita dapat membatalkan komit terbaru untuk berjaga-jaga jika kita tidak dapat mengubahnya.


# LINKS WEEK02
1. [Keys on GPG](https://www.dewinter.com/gnupg_howto/english/GPGMiniHowto-3.html)<br>
   Tutorial terkait beberapa step mengenai key pada GPG mulai dari cara membuat key, mengexport key, mengimport key dan lainnya.

2. [Bash](https://ryanstutorials.net/bash-scripting-tutorial/bash-script.php)<br/>
Penggunaan Bash dalam mengompilasikan beberapa perintah dan mendifinisikannya sebagai file tunggal, contohnya dengan penggunaan SHA256SUM

# LINKS WEEK 03
1. [Pengenalan Bahasa C](https://www.geeksforgeeks.org/c-language-set-1-introduction/)<br>
Pengenalan bahasa pemrograman yang dipakai pada materi ketiga, apa itu bahasa C dan mengapa kita menggunakan bahasa pemrograman ini pada mata kuliah Sistem Operasi.

2. [Fuse](https://www.kernel.org/doc/html/latest/filesystems/fuse.html)<br>
Pengenalan Fuse yang membicarakan bahwa sistem file ruang pengguna merupakan sistem file yang mengandung data dan metadata disediakan oleh proses ruang pengguna biasa.

3. [Pengenalan Sistem File Linux](https://opensource.com/article/19/3/virtual-filesystems-linux)<br>
Kernel Linux mengharuskan entitas untuk menjadi sistem file, kernel memperlakukan sistem file generik sebagai antarmuka abstrak, dan tiga fungsi besar ini "virtual," tanpa definisi default. Oleh karena itu, implementasi sistem file default kernel disebut sistem file virtual (VFS).

4. [File Storage](https://www.geeksforgeeks.org/understanding-file-system/)<br>
File storage system yang sering digunakan terdapat 4 file storage system serta berbeda berdasarkan definisinya masing-masing.

# LINKS WEEK 04
1. [Addresing dan Pointers](https://beginnersbook.com/2014/01/c-pointers/)<br>
Materi mengenai addressing dan pointers pada bahasa pemrograman C.

2. [Tarball](https://www.networkworld.com/article/3328840/working-with-tarballs-on-linux.html)<br>
Proses mencadangkan sekelompok file dan menggabungkannya menjadi data tunggal dengan tipe file .tar. merupakan cara kerja Tarball.

# LINKS WEEK 05
1. [NUMA (Non-Uniform Memory Access)](https://whatis.techtarget.com/definition/NUMA-non-uniform-memory-access)<br>
Di dalam sistem yang memiliki lebih dari satu processor tentu membutuhkan penengah sehingga dibuatlah NUMA. Website ini menjelaskan apa itu NUMA, cara kerjanya, bahkan aplikasinya secara singkat dan menggunakan bahasa yang mudah dimengerti.

2. [Virtual Memory](https://www.youtube.com/watch?v=2quKyPnUShQ)<br>
Sebuah video yang membahas dari definisi, fungsi, dan cara kerja dari virtual memory. Video ini saya rekomendasikan karena pembahasannya sangat jelas dan mudah dimengerti.

3. [Process Table](https://exposnitc.github.io/os_design-files/process_table.html)<br>
Website Ini memiliki penjelasan yang cukup terinci mengenai proses dan cara kerjanya.

4. [Page Fault](https://techterms.com/definition/page_fault)<br>
Apabila sebuah program pernah mengalami hang atau crash, salah satu penyebabnya adalah Page Fault. Melalui website ini, dijelaskan secara lengkap mengenai definisi, penyebab, penanganan, dan akibat Page Fault secara singkat, jelas, dan padat.

# LINKS WEEK 06
1. [Fork](https://www.geeksforgeeks.org/fork-system-call/)<br>
Berisi penjelasan mengenai fork dengan penjelasan yang singkat, terdapat gambar, dan terdapat contoh code yang akan memudahkan pembaca memahami secara mendalam mengenail fork.

2. [Perbedaan CPU Cores dan Threads Explained](https://www.youtube.com/watch?v=hwTYDQ0zZOw)<br>
Dalam video ini, pengetahuan yang diberikan tidak hanya menjelaskan mengenai perbedaan antara Core dan Thread saja, tetapi diidalam video ini juga dijelaskan mengenai proses Multithreading. Saya memilih video ini karena video ini singkat, jelas dan padat sehingga mudah untuk dipahami.

3. [Process Execution Priority](https://developer.ibm.com/technologies/linux/tutorials/l-lpic1-103-6/)<br>
Blog yang menjelaskan mengenai prioritas eksekusi proses di Linux serta cara mengatur prioritas.

# LINKS WEEK 07
1. [Proses Deadlocks dalam Sistem Operasi](https://www.tutorialspoint.com/process-deadlocks-in-operating-system)<br>
menjelaskan jenis-jenis deadlock juga cara mencegah dan menghindari deadlock melalui media teks dan ilustrasi. Saya pribadi belum pernah bertemu dengan masalah ini sehingga sulit untuk dibayangkan, tetapi blog ini berhasil menjelaskannya dengan sangat baik.

2. [Critical Section](https://tuxthink.blogspot.com/2013/07/introduction-to-critical-section-with.html)<br>
menjelaskan tentang critical section yang masih agak berhubungan dengan race condition. Saya memilih website ini karena terdapat penjelasan dengan teks yang singkat dan mudah dipahami, apalagi ditambah dengan animasi sederhana.

3. [Race Conditions](https://www.youtube.com/watch?v=MqnpIwN7dz0)<br>
menjelaskan tentang race conditions dan cara penanganannya menggunakan Dekker's Algorithm. Menurut saya, video ini sangat bagus untuk ditonton karena masalah ini cukup sering ditemukan, salah satu yang pernah saya alami adalah saat mempelajari game development.

# LINKS WEEK 08
1. [CPU Scheduling](https://www.studytonight.com/operating-system/cpu-scheduling)<br>
Berisi mengenai definisi, kegunaan, jenis, dan kriteria dari CPU Scheduling. Topik tersebut dirangkum dalam penjelasan yang relatif singkat dalam website ini sehingga menarik untuk dipelajari.

2. [Perbedaan antara Scheduler dan Dispatcher](https://www.differencebetween.com/difference-between-scheduler-and-vs-dispatcher/)<br>
Scheduler dan Dispatcher terlihat mirip, tetapi keduanya memiliki definisi, cara kerja, dan kegunaan yang berbeda. Pada website ini, perbedaan keduanya dijelaskan menggunakan tabel perbandingan sehingga mudah dipahami.

3. [Process Scheduling](https://www.guru99.com/process-scheduling.html)<br>
membahas tentang perbedaan antara ketiga scheduler yaitu Long, Medium, dan Short Term Scheduler. Pada website ini, perbedaan dari ketiga prosses dijelaskan menggunakan tabel perbandingan sehingga mudah dipahami.
