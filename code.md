```bash

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (master)
$ git init
Initialized empty Git repository in C:/Users/liangqianxing/Desktop/软件工程基础/
.git/

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (master)
$ git clone git@github.com:liangqianxing/-Flask-.git
fatal: destination path '-Flask-' already exists and is not an empty directory.

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (master)
$ git clone git@github.com:liangqianxing/-Flask-.git
Cloning into '-Flask-'...
remote: Enumerating objects: 8, done.
remote: Counting objects: 100% (8/8), done.
remote: Compressing objects: 100% (7/7), done.
remote: Total 8 (delta 0), reused 4 (delta 0), pack-reused 0
Receiving objects: 100% (8/8), done.

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (master)
$ git push -u origin "master"
error: src refspec master does not match any
error: failed to push some refs to 'origin'

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (master)
$ git push -u origin master
error: src refspec master does not match any
error: failed to push some refs to 'origin'

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (master)
$ git push -u origin master
error: src refspec master does not match any
error: failed to push some refs to 'origin'

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (master)
$ git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Turn this message off by running
hint: "git config advice.addEmptyPathspec false"

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (master)
$ git add .
warning: adding embedded git repository: -Flask-
hint: You've added another git repository inside your current repository.
hint: Clones of the outer repository will not contain the contents of
hint: the embedded repository and will not know how to obtain it.
hint: If you meant to add a submodule, use:
hint:
hint:   git submodule add <url> -Flask-
hint:
hint: If you added this path by mistake, you can remove it from the
hint: index with:
hint:
hint:   git rm --cached -Flask-
hint:
hint: See "git help submodule" for more information.

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (master)
$ git commit -m "submit"
[master (root-commit) 7ef77fa] submit
 1 file changed, 1 insertion(+)
 create mode 160000 -Flask-

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (master)
$ git remote add origin git@github.com:liangqianxing/-Flask-.git

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (master)
$ git push -u origin master
To github.com:liangqianxing/-Flask-.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'github.com:liangqianxing/-Flask-.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (master)
$ ^C

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (master)
$ git pull --rebase origin master
remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 4 (delta 0), reused 4 (delta 0), pack-reused 0
Unpacking objects: 100% (4/4), 1.10 KiB | 70.00 KiB/s, done.
From github.com:liangqianxing/-Flask-
 * branch            master     -> FETCH_HEAD
 * [new branch]      master     -> origin/master
warning: unable to rmdir '-Flask-': Directory not empty
Successfully rebased and updated refs/heads/master.

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (master)
$ git push -u origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 301 bytes | 301.00 KiB/s, done.
Total 2 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:liangqianxing/-Flask-.git
   6ee0d7d..7f5d125  master -> master
branch 'master' set up to track 'origin/master'.

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (master)
$ git branch newbrance

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (master)
$ git brance
git: 'brance' is not a git command. See 'git --help'.

The most similar command is
        branch

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (master)
$ git branch
* master
  newbrance

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (master)
$ git checkout newbrance
Switched to branch 'newbrance'

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (newbrance)
$ git add .

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (newbrance)
$ git commit -m "add a markdown file"
[newbrance 810263c] add a markdown file
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 test.md

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (newbrance)
$ git merge newbranch
merge: newbranch - not something we can merge

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (newbrance)
$ git merge newbrance
Already up to date.

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (newbrance)
$ git diff

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (newbrance)
$ git push -u origin master
Everything up-to-date
branch 'master' set up to track 'origin/master'.

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (newbrance)
$ git branch -D newbrance
error: Cannot delete branch 'newbrance' checked out at 'C:/Users/liangqianxing/Desktop/软件工程基础'

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (newbrance)
$ git branch
  master
* newbrance

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (newbrance)
$ git branch -D newbrance
error: Cannot delete branch 'newbrance' checked out at 'C:/Users/liangqianxing/Desktop/软件工程基础'

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (newbrance)
$ ^C

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (newbrance)
$ git checkout master
Switched to branch 'master'
D       -Flask-
Your branch is up to date with 'origin/master'.

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (master)
$ git branch -D newbrance
Deleted branch newbrance (was 810263c).

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (master)
$ git branch now

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (master)
$ git checkout now
Switched to branch 'now'
D       -Flask-

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (now)
$ git add .

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (now)
$ git commit "提交md文件测试"
error: pathspec '提交md文件测试' did not match any file(s) known to git

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (now)
$ git commit -m "提交md文件测试"
[now 38394e1] 提交md文件测试
 2 files changed, 2 insertions(+), 1 deletion(-)
 delete mode 160000 -Flask-
 create mode 100644 test.md

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (now)
$ git push -u origin master
Everything up-to-date
branch 'master' set up to track 'origin/master'.

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (now)
$ git switch master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (master)
$ git branch -D now
Deleted branch now (was 38394e1).

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (master)
$ git branch now

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (master)
$ git checkout now
Switched to branch 'now'
D       -Flask-

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (now)
$ git push -u origin now
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'now' on GitHub by visiting:
remote:      https://github.com/liangqianxing/-Flask-/pull/new/now
remote:
To github.com:liangqianxing/-Flask-.git
 * [new branch]      now -> now
branch 'now' set up to track 'origin/now'.

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (now)
$ git add .

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (now)
$ git push -u origin now
Everything up-to-date
branch 'now' set up to track 'origin/now'.

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (now)
$ git commit -m "test"
[now 99fb408] test
 2 files changed, 1 deletion(-)
 delete mode 160000 -Flask-
 create mode 100644 test.md

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (now)
$ git checkout master
error: Your local changes to the following files would be overwritten by checkout:
        test.md
Please commit your changes or stash them before you switch branches.
Aborting

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (now)
$ git commit -m "markdown"
On branch now
Your branch is ahead of 'origin/now' by 1 commit.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   test.md

no changes added to commit (use "git add" and/or "git commit -a")

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (now)
$ git push -u origin now
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 299 bytes | 299.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:liangqianxing/-Flask-.git
   7f5d125..99fb408  now -> now
branch 'now' set up to track 'origin/now'.

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (now)
$ git checkout master
error: Your local changes to the following files would be overwritten by checkout:
        test.md
Please commit your changes or stash them before you switch branches.
Aborting

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (now)
$ ^C

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (now)
$ git add .

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (now)
$ git commit -m "
> etet"
[now b4a1834] etet
 1 file changed, 1 insertion(+)

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (now)
$ git commit -m "etet"
On branch now
Your branch is ahead of 'origin/now' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (now)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 250 bytes | 250.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To github.com:liangqianxing/-Flask-.git
   99fb408..b4a1834  now -> now

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (now)
$ git push -u origin now
Everything up-to-date
branch 'now' set up to track 'origin/now'.

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (now)
$ git branch -D now
error: Cannot delete branch 'now' checked out at 'C:/Users/liangqianxing/Desktop/软件工程基础'

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (now)
$ git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (master)
$ git branch -D now
Deleted branch now (was b4a1834).

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (master)
$ git push
Everything up-to-date

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (master)
$ git branch
* master

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (master)
$ git pull
remote: Enumerating objects: 7, done.
remote: Counting objects: 100% (7/7), done.
remote: Compressing objects: 100% (6/6), done.
remote: Total 7 (delta 0), reused 4 (delta 0), pack-reused 0
Unpacking objects: 100% (7/7), 2.68 KiB | 228.00 KiB/s, done.
From github.com:liangqianxing/-Flask-
 * [new branch]      main       -> origin/main
Already up to date.

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (master)
$ git push
Everything up-to-date

liangqianxing@SDUST-slient MINGW64 ~/Desktop/软件工程基础 (master)
$

```

