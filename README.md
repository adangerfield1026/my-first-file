# my-first-file
amber@Amber MINGW64 ~
$ mkdir my-local-repo

amber@Amber MINGW64 ~
$ cd my-local-repo

amber@Amber MINGW64 ~/my-local-repo
$ git init
Initialized empty Git repository in C:/Users/amber/my-local-repo/.git/

amber@Amber MINGW64 ~/my-local-repo (master)
$ echo "Hello, this is my first file." > file1.txt

amber@Amber MINGW64 ~/my-local-repo (master)
$ git add file1.txt
warning: in the working copy of 'file1.txt', LF will be replaced by CRLF the next time Git touches it

amber@Amber MINGW64 ~/my-local-repo (master)
$ git commit -m "Initial Commit: Add file1.txt"
[master (root-commit) b524142] Initial Commit: Add file1.txt
 1 file changed, 1 insertion(+)
 create mode 100644 file1.txt

amber@Amber MINGW64 ~/my-local-repo (master)
$ git remote add orgin https://github.com/adangerfield1026/my-first-file.git

amber@Amber MINGW64 ~/my-local-repo (master)
$ git branch -M main

amber@Amber MINGW64 ~/my-local-repo (main)
$ git push -u orgin main


amber@Amber MINGW64 ~/my-local-repo (main)
$ git checkout -b feature-branch
Switched to a new branch 'feature-branch'

amber@Amber MINGW64 ~/my-local-repo (feature-branch)
$ echo "This is a new file feature." >file2.txt

amber@Amber MINGW64 ~/my-local-repo (feature-branch)
$ git add file2.txt
warning: in the working copy of 'file2.txt', LF will be replaced by CRLF the next time Git touches it

amber@Amber MINGW64 ~/my-local-repo (feature-branch)
$ git commit -m "Add file2.txt in feature-branch
> ^C

amber@Amber MINGW64 ~/my-local-repo (feature-branch)
$ Git commit -m "Add file2.txt in feature-branch"
[feature-branch a6fbd6b] Add file2.txt in feature-branch
 1 file changed, 1 insertion(+)
 create mode 100644 file2.txt

amber@Amber MINGW64 ~/my-local-repo (feature-branch)
$ git push -u orgin feature-branch


amber@Amber MINGW64 ~/my-local-repo (feature-branch)
$ git remote add orgin https://github.com/adangerfield1026/my-first-file.git
error: remote orgin already exists.

amber@Amber MINGW64 ~/my-local-repo (feature-branch)
$ Git push -u orgin feature-branch
