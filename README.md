# belajarGIT
Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject
Daftar perintah GiT

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web (master)
$ git clone https://github.com/RezaMawara/belajarGIT
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web (master)
$ cd belajarGIT

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (main)
$ git branch
* main

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (main)
$ git branch Tugas-git

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (main)
$ git checkout Tugas-git
Switched to branch 'Tugas-git'

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-git.txt

nothing added to commit but untracked files present (use "git add" to track)

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (Tugas-git)
$ git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Turn this message off by running
hint: "git config advice.addEmptyPathspec false"

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (Tugas-git)
$ git add Tugas-git.txt

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-git.txt


ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (Tugas-git)
$ git commit -m "Tugas-git"
[Tugas-git 9e22d8d] Tugas-git
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (main)
$ git marge Tugas-git
git: 'marge' is not a git command. See 'git --help'.

The most similar command is
        merge

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (main)
$ git merge Tugas-git
Updating 7497f62..9e22d8d
Fast-forward
 Tugas-git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 297 bytes | 297.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/RezaMawara/belajarGIT
   7497f62..9e22d8d  main -> main

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (main)
$ git branch
  Tugas-git
* main

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (main)
$ git branch Tugas-html

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (main)
$ git checkout Tugas-html
Switched to branch 'Tugas-html'

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (Tugas-html)
$ git status
On branch Tugas-html
nothing to commit, working tree clean

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (Tugas-html)
$ git status
On branch Tugas-html
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-html.txt

nothing added to commit but untracked files present (use "git add" to track)

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (Tugas-html)
$ git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Turn this message off by running
hint: "git config advice.addEmptyPathspec false"

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (Tugas-html)
$ git add Tugas-html
fatal: pathspec 'Tugas-html' did not match any files

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (Tugas-html)
$ git add Tugas-html.txt

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (Tugas-html)
$ git status
On branch Tugas-html
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-html.txt


ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (Tugas-html)
$ git commit -m "Tuugas-html"
[Tugas-html 303dbbc] Tuugas-html
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (main)
$ git merge Tugas-html
Updating 9e22d8d..303dbbc
Fast-forward
 Tugas-html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 325 bytes | 325.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/RezaMawara/belajarGIT
   9e22d8d..303dbbc  main -> main

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (main)
$ git branch
  Tugas-git
  Tugas-html
* main

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (main)
$ git branch Tugas-css

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (main)
$ git checkout Tugas-css
Switched to branch 'Tugas-css'

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (Tugas-css)
$ touch Tugas-css.txt

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (Tugas-css)
$ nano Tugas-css.txt

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (Tugas-css)
$ git add Tugas-css.txt
warning: in the working copy of 'Tugas-css.txt', LF will be replaced by CRLF the next time Git touches it

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (Tugas-css)
$ git status
On branch Tugas-css
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-css.txt


ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (Tugas-css)
$ git commit -m "Tugas-css"
[Tugas-css 43935cc] Tugas-css
 1 file changed, 2 insertions(+)
 create mode 100644 Tugas-css.txt

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (main)
$ git merge Tugas-css
Updating 303dbbc..43935cc
Fast-forward
 Tugas-css.txt | 2 ++
 1 file changed, 2 insertions(+)
 create mode 100644 Tugas-css.txt

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 350 bytes | 350.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/RezaMawara/belajarGIT
   303dbbc..43935cc  main -> main

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (main)
$ git branch Tugas-js

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (main)
$ git checkout Tugas-js
Switched to branch 'Tugas-js'

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (Tugas-js)
$ git add Tugas-js.txt

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (Tugas-js)
$ git status
On branch Tugas-js
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-js.txt


ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (Tugas-js)
$ git commit -m "Tugas-js"
[Tugas-js 3d090de] Tugas-js
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (main)
$ git merge Tugas-js
Updating 43935cc..3d090de
Fast-forward
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 289 bytes | 289.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/RezaMawara/belajarGIT
   43935cc..3d090de  main -> main

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (main)
$ git branch Tugas-midProject

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (main)
$ git checkout Tugas-midProject
Switched to branch 'Tugas-midProject'

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (Tugas-midProject)
$ git status
On branch Tugas-midProject
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-midProject.txt


ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (Tugas-midProject)
$ git commit -m "Tugas-midProject"
[Tugas-midProject b51ce5d] Tugas-midProject
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (main)
$ git merge Tugas-midProject
Updating 3d090de..b51ce5d
Fast-forward
 Tugas-midProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 299 bytes | 299.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/RezaMawara/belajarGIT
   3d090de..b51ce5d  main -> main

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (main)
$ git branch Tugas-php

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (main)
$ git checkout Tugas-php
Switched to branch 'Tugas-php'

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (Tugas-php)
$ git status
On branch Tugas-php
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-php.txt

nothing added to commit but untracked files present (use "git add" to track)

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (Tugas-php)
$ git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Turn this message off by running
hint: "git config advice.addEmptyPathspec false"

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (Tugas-php)
$ git add Tugas-php
fatal: pathspec 'Tugas-php' did not match any files

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (Tugas-php)
$ git status
On branch Tugas-php
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-php.txt

nothing added to commit but untracked files present (use "git add" to track)

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (Tugas-php)
$ git add Tugas-php.txt

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (Tugas-php)
$ git status
On branch Tugas-php
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-php.txt


ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (Tugas-php)
$ git commit -m "Tugas-php"
[Tugas-php 0e10f7e] Tugas-php
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (main)
$ git merge Tugas-php
Updating b51ce5d..0e10f7e
Fast-forward
 Tugas-php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 286 bytes | 286.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/RezaMawara/belajarGIT
   b51ce5d..0e10f7e  main -> main

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (main)
$ git branch Tugas-finalProject

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (main)
$ git checkout Tugas-finalProject
Switched to branch 'Tugas-finalProject'

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (Tugas-finalProject)
$ git status
On branch Tugas-finalProject
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-finalProject.txt


ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (Tugas-finalProject)
$ git commit -m "Tugas-finalProject"
[Tugas-finalProject a7d7865] Tugas-finalProject
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (main)
$ git merge Tugas-finalProject
Updating 0e10f7e..a7d7865
Fast-forward
 Tugas-finalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 292 bytes | 292.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/RezaMawara/belajarGIT
   0e10f7e..a7d7865  main -> main

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (main)
$ git push original --all
fatal: 'original' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (main)
$ git push origin --all
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/RezaMawara/belajarGIT
 * [new branch]      Tugas-css -> Tugas-css
 * [new branch]      Tugas-finalProject -> Tugas-finalProject
 * [new branch]      Tugas-git -> Tugas-git
 * [new branch]      Tugas-html -> Tugas-html
 * [new branch]      Tugas-js -> Tugas-js
 * [new branch]      Tugas-midProject -> Tugas-midProject
 * [new branch]      Tugas-php -> Tugas-php

ASUS@LAPTOP-AT1SJL9R MINGW64 ~/Documents/Semester 4/Pemrograman Web/belajarGIT (main)
$
