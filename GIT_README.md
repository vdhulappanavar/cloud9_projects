-------------------------------------------------------------
Step 1 : Create a Github repo cloud9_projects
-------------------------------------------------------------


https://github.com/vdhulappanavar/cloud9_projects

touch README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/vdhulappanavar/cloud9_projects.git
git push -u origin master
…or push an existing repository from the command line


git remote add origin https://github.com/vdhulappanavar/cloud9_projects.git
git push -u origin master
…or import code from another repository

You can initialize this repository with code from a Subversion, Mercurial, or TFS project.

------------------------------------------------------------
Step 2 : 
-------------------------------------------------------------
vdhulappanavar@demo-project:~/workspace (master) $ git init
Reinitialized existing Git repository in /home/ubuntu/workspace/.git/

------------------------------------------------------------
Step 2 : 
-------------------------------------------------------------
vdhulappanavar@demo-project:~/workspace (master) $ git add -A

------------------------------------------------------------
Step 2 : 
-------------------------------------------------------------
vdhulappanavar@demo-project:~/workspace (master) $ git commit -m "Initial Version"
[master 34308f7] Initial Version
 21 files changed, 115 insertions(+)
 create mode 100644 .c9/.nakignore
 create mode 100644 .c9/metadata/tab0
 create mode 100644 .c9/metadata/tab1
 create mode 100644 .c9/metadata/workspace/C/README.md
 create mode 100644 .c9/metadata/workspace/C/hello.c
 create mode 100644 .c9/metadata/workspace/GIT_README.md
 create mode 100644 .c9/metadata/workspace/Java/README.md
 create mode 100644 .c9/metadata/workspace/README.md
 create mode 100644 .c9/metadata/workspace/hello.c
 create mode 100644 .c9/metadata/workspace/node.js/server.js
 create mode 100644 .c9/metadata/workspace/php/index.php
 create mode 100644 .c9/metadata/workspace/vidya.java
 create mode 100644 .c9/project.settings
 create mode 100644 C/README.md
 create mode 100755 C/a.out
 create mode 100644 C/hello.c
 create mode 100755 C/vidya.out
 create mode 100644 GIT_README.md
 create mode 100644 Java/README.md
 create mode 100644 Java/vidya.class
 create mode 100644 Java/vidya.java
 
------------------------------------------------------------
Step 2 : 
------------------------------------------------------------- 
 
vdhulappanavar@demo-project:~/workspace (master) $ git remote add origin https://github.com/vdhulappanavar/cloud9_projects.git
fatal: remote origin already exists.
vdhulappanavar@demo-project:~/workspace (master) $ git remote -v
origin  git://github.com/ajaxorg/demo-project.git (fetch)
origin  git://github.com/ajaxorg/demo-project.git (push)
vdhulappanavar@demo-project:~/workspace (master) $ git remote add vidya_githuborigin https://github.com/vdhulappanavar/cloud9_projects.git                      
vdhulappanavar@demo-project:~/workspace (master) $ git remote -v
origin  git://github.com/ajaxorg/demo-project.git (fetch)
origin  git://github.com/ajaxorg/demo-project.git (push)
vidya_githuborigin      https://github.com/vdhulappanavar/cloud9_projects.git (fetch)
vidya_githuborigin      https://github.com/vdhulappanavar/cloud9_projects.git (push)

------------------------------------------------------------
Step 2 : 
-------------------------------------------------------------

vdhulappanavar@demo-project:~/workspace (master) $ git push -u vidya_githuborigin master
Username for 'https://github.com': vdhulappanavar
Password for 'https://vdhulappanavar@github.com': 
Counting objects: 94, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (62/62), done.
Writing objects: 100% (94/94), 55.91 KiB | 0 bytes/s, done.
Total 94 (delta 24), reused 62 (delta 16)
To https://github.com/vdhulappanavar/cloud9_projects.git
 * [new branch]      master -> master
Branch master set up to track remote branch master from vidya_githuborigin.
vdhulappanavar@demo-project:~/workspace (master) $ 

------------------------------------------------------------
Step 2 : 
-------------------------------------------------------------

vdhulappanavar@demo-project:~/workspace (master) $ git add -A
vdhulappanavar@demo-project:~/workspace (master) $ git commit -m "Second Version"
[master 9b5075e] Second Version
 3 files changed, 99 insertions(+), 2 deletions(-)
 rewrite .c9/metadata/workspace/GIT_README.md (92%)
vdhulappanavar@demo-project:~/workspace (master) $ git push -u vidya_githuborigin master
Username for 'https://github.com': vdhulappanavar
Password for 'https://vdhulappanavar@github.com': 
Counting objects: 15, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (8/8), done.
Writing objects: 100% (8/8), 3.09 KiB | 0 bytes/s, done.
Total 8 (delta 5), reused 0 (delta 0)
To https://github.com/vdhulappanavar/cloud9_projects.git
   34308f7..9b5075e  master -> master
Branch master set up to track remote branch master from vidya_githuborigin.
vdhulappanavar@demo-project:~/workspace (master) $ 