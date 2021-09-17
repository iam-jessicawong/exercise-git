Step-step dan command line saat menginisasi project untuk menggunakan git hingga sampai push ke github :
1. Buat repositori/folder/repositori pada komputer kita
2. Buka git bash atau cmd pada repostori tersebut
3. Kemudian ketikkan command "git init" untuk menjadikan folder tersebut sebagai repositori git
4. Buka github dan buat repositori baru pada github kemudian ikuti langkah-langkah yang sudah tertera saat pertama kali membuat repository pada bagian push existing repo atau copy link repo github tersebut dan ikuti langkah-langkah berikut ini
  1. Kembali pada git bash atau cmd pada repositori lokal, ketikkan command "git remote url_repo_github_yang_sudah_dicopy_sebelumnya" untuk menghubungkan repositori git dengan github
  2. Kemudian ketikkan command "git branch -M main"
  3. Setelah itu ketikkan command "git push -u origin main" untuk push repositori yang dari lokal ke github
5. Cek github repositorynya maka file-file yang ada pada lokal sudah masuk ke repo githubnya juga


Perbedaan git reset dan git revert
- Jika menggunakan git reset maka commit terakhirnya akan dihapus sedangkan dengan menggunakan git revert maka kita hanya kembali/mundur ke commit tertentu tanpa menghapus commit terakhirnya


Perbedaan GIT dan GITHUB
- git merupakan version control system yang bersifat lokal atau di komputer kita sedangkan github merupakan penyedia service untuk melakukan version control atau dengan kata lain github merupakan tempat penyimpanan repo git yang berbasis cloud sehingga dapat diakses oleh siapa saja
