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
…
lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev
$ git init
Initialized empty Git repository in C:/Users/lenovo/Documents/WebDev/.git

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev (master)
$ git clone https://github.com/injiliatt/belajarGIT/blob/main/README.md
Cloning into 'README.md'...
fatal: repository 'https://github.com/injiliatt/belajarGIT/blob/main/READ
 not found

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev (master)
$ git clone https://github.com/injiliatt/belajarGIT/tree/main
Cloning into 'main'...
fatal: repository 'https://github.com/injiliatt/belajarGIT/tree/main/' no

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev (master)
$ git clone https://github.com/injiliatt/belajarGIT
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev (master)
$ cd belajarGIT

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (main)
$ git branch belajarGIT

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (main)
$ git checkout belajarGIT
Switched to branch 'belajarGIT'

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (belajarGIT)
$ git status
On branch belajarGIT
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        belajarGIT.txt

nothing added to commit but untracked files present (use "git add" to track)

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (belajarGIT)
$ git add belajarGIT.txt

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (belajarGIT)
$ git status
On branch belajarGIT
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   belajarGIT.txt


lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (belajarGIT)
$ git commit -m "tugasGIT"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'lenovo@DESKTOP-3OC8K9N.(none)')

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (belajarGIT)
$ ^C

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (belajarGIT)
$  git config --global user.email "injilticoalu0126@gmail.com"

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (belajarGIT)
$ git config --global user.name "injiliatt"

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (belajarGIT)
$ git commit -m "tugasGIT"
[belajarGIT 6d4520e] tugasGIT
 1 file changed, 1 insertion(+)
 create mode 100644 belajarGIT.txt

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (belajarGIT)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (main)
$ git merge belajarGIT
Updating b9a865a..6d4520e
Fast-forward
 belajarGIT.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 belajarGIT.txt

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 297 bytes | 297.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/injiliatt/belajarGIT
   b9a865a..6d4520e  main -> main

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (main)
$ git branch belajarHTML

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (main)
$ git checkout belajarHTML
Switched to branch 'belajarHTML'

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (belajarHTML)
$ git status
On branch belajarHTML
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        belajarHTML.txt

nothing added to commit but untracked files present (use "git add" to track)

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (belajarHTML)
$ git add belajarHTML.txt

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (belajarHTML)
$ git status
On branch belajarHTML
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   belajarHTML.txt


lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (belajarHTML)
$ git commit -m "tugasHTML"
[belajarHTML 8345027] tugasHTML
 1 file changed, 1 insertion(+)
 create mode 100644 belajarHTML.txt

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (belajarHTML)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (main)
$ git merge belajarHTML
Updating 6d4520e..8345027
Fast-forward
 belajarHTML.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 belajarHTML.txt

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 322 bytes | 322.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/injiliatt/belajarGIT
   6d4520e..8345027  main -> main

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (main)
$ git branch belajarCSS

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (main)
$ git checkout belajarCSS
Switched to branch 'belajarCSS'

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (belajarCSS)
$ git status
On branch belajarCSS
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        belajarCSS.txt

nothing added to commit but untracked files present (use "git add" to track)

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (belajarCSS)
$ git add belajarCSS.txt

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (belajarCSS)
$ git status
On branch belajarCSS
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   belajarCSS.txt


lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (belajarCSS)
$ git commit -m "tugasCSS"
[belajarCSS d03e270] tugasCSS
 1 file changed, 1 insertion(+)
 create mode 100644 belajarCSS.txt

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (belajarCSS)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (main)
$ git merge belajarCSS
Updating 8345027..d03e270
Fast-forward
 belajarCSS.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 belajarCSS.txt

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (main)
$ git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 231 bytes | 231.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/injiliatt/belajarGIT
   8345027..d03e270  main -> main

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (main)
$ git branch belajarJS

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (main)
$ git checkout belajarJS
Switched to branch 'belajarJS'

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (belajarJS)
$ ^C

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (belajarJS)
$ git status
On branch belajarJS
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        belajarJS.txt

nothing added to commit but untracked files present (use "git add" to track)

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (belajarJS)
$ git add belajarJS.txt

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (belajarJS)
$ git status
On branch belajarJS
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   belajarJS.txt


lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (belajarJS)
$ git commit -m "tugasJS"
[belajarJS 1730abf] tugasJS
 1 file changed, 1 insertion(+)
 create mode 100644 belajarJS.txt

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (belajarJS)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (main)
$ git merge belajarJS
Updating d03e270..1730abf
Fast-forward
 belajarJS.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 belajarJS.txt

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 272 bytes | 272.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/injiliatt/belajarGIT
   d03e270..1730abf  main -> main

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (main)
$ git branch belajarmidProject

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (main)
$ git checkout belajarmidProject
Switched to branch 'belajarmidProject'

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (belajarmidProject)
$ git status
On branch belajarmidProject
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        belajarmidProject.txt

nothing added to commit but untracked files present (use "git add" to track)

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (belajarmidProject)
$ git add belajarmidProject.txt

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (belajarmidProject)
$ git status
On branch belajarmidProject
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   belajarmidProject.txt


lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (belajarmidProject)
$ git commit -m "tugasmidProject"
[belajarmidProject d278782] tugasmidProject
 1 file changed, 1 insertion(+)
 create mode 100644 belajarmidProject.txt

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (belajarmidProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (main)
$ git merge belajarmidProject
Updating 1730abf..d278782
Fast-forward
 belajarmidProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 belajarmidProject.txt

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 298 bytes | 298.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/injiliatt/belajarGIT
   1730abf..d278782  main -> main

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (main)
$ git branch belajarPHP

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (main)
$ git checkout belajarPHP
Switched to branch 'belajarPHP'

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (belajarPHP)
$ git status
On branch belajarPHP
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        belajarPHP.txt

nothing added to commit but untracked files present (use "git add" to track)

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (belajarPHP)
$ git add belajarPHP.txt

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (belajarPHP)
$ git status
On branch belajarPHP
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   belajarPHP.txt


lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (belajarPHP)
$ git commit -m "tugasPHP"
[belajarPHP 6a0b041] tugasPHP
 1 file changed, 1 insertion(+)
 create mode 100644 belajarPHP.txt

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (belajarPHP)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (main)
$ git merge belajarPHP
Updating d278782..6a0b041
Fast-forward
 belajarPHP.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 belajarPHP.txt

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 270 bytes | 270.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/injiliatt/belajarGIT
   d278782..6a0b041  main -> main

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (main)
$ git branch belajarfinalProject

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (main)
$ git checkout belajarfinalProject
Switched to branch 'belajarfinalProject'

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (belajarfinalProject)
$ git status
On branch belajarfinalProject
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        belajarfinalProject.txt

nothing added to commit but untracked files present (use "git add" to track)

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (belajarfinalProject)
$ git add belajarfinalProject.txt

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (belajarfinalProject)
$ git status
On branch belajarfinalProject
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   belajarfinalProject.txt


lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (belajarfinalProject)
$ git commit -m "tugasfinalProject"
[belajarfinalProject 3f7af04] tugasfinalProject
 1 file changed, 1 insertion(+)
 create mode 100644 belajarfinalProject.txt

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (belajarfinalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (main)
$ git merge belajarfinalProject
Updating 6a0b041..3f7af04
Fast-forward
 belajarfinalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 belajarfinalProject.txt

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (main)
$ git push origin --all
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 249 bytes | 249.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/injiliatt/belajarGIT
   6a0b041..3f7af04  main -> main
 * [new branch]      belajarCSS -> belajarCSS
 * [new branch]      belajarGIT -> belajarGIT
 * [new branch]      belajarHTML -> belajarHTML
 * [new branch]      belajarJS -> belajarJS
 * [new branch]      belajarPHP -> belajarPHP
 * [new branch]      belajarfinalProject -> belajarfinalProject
 * [new branch]      belajarmidProject -> belajarmidProject

lenovo@DESKTOP-3OC8K9N MINGW64 ~/Documents/WebDev/belajarGIT (main)
$

