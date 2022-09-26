# Pemrograman-Client-Server-Latihan-1
## Langkah - Langkah untuk membuat latihan 1
1. Untuk langkah pertama, kita perlu masuk ke link start.spring.io untuk mendownload file spring. Disini untuk file nya
harus kita sesuaikan yang sudah terinstall di laptop / pc anda 
yang saya gunakan :
	a. Project : maven project
	b. Language : java
	c. Spring boot : 2.7.4
	d.  Project metadata
		  Group : com.farid
		  Artifact : latihan-service
	    Packaging : java
	    java : 17
	    Untuk dependencies kita hanya menggunakan spring web
2. Setelah itu kita generate
3. Untuk file yang di generate tadi itu bisa kita pindahkan sesuai dengan kemauan kita sendiri, misalkan tadi letaknya didownload
bisa kita pindahkan di D:\Kuliah Parid\Semester 3\Pemrograman Client Server 2\latihan-service\latihan-service ( ini contoh punya saya ) .
3. Setelah memindahkan file ditempat yang kita inginkan kita bisa ekstrak file tersebut.
4. Lalu buka apache netbeans 13 ( karna saya punya yang 3 dan jdk 17 seperti yang sudah didownload/generate pada start.spring.io
5. Lalu import file tadi, kemudian build with dependencies dan tunggu beberapa saat sampai keluar output tulisan spring 
6. Kemudian masukkan perintah seperti dibawah ini pada Source Package -> com.farid.microservices.latihanservice -> LatihanServiceApplication.java
![image](https://user-images.githubusercontent.com/113502299/192332426-e2f5d644-4d01-4902-8c85-70d35be286c8.png)

7. Lalu kita akan mengatur port yang akan kita gunakan, disini saya menggunakan port 8080 untuk latihan
8. Terakhir kita run file di LatihanServiceApplication.java
![image](https://user-images.githubusercontent.com/113502299/192332486-0dedb80c-6c80-4516-81c1-2db75445bad6.png)

9. Setelah itu kita pergi ke chrome kita lalu ketikkan http://localhost:8080/hello
