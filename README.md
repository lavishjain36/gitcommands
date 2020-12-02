# gitcommands
Microsoft Windows [Version 10.0.18363.1198]
(c) 2019 Microsoft Corporation. All rights reserved.

C:\Users\DELL>git config --global user.name "Lavish Jain"

C:\Users\DELL>git config --global user.email "lavishjain36@gmail.com"
warning: user.email has multiple values
error: cannot overwrite multiple values with a single value
       Use a regexp, --add or --replace-all to change user.email.

C:\Users\DELL>git config --global user.email "lavishjain36@gmail.com"
warning: user.email has multiple values
error: cannot overwrite multiple values with a single value
       Use a regexp, --add or --replace-all to change user.email.

C:\Users\DELL>e:

E:\>mkdir gitnotes

E:\>cd gitnotes

E:\gitnotes>git init
Initialized empty Git repository in E:/gitnotes/.git/

E:\gitnotes>git add *

E:\gitnotes>git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   GITHUB  KHAJANA.docx


E:\gitnotes>git commit -m "gitcommannds"
[master (root-commit) bd0b97d] gitcommannds
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 GITHUB  KHAJANA.docx

E:\gitnotes>git remote add origin https://github.com/lavishjain36/gitcommands.git

E:\gitnotes>git branch
* master

E:\gitnotes>git push origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 12.90 KiB | 4.30 MiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/lavishjain36/gitcommands/pull/new/master
remote:
To https://github.com/lavishjain36/gitcommands.git
 * [new branch]      master -> master

E:\gitnotes>git pull
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 589 bytes | 4.00 KiB/s, done.
From https://github.com/lavishjain36/gitcommands
 * [new branch]      main       -> origin/main
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=origin/<branch> master


E:\gitnotes>git branch
* master

E:\gitnotes>git config --global user.email "email@example.com"
warning: user.email has multiple values
error: cannot overwrite multiple values with a single value
       Use a regexp, --add or --replace-all to change user.email.

E:\gitnotes>
E:\gitnotes>git config --global user.email "email@example.com"
warning: user.email has multiple values
error: cannot overwrite multiple values with a single value
       Use a regexp, --add or --replace-all to change user.email.

E:\gitnotes>
E:\gitnotes>git config --global user.email "lavishjain36@gmail.com"
warning: user.email has multiple values
error: cannot overwrite multiple values with a single value
       Use a regexp, --add or --replace-all to change user.email.

E:\gitnotes>git commit --allow-empty -m "Empty commit"
[master 956a617] Empty commit

E:\gitnotes>git add *

E:\gitnotes>git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   GITHUB  KHAJANA.docx
