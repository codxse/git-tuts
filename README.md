# Tutorial Git

Jadi, sebenarnya apa yang dimaksud dengan Git? Ini adalah bagian penting untuk dipahami, karena jika anda memahami apa itu Git dan cara kerjanya, maka dapat dipastikan anda dapat menggunakan Git secara efektif dengan mudah. Selama mempelajari Git, cobalah untuk melupakan VCS lain yang mungkin telah anda kenal sebelumnya, misalnya Subversion dan Perforce. Git sangat berbeda dengan sistem-sistem tersebut dalam hal menyimpan dan memperlakukan informasi yang digunakan, walaupun antar-muka penggunanya hampir mirip. Dengan memahami perbedaan tersebut diharapkan dapat membantu anda menghindari kebingungan saat menggunakan Git. [[*more*](http://git-scm.com/book/id/v1/Memulai-Git-Dasar-Git)]

## Global setup:

*Global setup* dipakai setelah berhasil [meng*install*](http://git-scm.com/book/id/v1/Memulai-Git-Menginstall-Git) Git untuk pertama kali. *Global setup* berguna untuk mengetahui siapa yang berkontribusi saat melakukan kolaborasi.

```
git config --global user.name "Your Name"
git config --global user.email "youremail@email.com"
```
**Opsi Tambahan:**

+ [*Setup* kunci SSH](https://help.github.com/articles/generating-ssh-keys/#platform-windows) untuk OS Windows.
+ [*Setup* kunci SSH](https://help.github.com/articles/generating-ssh-keys/#platform-linux) untuk OS Linux.
+ [*Setup* kunci SSH](https://help.github.com/articles/generating-ssh-keys/#platform-mac) untuk OS Mac.

## Next step:

Selanjutnya membuat repositori *project* yang akan di*track* oleh Git.

```
mkdir TutorialGit
cd TutorialGit
git init
git add README.md
git commit -m "initial commit"
git remote add origin git@github.com:maxsinus/TutorialGit.git
git push -u origin master
```

## Existing Git Repo?

Jika sudah memiliki repositori, Anda bisa menambahkan repositori *remote* dengan cara berikut:
```
cd nama_repo
git remote add origin git@github.com:maxsinus/TutorialGit.git
git push -u origin master
```

## Exercise

Tautan-tautan berikut adalah tautan menuju web/halaman yang bisa Anda pakai sebagai materi latihan menggunakan Git, Anda bahkan bisa menjadi master Git.

+ mirror pdf: [Git Cheat Sheet](https://github.com/maxsinus/TutorialGit/blob/master/mirror/github-git-cheat-sheet.pdf?raw=true)
+ mirror pdf: [ProGit v1](https://github.com/maxsinus/TutorialGit/blob/master/mirror/progit.en.pdf?raw=true)
+ mirror pdf: [ProGit v2](https://github.com/maxsinus/TutorialGit/blob/master/mirror/progit-en.210.pdf?raw=true)
+ [git-scm v1](http://git-scm.com/book/en/v1)
+ [git-scm v2](http://git-scm.com/book/en/v2)
+ [git-scm v1 bahasa Indonesia](http://git-scm.com/book/id/v1) (rekomendasi)
+ Video tutorial Git dari [Jason Semko](https://www.youtube.com/user/thejacenxpress/videos) (rekomendasi)
+ Video tutorial [Git & GitHub Guides](https://www.youtube.com/user/GitHubGuides/videos)
+ Latihan: [Belajar Git di KelasKita](https://kelaskita.com/kelaskita/kelas/mengenal-git/)
+ Latihan: [Belajar Git interaktif di KelasKita](https://kelaskita.com/kelaskita/kelas/git-interaktif/)
+ Latihan: [Git Branching Exercise](http://eecs.mines.edu/Courses/csci306/ASSIGN/Exercises/GitBranching.html) 
+ Video dan latihan: [GitHub Training](https://training.github.com/resources/videos/)
+ Video dan latihan: [Mastering GitHub](https://www.codeschool.com/courses/mastering-github)

### Advanced Topics

Topik ini diasumsikan bahwa Anda sudah mengerti *branch*, *checkout*, *commit*, *log*, *merge*, *push*, dan *pull*.

+ [Mengenal Git rebase](https://help.github.com/articles/about-git-rebase)
+ [Tutorial Git rebase](https://help.github.com/articles/using-git-rebase)
+ [Tutorial Git rebase](http://stackoverflow.com/questions/1186535/how-to-modify-a-specified-commit): merubah file commit tertentu
+ [Tutorial Git](http://stackoverflow.com/questions/7744049/git-how-to-rebase-to-a-specific-commit): *how to rebase to a specific commit?*
+ [Tutorial Git](http://stackoverflow.com/questions/14635672/git-rebase-a-single-commit): *rebase a single commit*
+ [Tutorial Git](https://www.atlassian.com/git/tutorials/rewriting-history/git-commit--amend): `git commit --amend`
+ [Git reset vs Git checkout](http://stackoverflow.com/questions/3639342/whats-the-difference-between-git-reset-and-git-checkout) 
+ [Tutorial Git reset dan Git checkout](http://stackoverflow.com/questions/4114095/revert-to-a-previous-git-commit)
+ [Simple Git stash](http://stackoverflow.com/questions/2944469/how-to-commit-my-current-changes-to-a-different-branch-in-git)
+ [Complete Git stash](http://git-scm.com/book/en/v2/Git-Tools-Stashing)
+ [Opsi Git stash](http://git-scm.com/docs/git-stash)
