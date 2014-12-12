# Tutorial Git

Jadi, sebenarnya apa yang dimaksud dengan Git? Ini adalah bagian penting untuk dipahami, karena jika anda memahami apa itu Git dan cara kerjanya, maka dapat dipastikan anda dapat menggunakan Git secara efektif dengan mudah. Selama mempelajari Git, cobalah untuk melupakan VCS lain yang mungkin telah anda kenal sebelumnya, misalnya Subversion dan Perforce. Git sangat berbeda dengan sistem-sistem tersebut dalam hal menyimpan dan memperlakukan informasi yang digunakan, walaupun antar-muka penggunanya hampir mirip. Dengan memahami perbedaan tersebut diharapkan dapat membantu anda menghindari kebingungan saat menggunakan Git.[[*more*]:http://git-scm.com/book/id/v1/Memulai-Git-Dasar-Git]

## Global setup:

*Global setup* dipakai setelah berhasil meng*install* Git untuk pertama kali. *Global setup* berguna untuk mengetahui siapa yang berkontribusi saat melakukan kolaborasi.

```
git config --global user.name "Your Name"
git config --global user.email "youremail@email.domain"
```

## Next step:

Selanjutnya membuat repositori *project* yang akan di*track* oleh Git.

```
mkdir TutorialGit
cd TutorialGit
git init
git add README.md
git commit -m "initial commit"
git remote add origin git@github.com/maxsinus/TutorialGit.git
git push -u origin master
```

## Existing Git Repo?

Jika sudah memiliki repositori, Anda bisa menambahkan repositori *remote* dengan cara:
```
cd nama_repo
git remote add origin git@github.com/maxsinus/TutorialGit.git
git push -u origin master
```
![Fork Me](https://raw.githubusercontent.com/maxsinus/TutorialGit/master/img/fork_me.png)