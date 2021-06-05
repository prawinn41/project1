# project1

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo
$ pwd
/c/Users/Praveen/Desktop/git_repo

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo
$ ls

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo
$ ls -lt
total 0

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo
$ git --version
git version 2.31.1.windows.1

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo
$ git status
fatal: not a git repository (or any of the parent directories): .git

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo
$ git init
Initialized empty Git repository in C:/Users/Praveen/Desktop/git_repo/.git/

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo (master)
$ ls

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo (master)
$ ls -lt
total 0

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo (master)
$ ls-a
bash: ls-a: command not found

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo (master)
$ ls -a
./  ../  .git/

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo (master)
$ ls -la
total 68
drwxr-xr-x 1 Praveen 197121 0 Jun  5 12:36 ./
drwxr-xr-x 1 Praveen 197121 0 Jun  5 12:30 ../
drwxr-xr-x 1 Praveen 197121 0 Jun  5 12:36 .git/

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo (master)
$ git config --global user.name "Prawinn"

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo (master)
$ git config --list
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
credential.helper=manager-core
pull.rebase=false
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
user.name=Prawinn
core.repositoryformatversion=0
core.filemode=false
core.bare=false
core.logallrefupdates=true
core.symlinks=false
core.ignorecase=true

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo (master)
$ git config --global user.name "Prawinn.41"

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo (master)
$ git config --list
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
credential.helper=manager-core
pull.rebase=false
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
user.name=Prawinn.41
core.repositoryformatversion=0
core.filemode=false
core.bare=false
core.logallrefupdates=true
core.symlinks=false
core.ignorecase=true

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo (master)
$ git config --global user.email "Prawinn.41@gmail.com"

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo (master)
$ git config --list
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
credential.helper=manager-core
pull.rebase=false
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
user.name=Prawinn.41
user.email=Prawinn.41@gmail.com
core.repositoryformatversion=0
core.filemode=false
core.bare=false
core.logallrefupdates=true
core.symlinks=false
core.ignorecase=true

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo (master)
$ touch file.txt

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo (master)
$ ls
file.txt

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo (master)
$ ls -lt
total 0
-rw-r--r-- 1 Praveen 197121 0 Jun  5 13:02 file.txt

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        file.txt

nothing added to commit but untracked files present (use "git add" to track)

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo (master)
$ git add file.txt

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   file.txt


Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo (master)
$ git commit -m "1st commit"
[master (root-commit) c74dd6b] 1st commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 file.txt

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo (master)
$ git status
On branch master
nothing to commit, working tree clean

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo (master)
$ git log
commit c74dd6bfbddcaf15ffbfff058fdb37685024875f (HEAD -> master)
Author: Prawinn.41 <Prawinn.41@gmail.com>
Date:   Sat Jun 5 13:05:48 2021 +0200

    1st commit

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo (master)
$ git status
On branch master
nothing to commit, working tree clean

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo (master)
$ touch f1 f2 f3

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo (master)
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        f1
        f2
        f3

nothing added to commit but untracked files present (use "git add" to track)

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo (master)
$ git add f1 f2

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   f1
        new file:   f2

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        f3


Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo (master)
$

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo (master)
$ git add.
git: 'add.' is not a git command. See 'git --help'.

The most similar command is
        add

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo (master)
$ git add .

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   f1
        new file:   f2
        new file:   f3


Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo (master)
$ git commit -m "f3 and f4 files"
[master 2708869] f3 and f4 files
 3 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 f1
 create mode 100644 f2
 create mode 100644 f3

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo (master)
$ git status
On branch master
nothing to commit, working tree clean

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo (master)
$ git log
commit 2708869d1adfee915c67afe86b806103146465ac (HEAD -> master)
Author: Prawinn.41 <Prawinn.41@gmail.com>
Date:   Sat Jun 5 13:22:59 2021 +0200

    f3 and f4 files

commit c74dd6bfbddcaf15ffbfff058fdb37685024875f
Author: Prawinn.41 <Prawinn.41@gmail.com>
Date:   Sat Jun 5 13:05:48 2021 +0200

    1st commit

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo (master)
$ git show
commit 2708869d1adfee915c67afe86b806103146465ac (HEAD -> master)
Author: Prawinn.41 <Prawinn.41@gmail.com>
Date:   Sat Jun 5 13:22:59 2021 +0200

    f3 and f4 files

diff --git a/f1 b/f1
new file mode 100644
index 0000000..e69de29
diff --git a/f2 b/f2
new file mode 100644
index 0000000..e69de29
diff --git a/f3 b/f3
new file mode 100644
index 0000000..e69de29

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo (master)
$ git clone https://github.com/prawinn41/logistic_regression_ml.git
Cloning into 'logistic_regression_ml'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), 3.74 MiB | 1.08 MiB/s, done.

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo (master)
$ ls
f1  f2  f3  file.txt  logistic_regression_ml/

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo (master)
$ cd logistic_regression_ml

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo/logistic_regression_ml (main)
$ pwd
/c/Users/Praveen/Desktop/git_repo/logistic_regression_ml

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo/logistic_regression_ml (main)
$ ls
'Logistic-regression_final (2) (1).zip'   README.md

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo/logistic_regression_ml (main)
$ ls -lt
total 3829
-rw-r--r-- 1 Praveen 197121      26 Jun  5 14:06  README.md
-rw-r--r-- 1 Praveen 197121 3917161 Jun  5 14:06 'Logistic-regression_final (2) (1).zip'

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo/logistic_regression_ml (main)
$ ls -la
total 3841
drwxr-xr-x 1 Praveen 197121       0 Jun  5 14:06  ./
drwxr-xr-x 1 Praveen 197121       0 Jun  5 14:06  ../
drwxr-xr-x 1 Praveen 197121       0 Jun  5 14:06  .git/
-rw-r--r-- 1 Praveen 197121 3917161 Jun  5 14:06 'Logistic-regression_final (2) (1).zip'
-rw-r--r-- 1 Praveen 197121      26 Jun  5 14:06  README.md

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo/logistic_regression_ml (main)
$ touch file1 file2 file3

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo/logistic_regression_ml (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        file1
        file2
        file3

nothing added to commit but untracked files present (use "git add" to track)

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo/logistic_regression_ml (main)
$ git add .

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo/logistic_regression_ml (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   file1
        new file:   file2
        new file:   file3


Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo/logistic_regression_ml (main)
$ git commit -m "githum cmt"
[main f1243ed] githum cmt
 3 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 file1
 create mode 100644 file2
 create mode 100644 file3

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo/logistic_regression_ml (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo/logistic_regression_ml (main)
$ git log
commit f1243ed3a591b7ab7d4ef844475768c1de6907a2 (HEAD -> main)
Author: Prawinn.41 <Prawinn.41@gmail.com>
Date:   Sat Jun 5 17:06:17 2021 +0200

    githum cmt

commit e5b1a49c7b6f2de2eb2acbf5a03482b0f3b2b8e8 (origin/main, origin/HEAD)
Author: PRAWINN <69505940+prawinn41@users.noreply.github.com>
Date:   Sat Jun 5 11:20:58 2021 +0200

    Add files via upload

commit b015822159f3b230d5a211779d03c5e19d800ec8
Author: PRAWINN <69505940+prawinn41@users.noreply.github.com>
Date:   Sat Jun 5 11:09:08 2021 +0200

    Create README.md

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo/logistic_regression_ml (main)
$ git push
fatal: unable to access 'https://github.com/prawinn41/logistic_regression_ml.git/': Could not resolve host: github.com

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo/logistic_regression_ml (main)
$ git push
fatal: An error occurred while sending the request.
fatal: The request was aborted: Could not create SSL/TLS secure channel.
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 339 bytes | 339.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/prawinn41/logistic_regression_ml.git
   e5b1a49..f1243ed  main -> main

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo/logistic_regression_ml (main)
$ git log
commit f1243ed3a591b7ab7d4ef844475768c1de6907a2 (HEAD -> main, origin/main, origin/HEAD)
Author: Prawinn.41 <Prawinn.41@gmail.com>
Date:   Sat Jun 5 17:06:17 2021 +0200

    githum cmt

commit e5b1a49c7b6f2de2eb2acbf5a03482b0f3b2b8e8
Author: PRAWINN <69505940+prawinn41@users.noreply.github.com>
Date:   Sat Jun 5 11:20:58 2021 +0200

    Add files via upload

commit b015822159f3b230d5a211779d03c5e19d800ec8
Author: PRAWINN <69505940+prawinn41@users.noreply.github.com>
Date:   Sat Jun 5 11:09:08 2021 +0200

    Create README.md

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo/logistic_regression_ml (main)
$ git show
commit f1243ed3a591b7ab7d4ef844475768c1de6907a2 (HEAD -> main, origin/main, origin/HEAD)
Author: Prawinn.41 <Prawinn.41@gmail.com>
Date:   Sat Jun 5 17:06:17 2021 +0200

    githum cmt

diff --git a/file1 b/file1
new file mode 100644
index 0000000..e69de29
diff --git a/file2 b/file2
new file mode 100644
index 0000000..e69de29
diff --git a/file3 b/file3
new file mode 100644
index 0000000..e69de29

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo/logistic_regression_ml (main)
$ git show
commit f1243ed3a591b7ab7d4ef844475768c1de6907a2 (HEAD -> main, origin/main, origin/HEAD)
Author: Prawinn.41 <Prawinn.41@gmail.com>
Date:   Sat Jun 5 17:06:17 2021 +0200

    githum cmt

diff --git a/file1 b/file1
new file mode 100644
index 0000000..e69de29
diff --git a/file2 b/file2
new file mode 100644
index 0000000..e69de29
diff --git a/file3 b/file3
new file mode 100644
index 0000000..e69de29

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo/logistic_regression_ml (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo/logistic_regression_ml (main)
$ touch file4

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo/logistic_regression_ml (main)
$ git add .

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo/logistic_regression_ml (main)
$ git commit -m "2nd cmt"
[main 61e3c8d] 2nd cmt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 file4

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo/logistic_regression_ml (main)
$ git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 252 bytes | 252.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/prawinn41/logistic_regression_ml.git
   f1243ed..61e3c8d  main -> main

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo/logistic_regression_ml (main)
$ git log --online
fatal: unrecognized argument: --online

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo/logistic_regression_ml (main)
$ git log --oneline
61e3c8d (HEAD -> main, origin/main, origin/HEAD) 2nd cmt
f1243ed githum cmt
e5b1a49 Add files via upload
b015822 Create README.md

Praveen@Praveen-TOSH MINGW64 ~/Desktop/git_repo/logistic_regression_ml (main)
$ git log
commit 61e3c8d00fb51c2b009ae5dc9d7a65c0812a677a (HEAD -> main, origin/main, origin/HEAD)
Author: Prawinn.41 <Prawinn.41@gmail.com>
Date:   Sat Jun 5 18:25:36 2021 +0200

    2nd cmt

commit f1243ed3a591b7ab7d4ef844475768c1de6907a2
Author: Prawinn.41 <Prawinn.41@gmail.com>
Date:   Sat Jun 5 17:06:17 2021 +0200

    githum cmt

commit e5b1a49c7b6f2de2eb2acbf5a03482b0f3b2b8e8
Author: PRAWINN <69505940+prawinn41@users.noreply.github.com>
Date:   Sat Jun 5 11:20:58 2021 +0200

    Add files via upload

commit b015822159f3b230d5a211779d03c5e19d800ec8
Author: PRAWINN <69505940+prawinn41@users.noreply.github.com>
Date:   Sat Jun 5 11:09:08 2021 +0200

    Create README.md
 ESCOC
in/HEAD)
>




e6907a2
>




3b2b8e8
s.noreply.github.com>




d800ec8
s.noreply.github.com>



 ESCOD
in/HEAD)
Author: Prawinn.41 <Prawinn.41@gmail.com>
Date:   Sat Jun 5 18:25:36 2021 +0200

    2nd cmt

commit f1243ed3a591b7ab7d4ef844475768c1de6907a2
Author: Prawinn.41 <Prawinn.41@gmail.com>
Date:   Sat Jun 5 17:06:17 2021 +0200

    githum cmt

commit e5b1a49c7b6f2de2eb2acbf5a03482b0f3b2b8e8
Author: PRAWINN <69505940+prawinn41@users.noreply.github.com>
Date:   Sat Jun 5 11:20:58 2021 +0200

    Add files via upload

commit b015822159f3b230d5a211779d03c5e19d800ec8
Author: PRAWINN <69505940+prawinn41@users.noreply.github.com>
Date:   Sat Jun 5 11:09:08 2021 +0200

    Create README.md
(END)
in/HEAD)
Author: Prawinn.41 <Prawinn.41@gmail.com>
Date:   Sat Jun 5 18:25:36 2021 +0200

    2nd cmt

commit f1243ed3a591b7ab7d4ef844475768c1de6907a2
Author: Prawinn.41 <Prawinn.41@gmail.com>
Date:   Sat Jun 5 17:06:17 2021 +0200

    githum cmt

commit e5b1a49c7b6f2de2eb2acbf5a03482b0f3b2b8e8
Author: PRAWINN <69505940+prawinn41@users.noreply.github.com>
Date:   Sat Jun 5 11:20:58 2021 +0200

    Add files via upload

commit b015822159f3b230d5a211779d03c5e19d800ec8
Author: PRAWINN <69505940+prawinn41@users.noreply.github.com>
Date:   Sat Jun 5 11:09:08 2021 +0200

    Create README.md
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
(END)

