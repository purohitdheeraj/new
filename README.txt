hello git

 ~/Desktop/new (master)
$ git init
Reinitialized existing Git repository in C:/Users/Dinesh Purohit/Desktop/new/.git/

~/Desktop/new (master)
$ echo "hello git" >> README.txt

~/Desktop/new (master)
$ git add README.txt
warning: LF will be replaced by CRLF in README.txt.
The file will have its original line endings in your working directory

~/Desktop/new (master)
$ git add first

 ~/Desktop/new (master)
$ git commit -m "first comit"
[master (root-commit) e512fdc] first comit
 1 file changed, 1 insertion(+)
 create mode 100644 README.txt

~/Desktop/new (master)
$ git status
On branch master
nothing to commit, working tree clean

 ~/Desktop/new (master)
$ git remote add origin https://github.com/purohitdheeraj/new.git
 ~/Desktop/new (master)

$ git push -u origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 223 bytes | 223.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/purohitdheeraj/new.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.

 ~/Desktop/new (master)
$ cd first
 ~/Desktop/new/first (master)
$ echo "hello world!" >> hello.txt

~/Desktop/new/first (master)
$ add hello.txt
bash: add: command not found

~/Desktop/new/first (master)
$ git add hello.txt
warning: LF will be replaced by CRLF in first/hello.txt.
The file will have its original line endings in your working directory

 ~/Desktop/new/first (master)
$ git commit -m "hello world"
[master 7d0ae4b] hello world
 1 file changed, 1 insertion(+)
 create mode 100644 first/hello.txt

~/Desktop/new/first (master)
$ git push -u origin master
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (4/4), 337 bytes | 168.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0)
To https://github.com/purohitdheeraj/new.git
   e512fdc..7d0ae4b  master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.

 ~/Desktop/new/first (master)
$
