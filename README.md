Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject
Daftar perintah GiT
a@INBook_X1 MINGW64 ~
$ cd "C:\Users\a\Documents\Semester 4\PROGRAM WEB"

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB
$ git clone https://github.com/SUGARDADY123/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB
$ cd belajarGIT

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (main)
$ git checkout -b Tugas-git
Switched to a new branch 'Tugas-git'

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (Tugas-git)
$ touch Tugas-Git.txt

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (Tugas-git)
$ git add Tugas-Git.txt

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan Tugas-Git.txt"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'a@INBook_X1.(none)')

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (Tugas-git)
$ ^C

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (Tugas-git)
$ git config --global user.email "yancemamangkey56@gmail.com"

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan Tugas-Git.txt"
[Tugas-git 3944045] Menambahkan Tugas-Git.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Git.txt

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (main)
$ git merge Tugas-git
Updating e697876..3944045
Fast-forward
 Tugas-Git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Git.txt

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (main)
$ git push origin main
fatal: unable to access 'https://github.com/SUGARDADY123/belajarGIT.git/': Failed to connect to github.com port 443 after 20645 ms: Couldn't connect to server

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (main)
$ ^C

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (main)
$ ^C

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 318 bytes | 318.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/SUGARDADY123/belajarGIT.git
   e697876..3944045  main -> main

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (main)
$ git checkout -b Tugas-html
Switched to a new branch 'Tugas-html'

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (Tugas-html)
$ touch Tugas-Html.txt

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (Tugas-html)
$ git add Tugas-Html.txt

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (Tugas-html)
$ git commit -m "Menambahkan Tugas-Html.txt"
[Tugas-html 9a6a6cb] Menambahkan Tugas-Html.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Html.txt

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (main)
$ git merge Tugas-html
Updating 3944045..9a6a6cb
Fast-forward
 Tugas-Html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Html.txt

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 331 bytes | 331.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/SUGARDADY123/belajarGIT.git
   3944045..9a6a6cb  main -> main

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (main)
$ git checkout -b Tugas-css
Switched to a new branch 'Tugas-css'

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (Tugas-css)
$ touch Tugas-Css.txt

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (Tugas-css)
$ git add Tugas-Css.txt

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan Tugas-css.txt
> git commit -m "Menambahkan Tugas-css.txt
error: pathspec 'Tugas-css.txt' did not match any file(s) known to git

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan Tugas-css.txt
>
> "
[Tugas-css 0950e97] Menambahkan Tugas-css.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Css.txt

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (main)
$ git merge Tugas-css
Updating 9a6a6cb..0950e97
Fast-forward
 Tugas-Css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Css.txt

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 245 bytes | 245.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/SUGARDADY123/belajarGIT.git
   9a6a6cb..0950e97  main -> main

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (main)
$ git checkout -b Tugas-js
Switched to a new branch 'Tugas-js'

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (Tugas-js)
$ touch Tugas-Js.txt

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (Tugas-js)
$ git add Tugas-Js.txt

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (Tugas-js)
$ git commit -m "Menambahkan Tugas-css.txt"
[Tugas-js f6a6841] Menambahkan Tugas-css.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Js.txt

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (main)
$ git merge Tugas-js
Updating 0950e97..f6a6841
Fast-forward
 Tugas-Js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Js.txt

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 271 bytes | 271.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/SUGARDADY123/belajarGIT.git
   0950e97..f6a6841  main -> main

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (main)
$ git checkout -b Tugas-midProject
Switched to a new branch 'Tugas-midProject'

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (Tugas-midProject)
$ touch Tugas-^Cxt

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (Tugas-midProject)
$ git merge Tugas-^[[200~midProject
merge: Tugas-midProject - not something we can merge

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (Tugas-midProject)
$ touch Tugas-Midproject.txt

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (Tugas-midProject)
$ git add Tugas-Midproject.txt

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (Tugas-midProject)
$ git commit -m "Menambahkan Tugas-Midproject.txt"
[Tugas-midProject e190ad1] Menambahkan Tugas-Midproject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Midproject.txt

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (main)
$ git merge Tugas-midProject
Updating f6a6841..e190ad1
Fast-forward
 Tugas-Midproject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Midproject.txt

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (main)
$ git push origin main

Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 259 bytes | 259.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/SUGARDADY123/belajarGIT.git
   f6a6841..e190ad1  main -> main

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (main)
$ git checkout -b Tugas-php
Switched to a new branch 'Tugas-php'

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (Tugas-php)
$ touch Tugas-Php.txt

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (Tugas-php)
$ git add Tugas-Php.txt

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (Tugas-php)
$ git commit -m "Menambahkan Tugas-Php.txt"
[Tugas-php e7b2f2b] Menambahkan Tugas-Php.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Php.txt

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (main)
$ git merge Tugas-php
Updating e190ad1..e7b2f2b
Fast-forward
 Tugas-Php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Php.txt

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (main)
$ git push origin main

Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 249 bytes | 249.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/SUGARDADY123/belajarGIT.git
   e190ad1..e7b2f2b  main -> main

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (main)
$ git checkout -b Tugas-finalProject
Switched to a new branch 'Tugas-finalProject'

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (Tugas-finalProject)
$ touch Tugas-FinalProject.txt

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (Tugas-finalProject)
$ git add Tugas-FinalProject.txt

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan Tugas-FinalProject.txt"
[Tugas-finalProject ce615d6] Menambahkan Tugas-FinalProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-FinalProject.txt

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (main)
$ git merge Tugas-finalProject
Updating e7b2f2b..ce615d6
Fast-forward
 Tugas-FinalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-FinalProject.txt

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 266 bytes | 266.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/SUGARDADY123/belajarGIT.git
   e7b2f2b..ce615d6  main -> main

a@INBook_X1 MINGW64 ~/Documents/Semester 4/PROGRAM WEB/belajarGIT (main)
$
