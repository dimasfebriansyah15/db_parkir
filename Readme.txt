Install Database

Buka http://localhost/phpmyadmin

Buat sebuah database parkirdb
Lalu import script parkirdb.sql


Error saat loading project
Klik Resolve Problem, klik Resolve. Buka Folder lib , seleksi semua jar nya


Laporan

Buka package program.parkir -> ClassDatabase pada project

Disana ada info lokasi laporan

Jika menjalankan program dari Netbeans :
aktifkan public static String PathReport=System.getProperty("user.dir") + "/src/";

Jika menjalankan program dari program_parkir.jar
aktifkan public static String PathReport=System.getProperty("user.dir") + "/";  
dan copy file report *.jrxml dan *.jasper pada folder src ke satu folder 
program_parkir.jar (ini berfungsi jika tidak menggunakan netbeans/publikasi)