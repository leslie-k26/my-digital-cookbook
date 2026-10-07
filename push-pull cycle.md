Windows PowerShell
Copyright (C) Microsoft Corporation. All rights reserved.

PS C:\Users\hlinh> git --version
git version 2.53.0.windows.2
PS C:\Users\hlinh> git --list
unknown option: --list
usage: git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--no-lazy-fetch]
           [--no-optional-locks] [--no-advice] [--bare] [--git-dir=<path>]
           [--work-tree=<path>] [--namespace=<name>] [--config-env=<name>=<envvar>]
           <command> [<args>]
PS C:\Users\hlinh> git config --list
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=schannel
core.autocrlf=input
core.fscache=true
core.symlinks=false
core.editor="C:\\Program Files\\Notepad++\\notepad++.exe" -multiInst -notabbar -nosession -noPlugin
pull.rebase=false
credential.helper=manager
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
user.email=zennie.3h@gmail.com
user.name=Linh
diff.guitool=vscode
difftool.vscode.path=C:/Users/hlinh/AppData/Local/Programs/Microsoft VS Code/Code.exe
difftool.vscode.cmd="C:/Users/hlinh/AppData/Local/Programs/Microsoft VS Code/Code.exe" --new-window --wait --diff "$LOCAL" "$REMOTE"
merge.guitool=vscode
mergetool.vscode.path=C:/Users/hlinh/AppData/Local/Programs/Microsoft VS Code/Code.exe
mergetool.vscode.cmd="C:/Users/hlinh/AppData/Local/Programs/Microsoft VS Code/Code.exe" --new-window --wait --merge "$REMOTE" "$LOCAL" "$BASE" "$MERGED"
PS C:\Users\hlinh> git config --global user.name
Linh
PS C:\Users\hlinh> cd D:\Dev\seneca\cep146\
PS D:\Dev\seneca\cep146> git config --global user.name
Linh
PS D:\Dev\seneca\cep146> git config --global user.name "Leslie Nguyen"
PS D:\Dev\seneca\cep146> git config --global user.name
Leslie Nguyen
PS D:\Dev\seneca\cep146> git config --global user.email
zennie.3h@gmail.com
PS D:\Dev\seneca\cep146> git config --global user.email "hlnguyen6@myseneca.ca"
PS D:\Dev\seneca\cep146> ls


    Directory: D:\Dev\seneca\cep146


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        2026-09-30  12:48 PM                labs
d-----        2026-09-09  11:22 PM                project
-a----        2026-09-09  11:22 PM           2058 addenda.md
-a----        2026-09-09  11:22 PM           2212 GIt_Command_Terms.md
-a----        2026-09-09  11:22 PM            919 README.md
-a----        2026-09-09  11:22 PM           3522 Setup_IDE.md


PS D:\Dev\seneca\cep146> cd labs
PS D:\Dev\seneca\cep146\labs> ls


    Directory: D:\Dev\seneca\cep146\labs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        2026-09-23   2:51 PM                cep146-lab3
d-----        2026-09-09   7:56 PM                lab0
d-----        2026-09-09  11:32 PM                lab1
d-----        2026-09-30   6:24 PM                lab2
d-----        2026-09-23   2:44 PM                lab3
d-----        2026-09-30   6:22 PM                lab4
-a----        2026-09-09  11:22 PM           3688 lab-00.md
-a----        2026-09-09  11:22 PM           3600 lab-01.md
-a----        2026-09-09  11:22 PM           3896 lab-02.md
-a----        2026-09-09  11:22 PM           5722 lab-03.md
-a----        2026-09-09  11:22 PM           3154 lab-04a.md
-a----        2026-09-09  11:22 PM          16083 lab-04b.md
-a----        2026-09-09  11:22 PM          13199 lab-05.md
-a----        2026-09-09  11:22 PM           5049 lab-06.md
-a----        2026-09-09  11:22 PM          11692 lab-07.md
-a----        2026-09-09  11:22 PM           7420 lab-08.md
-a----        2026-09-09  11:22 PM           5038 lab-09.md
-a----        2026-09-09  11:22 PM           4413 lab-10.md
-a----        2026-09-09  11:22 PM           8393 lab-11.md
-a----        2026-09-09  11:22 PM           6340 lab-12.md


PS D:\Dev\seneca\cep146\labs> cd ../
PS D:\Dev\seneca\cep146> cd ../
PS D:\Dev\seneca> ls


    Directory: D:\Dev\seneca


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        2026-09-16  10:20 AM                aps145
d-----        2026-09-30   6:23 PM                cep146
d-----        2026-10-07   1:25 PM                cep146-stuff
d-----        2026-10-06  11:43 PM                Computer System Overview _ Essential Tooling for
                                                  Programmers,Essential Git Commands and Workflo[...]
d-----        2026-09-29  11:48 AM                ipc144
d-----        2026-09-30   8:22 PM                ops102
-a----        2026-10-06   2:35 PM           4043 cep-group-taskmd.md
-a----        2026-09-15  11:08 PM           1004 Mon.txt
-a----        2026-09-15   5:19 PM           1644 OPS102 Labs are due on Friday at 17.txt
-a----        2026-09-15  10:10 PM           9869 To-do List (Sem 1).txt


PS D:\Dev\seneca> cd .\cep146-stuff\lab05\
PS D:\Dev\seneca\cep146-stuff\lab05> mkdir my-digital-cookbook


    Directory: D:\Dev\seneca\cep146-stuff\lab05


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        2026-10-07   1:26 PM                my-digital-cookbook


PS D:\Dev\seneca\cep146-stuff\lab05> cd .\my-digital-cookbook\
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> git init
Initialized empty Git repository in D:/Dev/seneca/cep146-stuff/lab05/my-digital-cookbook/.git/
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> echo "# My Digital Cookbook" > README.md
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> echo "## Spaghetti Carbonara" > carbonara.md
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> echo "**Prep Time:** 15 minutes" >> carbonara.md
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> echo "**Ingredients:** pasta, eggs, bacon, parmesan cheese" >> carbonara.md
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> git add.
git: 'add.' is not a git command. See 'git --help'.

The most similar command is
        add
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> git add .
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> git remote -v
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> ls -la

Get-ChildItem : A parameter cannot be found that matches
parameter name 'la'.
At line:1 char:4
+ ls -la
+    ~~~
    + CategoryInfo          : InvalidArgument: (:) [Get-Child
   Item], ParameterBindingException
    + FullyQualifiedErrorId : NamedParameterNotFound,Microsof
   t.PowerShell.Commands.GetChildItemCommand

PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> ls -la

Get-ChildItem : A parameter cannot be found that matches
parameter name 'la'.
At line:1 char:4
+ ls -la
+    ~~~
    + CategoryInfo          : InvalidArgument: (:) [Get-Child
   Item], ParameterBindingException
    + FullyQualifiedErrorId : NamedParameterNotFound,Microsof
   t.PowerShell.Commands.GetChildItemCommand

PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> ls -l
Get-ChildItem : Missing an argument for parameter
'LiteralPath'. Specify a parameter of type 'System.String[]'
and try again.
At line:1 char:4
+ ls -l
+    ~~
    + CategoryInfo          : InvalidArgument: (:) [Get-Child
   Item], ParameterBindingException
    + FullyQualifiedErrorId : MissingArgument,Microsoft.Power
   Shell.Commands.GetChildItemCommand

PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> ls


    Directory:
    D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        2026-10-07   1:28 PM            212 carbonara.md
-a----        2026-10-07   1:27 PM             48 README.md


PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> git config --get remote.origin.url
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
        new file:   carbonara.md

PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> git commit -m "Initial commit: AddREADME and carbonara recipe"
[master (root-commit) 7a6f0b7] Initial commit: Add README and carbonara recipe
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md
 create mode 100644 carbonara.md
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> git log --oneline
7a6f0b7 (HEAD -> master) Initial commit: Add README and carbonara recipe
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> cat README.md
# My Digital Cookbook
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> cat .\carbonara.md
## Spaghetti Carbonara
**Prep Time:** 15 minutes
**Ingredients:** pasta, eggs, bacon, parmesan cheese
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> git checkout -b add-desserts
Switched to a new branch 'add-desserts'
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> git branch
* add-desserts
  master
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> echo "## Chocolate Chip Cookies" >cookies.md
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> echo "**Prep Time:** 20 minutes" >> cookies.md
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> echo "**Bake Time:** 12 minutes" >> cookies.md
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> echo "**Ingredients:** flour, sugar, butter, chocolate chips, eggs" >> cookies.md
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> cat cookies.md
## Chocolate Chip Cookies
**Prep Time:** 20 minutes
**Bake Time:** 12 minutes
**Ingredients:** flour, sugar, butter, chocolate chips, eggs
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> git add cookies.md
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> git commit -m "Add chocolate chip cookies recipe"
[add-desserts ffac43c] Add chocolate chip cookies recipe
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 cookies.md
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> git log --oneline
ffac43c (HEAD -> add-desserts) Add chocolate chip cookies recipe
7a6f0b7 (master) Initial commit: Add README and carbonara recipe
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> git checkout main
error: pathspec 'main' did not match any file(s) known to git
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> git checkout -b add-appetizers
Switched to a new branch 'add-appetizers'
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> git branch
* add-appetizers
  add-desserts
  master
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> echo "## Bruschetta" > bruschetta.md
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> echo "**Prep Time:** 15 minutes" >> bruschetta.md
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> echo "**Ingredients:** bread, tomatoes, garlic, basil, olive oil" >> bruschetta.md
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> git add bruschetta.md
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> git commit -m "Add bruschetta appetizer recipe"
[add-appetizers 6742d7c] Add bruschetta appetizer recipe
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 bruschetta.md
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> cat bruschetta.md
## Bruschetta
**Prep Time:** 15 minutes
**Ingredients:** bread, tomatoes, garlic, basil, olive oil
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> git checkout master
Switched to branch 'master'
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> git merge add-desserts
Updating 7a6f0b7..ffac43c
Fast-forward
 cookies.md | Bin 0 -> 288 bytes
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 cookies.md
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> git merge add-appetizers
Updating ffac43c..6742d7c
Fast-forward
 bruschetta.md | Bin 0 -> 206 bytes
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 bruschetta.md
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> ls


    Directory: D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        2026-10-07   1:41 PM            206 bruschetta.md
-a----        2026-10-07   1:28 PM            212 carbonara.md
-a----        2026-10-07   1:41 PM            288 cookies.md
-a----        2026-10-07   1:27 PM             48 README.md


PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> git log --oneline --graph
* 6742d7c (HEAD -> master, add-appetizers) Add bruschetta appetizer recipe
* ffac43c (add-desserts) Add chocolate chip cookies recipe
* 7a6f0b7 Initial commit: Add README and carbonara recipe
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> git branch -d add-desserts
Deleted branch add-desserts (was ffac43c).
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> git branch -d add-appetizers
Deleted branch add-appetizers (was 6742d7c).
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> git remote add origin https://github.com/leslie-k26/my-digital-cookbook
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> git remote -v
origin  https://github.com/leslie-k26/my-digital-cookbook (fetch)
origin  https://github.com/leslie-k26/my-digital-cookbook (push)
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/leslie-k26/my-digital-cookbook'
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> git push -u origin
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin master

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> git push --set-upstream origin master
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 16 threads
Compressing objects: 100% (9/9), done.
Writing objects: 100% (10/10), 1.16 KiB | 594.00 KiB/s, done.
Total 10 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), done.
To https://github.com/leslie-k26/my-digital-cookbook
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> git remote -v
origin  https://github.com/leslie-k26/my-digital-cookbook (fetch)
origin  https://github.com/leslie-k26/my-digital-cookbook (push)
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> git push -u origin
branch 'master' set up to track 'origin/master'.
Everything up-to-date
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> git pull
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (3/3), 1.06 KiB | 77.00 KiB/s, done.
From https://github.com/leslie-k26/my-digital-cookbook
   6742d7c..01df6d6  master     -> origin/master
Updating 6742d7c..01df6d6
Fast-forward
 README.md | Bin 48 -> 61 bytes
 1 file changed, 0 insertions(+), 0 deletions(-)
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> cat .\README.md
# My Digital Cookbook
## Welcome to my cooking journey!
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> git log --oneline -3
01df6d6 (HEAD -> master, origin/master, origin/HEAD) Update README with welcome message
6742d7c Add bruschetta appetizer recipe
ffac43c Add chocolate chip cookies recipe
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> echo "**Created by:** Leslie Nguyen" >> README.md
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> git add .\README.md
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> git commit -m "Add author name to README"
[master 33620e2] Add author name to README
 1 file changed, 0 insertions(+), 0 deletions(-)
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook> git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 463 bytes | 463.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/leslie-k26/my-digital-cookbook
   01df6d6..33620e2  master -> master
PS D:\Dev\seneca\cep146-stuff\lab05\my-digital-cookbook>
