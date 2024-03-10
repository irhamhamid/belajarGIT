Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject
Daftar perintah GiT

iyam@iyam MINGW64 ~
$ cd D:\git

iyam@iyam MINGW64 /d/git
$ git clone https://github.com/irhamhamid/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

iyam@iyam MINGW64 /d/git
$ cd belajarGIT

iyam@iyam MINGW64 /d/git/belajarGIT (main)
$ git checkout -b Tugas-git
Switched to a new branch 'Tugas-git'

iyam@iyam MINGW64 /d/git/belajarGIT (Tugas-git)
$ touch Tugas-Git.txt

iyam@iyam MINGW64 /d/git/belajarGIT (Tugas-git)
$ git add Tugas-Git.txt

iyam@iyam MINGW64 /d/git/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan Tugas-Git.txt"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'iyam@iyam.(none)')

iyam@iyam MINGW64 /d/git/belajarGIT (Tugas-git)
$ git config --global user.email "irham.hamid82@gmail.com"

iyam@iyam MINGW64 /d/git/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan Tugas-Git.txt"
[Tugas-git 43dcfce] Menambahkan Tugas-Git.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Git.txt

iyam@iyam MINGW64 /d/git/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

iyam@iyam MINGW64 /d/git/belajarGIT (main)
$ git merge Tugas-git
Updating 958321f..43dcfce
Fast-forward
 Tugas-Git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Git.txt

iyam@iyam MINGW64 /d/git/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 302 bytes | 302.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/irhamhamid/belajarGIT.git
   958321f..43dcfce  main -> main

iyam@iyam MINGW64 /d/git/belajarGIT (main)
$ git checkout -b Tugas-html
Switched to a new branch 'Tugas-html'

iyam@iyam MINGW64 /d/git/belajarGIT (Tugas-html)
$ touch Tugas-Html.txt

iyam@iyam MINGW64 /d/git/belajarGIT (Tugas-html)
$ git status
On branch Tugas-html
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-Html.txt

nothing added to commit but untracked files present (use "git add" to track)

iyam@iyam MINGW64 /d/git/belajarGIT (Tugas-html)
$ git add Tugas-Html.txt

iyam@iyam MINGW64 /d/git/belajarGIT (Tugas-html)
$ git commit -m "Menambahkan Tugas-Html.txt"
[Tugas-html ab48398] Menambahkan Tugas-Html.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Html.txt

iyam@iyam MINGW64 /d/git/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

iyam@iyam MINGW64 /d/git/belajarGIT (main)
$ git merge Tugas-html
Updating 43dcfce..ab48398
Fast-forward
 Tugas-Html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Html.txt

iyam@iyam MINGW64 /d/git/belajarGIT (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 297 bytes | 297.00 KiB/s, done.
Total 2 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/irhamhamid/belajarGIT.git
   43dcfce..ab48398  main -> main

iyam@iyam MINGW64 /d/git/belajarGIT (main)
$ git checkout -b Tugas-css
Switched to a new branch 'Tugas-css'

iyam@iyam MINGW64 /d/git/belajarGIT (Tugas-css)
$ touch Tugas-Css.txt

iyam@iyam MINGW64 /d/git/belajarGIT (Tugas-css)
$ git add Tugas-Css.txt

iyam@iyam MINGW64 /d/git/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan Tugas-Css.txt"
[Tugas-css 4c29d1c] Menambahkan Tugas-Css.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Css.txt

iyam@iyam MINGW64 /d/git/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

iyam@iyam MINGW64 /d/git/belajarGIT (main)
$ git merge Tugas-css
Updating ab48398..4c29d1c
Fast-forward
 Tugas-Css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Css.txt

iyam@iyam MINGW64 /d/git/belajarGIT (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 248 bytes | 248.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/irhamhamid/belajarGIT.git
   ab48398..4c29d1c  main -> main

iyam@iyam MINGW64 /d/git/belajarGIT (main)
$ git checkout -b Tugas-js
Switched to a new branch 'Tugas-js'

iyam@iyam MINGW64 /d/git/belajarGIT (Tugas-js)
$ touch Tugas-Js.txt

iyam@iyam MINGW64 /d/git/belajarGIT (Tugas-js)
$ git add Tugas-Js.txt

iyam@iyam MINGW64 /d/git/belajarGIT (Tugas-js)
$ git commit -m "Menambahkan Tugas-Js.txt"
[Tugas-js f983181] Menambahkan Tugas-Js.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Js.txt

iyam@iyam MINGW64 /d/git/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

iyam@iyam MINGW64 /d/git/belajarGIT (main)
$ git merge Tugas-js
Updating 4c29d1c..f983181
Fast-forward
 Tugas-Js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Js.txt

iyam@iyam MINGW64 /d/git/belajarGIT (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 244 bytes | 244.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/irhamhamid/belajarGIT.git
   4c29d1c..f983181  main -> main

iyam@iyam MINGW64 /d/git/belajarGIT (main)
$
iyam@iyam MINGW64 ~
$ cd D:\git

iyam@iyam MINGW64 /d/git
$ git clone https://github.com/irhamhamid/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

iyam@iyam MINGW64 /d/git
$ cd belajarGIT

iyam@iyam MINGW64 /d/git/belajarGIT (main)
$ git checkout -b Tugas-git
Switched to a new branch 'Tugas-git'

iyam@iyam MINGW64 /d/git/belajarGIT (Tugas-git)
$ touch Tugas-Git.txt

iyam@iyam MINGW64 /d/git/belajarGIT (Tugas-git)
$ git add Tugas-Git.txt

iyam@iyam MINGW64 /d/git/belajarGIT (main)
$ git checkout -b Tugas-midProject
Switched to a new branch 'Tugas-midProject'

iyam@iyam MINGW64 /d/git/belajarGIT (Tugas-midProject)
$ touch Tugas-MidProject.txt

iyam@iyam MINGW64 /d/git/belajarGIT (Tugas-midProject)
$ git add Tugas-MidProject.txt

iyam@iyam MINGW64 /d/git/belajarGIT (Tugas-midProject)
$ git commit -m "Menambah Tugas-MidProject.txt"
[Tugas-midProject caaae3a] Menambah Tugas-MidProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-MidProject.txt

iyam@iyam MINGW64 /d/git/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

iyam@iyam MINGW64 /d/git/belajarGIT (main)
$ git merge Tugas-midProject
Updating f983181..caaae3a
Fast-forward
 Tugas-MidProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-MidProject.txt

iyam@iyam MINGW64 /d/git/belajarGIT (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 254 bytes | 25.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/irhamhamid/belajarGIT.git
   f983181..caaae3a  main -> main

iyam@iyam MINGW64 /d/git/belajarGIT (main)
$ git checkout -b Tugas-php
Switched to a new branch 'Tugas-php'

iyam@iyam MINGW64 /d/git/belajarGIT (Tugas-php)
$ touch Tugas-Php.jss

iyam@iyam MINGW64 /d/git/belajarGIT (Tugas-php)
$ touch Tugas-Php.txt

iyam@iyam MINGW64 /d/git/belajarGIT (Tugas-php)
$ git add Tugas-Php.txt

iyam@iyam MINGW64 /d/git/belajarGIT (Tugas-php)
$ git commit -m "Menambahkan Tugas-Php.txt"
[Tugas-php a5aa13b] Menambahkan Tugas-Php.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Php.txt

iyam@iyam MINGW64 /d/git/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

iyam@iyam MINGW64 /d/git/belajarGIT (main)
$ git merge Tugas-php
Updating caaae3a..a5aa13b
Fast-forward
 Tugas-Php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Php.txt

iyam@iyam MINGW64 /d/git/belajarGIT (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 244 bytes | 4.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/irhamhamid/belajarGIT.git
   caaae3a..a5aa13b  main -> main

iyam@iyam MINGW64 /d/git/belajarGIT (main)
$ git checkout -b Tugas-finalProject
Switched to a new branch 'Tugas-finalProject'

iyam@iyam MINGW64 /d/git/belajarGIT (Tugas-finalProject)
$ touch Tugas-FinalProject.txt

iyam@iyam MINGW64 /d/git/belajarGIT (Tugas-finalProject)
$ git add Tugas-FinalProject.txt

iyam@iyam MINGW64 /d/git/belajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan Tugas-FinalProject.txt"
[Tugas-finalProject d292772] Menambahkan Tugas-FinalProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-FinalProject.txt

iyam@iyam MINGW64 /d/git/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

iyam@iyam MINGW64 /d/git/belajarGIT (main)
$ git merge Tugas-finalProject
Updating a5aa13b..d292772
Fast-forward
 Tugas-FinalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-FinalProject.txt

iyam@iyam MINGW64 /d/git/belajarGIT (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 261 bytes | 130.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/irhamhamid/belajarGIT.git
   a5aa13b..d292772  main -> main

iyam@iyam MINGW64 /d/git/belajarGIT (main)
$

