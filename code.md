```bash

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (master)
$ git init
Initialized empty Git repository in C:/Users/liangqianxing/Desktop/软件工程基础/.git/


liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (master)
$ git clone git@github.com:liangqianxing/-Flask-.git
Cloning into '-Flask-'...
remote: Enumerating objects: 10, done.
remote: Counting objects: 100% (10/10), done.
remote: Compressing objects: 100% (9/9), done.
remote: Total 10 (delta 0), reused 7 (delta 0), pack-reused 0
Receiving objects: 100% (10/10), done.

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (master)
$ cd -Flask-
bash: cd: -F: invalid option
cd: usage: cd [-L|[-P [-e]] [-@]] [dir]

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (master)
$ git clone \git@github.com:liangqianxing/Flask.git
Cloning into 'Flask'...
remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (4/4), done.

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (master)
$ cd Flask

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础/Flask (main)
$ git pull
Already up to date.

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础/Flask (main)
$ git add .

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础/Flask (main)
$ git commit -m "test"
[main e8e4881] test
 1 file changed, 364 insertions(+)
 create mode 100644 code.md

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础/Flask (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 2.70 KiB | 2.70 MiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:liangqianxing/Flask.git
   a11ad84..e8e4881  main -> main

```

