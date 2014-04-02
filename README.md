Ownership_file_linux
====================

Merubah Ownership / kepemilikan dari suatu file atau folder / direktory :

1. Di gambar "1", menjelaskan pembuatan sebuah folder / direktory. Dengan mengetikkan " mkdir nama_folder".
2. Di gambar "2", melihat kepemilikan dari suatu folder / direktory. Dengan mengetikkan " ls -li ".
3. Di gambar "3", menjelaskan cara masuk ke dalam sebuah direktory / folder. Dengan mengetikkan " cd nama_folder ".
4. Di gambar "4", menjelaskan cara untuk membuat sebuah file. Dengan mengetikkan " touch nama_file ".
5. Di gambar "5", melihat kepemilikan dari suatu file. Dengan mengetikkan " ls -li ".
6. Di gambar "6", menjelaskan tentang bagaimana cara membuat sebuah group. Dengan mengetikkan " groupadd nama_group ".
7. Di gambar "7", menjelaskan tentang bagaimana cara membuat user di dalam group. Dengan mengetikkan " useradd -G nama_group nama_user ".
8. Di gambar "8", merupakan cara merubah ownership dari suatu file, ada beberapa cara tapi yang saya contohkan adalah memasukkan ke dalam user dan group yang sudah kita buat tadi. Dengan mengetikkan " chown nama_user.nama_group nama_file". Kemudian chek dengan perintah " ls -li ".
9. Di gambar "9", merupakan cara merubah ownership dari suatu folder / direktory, ada beberapa cara tapi yang saya contohkan adalah memasukkan ke dalam user dan group yang sudah kita buat tadi. Dengan mengetikkan " chown nama_user.nama_group nama_folder". Kemudian chek dengan perintah " ls -li ".

NOTE : ada beberapa perintah yang awalnya harus memakai " sudo ", digunakan untuk mendapak akses dari super user.

LP3I BC SEMARANG
