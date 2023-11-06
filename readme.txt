Terima kasih sudah membaca

ini adalah serangkaian tutorial singkat cara mengimpor file 
dari repositori lokal ke repositori github versi saya dalam konteks saya biasa menggunakan cara ini.

atau kalian bisa membaca serangkaian caranya di githubdocs

seperti yang kita ketahui ada banyak cara untuk kita bisa mengimport file dari lokal ke github 


step sebelum masuk ke kelangkah pertama install git terlebih dahulu di google


1. buatlah folder yang ingin kamu upload ke github 
contoh nya saya membuat file bertuliskan 'Tutorial'di file data D yang didalam nya ada 
html dan text Readme.txt

2. bukalah cmd lalu masuk ke folder yang kamu barusan buat tadi, 
karena saya tadi buat folder nya di data D, maka saya akan ke data D folder Tutorial
lalu mengetikkan perintah git init -b main, perintah ini untuk menginisialisasi repositori lokal kamu
dan kemudian membuat branch baru bernama main 

3. karena didalam nya tadi ada file-file yang akan mau di kirim 
jadi didalam folder Tutorial di cmd saya ketik git add . ( titik disini
maksud nya ialah mengcopy semua yang ada didalam folder tutorial)

4. setelah di add langsung saja ketik " git commit -m "commit pertama saya ke github "

5. lalu selanjut nya mengirim file ke repo github, ini kalau cara saya, saya login dulu ke github
lalu saya buat repositori baru kemudian repositori yang saya buat copy link nya
contoh https://github.com/EclaireRr/Tutorial.git 

maka jadinya saya ketik " git push https://github.com/EclaireRr/Tutorial.git " 

