Terima kasih sudah membaca

ini adalah serangkaian tutorial singkat cara mengimpor file 
dari repositori lokal ke repositori github versi saya dalam konteks, saya biasa menggunakan cara ini untuk mengirim file pertama kali di github memakai git.

atau kalian bisa membaca serangkaian caranya di githubdocs

step sebelum masuk ke kelangkah pertama install git terlebih dahulu di google.

=========================================================================================================
1. buatlah folder yang ingin kamu upload ke github 
contoh nya saya membuat file bertuliskan 'Tutorial' di file data D yang didalam nya ada 
html dan text Readme.txt.

2. bukalah cmd lalu masuk ke folder yang kamu barusan buat tadi, 
karena saya tadi buat folder nya di data D, maka saya akan ke data D => folder Tutorial
lalu mengetikkan perintah " git init -b main ", perintah ini untuk menginisialisasi repositori lokal kamu
dan kemudian membuat branch baru bernama main ,

3. karena didalam nya tadi ada file-file yang akan mau di kirim 
jadi didalam folder Tutorial di cmd saya ketik git add . ( titik disini
maksud nya ialah mengcopy semua yang ada didalam folder tutorial )

4. setelah di add langsung saja ketik " git commit -m "commit pertama saya di github "

5. selanjut nya mengirim repositori lokal ke repositori github, login dulu ke github
lalu saya buat repositori baru di github bernama ( Tutorial ) kemudian repositori yang saya buat tadi, saya copy link nya, 
dengan cara ke repositori yang brusan kamu buat, klik <>code lalu salin link https nya dan pastekan di cmd maka :

D:/Tutorial/ paste disini maka jadinya saya ketik " git push https://github.com/EclaireRr/Tutorial.git " 

contoh link https://github.com/EclaireRr/Tutorial.git 

EclaireRr adalah Username saya di github/ dan Tutorial.git adalah nama repositori saya yang akan saya buat di github 

kilas balik nya 
1. git init -b main
2. git add .
3. git commit -m " bebas tulis apa "
4. git push url https kamu 

=========================================================================================================



