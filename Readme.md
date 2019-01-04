# Hello wolrd

computer@computer-PC MINGW64 /c/AGitLearning/Learning
$ git init Demoapp
Reinitialized existing Git repository in C:/AGitLearning/Learning/Demoapp/.git/

computer@computer-PC MINGW64 /c/AGitLearning/Learning
$ cd Demoapp/

computer@computer-PC MINGW64 /c/AGitLearning/Learning/Demoapp (master)
$ ls -la
total 4
drwxr-xr-x 1 computer 197121 0 Jan  3 17:01 ./
drwxr-xr-x 1 computer 197121 0 Jan  3 17:01 ../
drwxr-xr-x 1 computer 197121 0 Jan  4 10:23 .git/

computer@computer-PC MINGW64 /c/AGitLearning/Learning/Demoapp (master)
$ git status
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)

computer@computer-PC MINGW64 /c/AGitLearning/Learning/Demoapp (master)
$ notepad ++ Readme.md

computer@computer-PC MINGW64 /c/AGitLearning/Learning/Demoapp (master)
$ notepad++ Readme.md
error: C:\Users\computer\AppData\Roaming\Notepad++\plugins\Config\Hunspell\en_US.usr: cannot open

computer@computer-PC MINGW64 /c/AGitLearning/Learning/Demoapp (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        Readme.md

nothing added to commit but untracked files present (use "git add" to track)

computer@computer-PC MINGW64 /c/AGitLearning/Learning/Demoapp (master)
$ git add readme.md

computer@computer-PC MINGW64 /c/AGitLearning/Learning/Demoapp (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        Readme.md

nothing added to commit but untracked files present (use "git add" to track)

computer@computer-PC MINGW64 /c/AGitLearning/Learning/Demoapp (master)
$ git add Readme.md

computer@computer-PC MINGW64 /c/AGitLearning/Learning/Demoapp (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   Readme.md


computer@computer-PC MINGW64 /c/AGitLearning/Learning/Demoapp (master)
$ git commit -m "Initial Commit"
[master (root-commit) 4391f2d] Initial Commit
 1 file changed, 1 insertion(+)
 create mode 100644 Readme.md

computer@computer-PC MINGW64 /c/AGitLearning/Learning/Demoapp (master)
$ git status
On branch master
nothing to commit, working tree clean

computer@computer-PC MINGW64 /c/AGitLearning/Learning/Demoapp (master)
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)

        Readme - Copy - Copy.md
        Readme - Copy.md

nothing added to commit but untracked files present (use "git add" to track)

computer@computer-PC MINGW64 /c/AGitLearning/Learning/Demoapp (master)
$ git add .

computer@computer-PC MINGW64 /c/AGitLearning/Learning/Demoapp (master)
$ git status
On branch master
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        new file:   Readme - Copy - Copy.md
        new file:   Readme - Copy.md


computer@computer-PC MINGW64 /c/AGitLearning/Learning/Demoapp (master)
$ git commit
Aborting commit due to empty commit message.

computer@computer-PC MINGW64 /c/AGitLearning/Learning/Demoapp (master)
$ git commit -m "new files added"
[master aa4c838] new files added
 2 files changed, 2 insertions(+)
 create mode 100644 Readme - Copy - Copy.md
 create mode 100644 Readme - Copy.md

computer@computer-PC MINGW64 /c/AGitLearning/Learning/Demoapp (master)
$ git commit
On branch master
nothing to commit, working tree clean

computer@computer-PC MINGW64 /c/AGitLearning/Learning/Demoapp (master)
$
