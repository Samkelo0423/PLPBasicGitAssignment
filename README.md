# PLPBasicGitAssignment

Microsoft Windows [Version 10.0.22631.3672]
(c) Microsoft Corporation. All rights reserved.

C:\Users\Samkelo Gift>mkdir PLPBasicGitAssignment

C:\Users\Samkelo Gift>cd PLPBasicGitAssigment
The system cannot find the path specified.

C:\Users\Samkelo Gift>cd  PLPBasicGitAssignment

C:\Users\Samkelo Gift\PLPBasicGitAssignment>git init
Initialized empty Git repository in C:/Users/Samkelo Gift/PLPBasicGitAssignment/.git/

C:\Users\Samkelo Gift\PLPBasicGitAssignment>git remote add origin https://github.com/Samkelo0423/PLPBasicGitAssignment.git

C:\Users\Samkelo Gift\PLPBasicGitAssignment>echo "Hello, Git!"> hello.txt

C:\Users\Samkelo Gift\PLPBasicGitAssignment>git add hello.txt

C:\Users\Samkelo Gift\PLPBasicGitAssignment>git commit -m "Add hello.txt with a greeting"
[master (root-commit) 8b84878] Add hello.txt with a greeting
 1 file changed, 1 insertion(+)
 create mode 100644 hello.txt

C:\Users\Samkelo Gift\PLPBasicGitAssignment>git -u origin main
unknown option: -u
usage: git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           [--super-prefix=<path>] [--config-env=<name>=<envvar>]
           <command> [<args>]

C:\Users\Samkelo Gift\PLPBasicGitAssignment>git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/Samkelo0423/PLPBasicGitAssignment.git'

C:\Users\Samkelo Gift\PLPBasicGitAssignment>git -M main
unknown option: -M
usage: git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           [--super-prefix=<path>] [--config-env=<name>=<envvar>]
           <command> [<args>]

C:\Users\Samkelo Gift\PLPBasicGitAssignment>git branch -M main

C:\Users\Samkelo Gift\PLPBasicGitAssignment>git push -u origin main
To https://github.com/Samkelo0423/PLPBasicGitAssignment.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/Samkelo0423/PLPBasicGitAssignment.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

C:\Users\Samkelo Gift\PLPBasicGitAssignment>git pull origin main --allow-unrelated-histories
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 896 bytes | 149.00 KiB/s, done.
From https://github.com/Samkelo0423/PLPBasicGitAssignment
 * branch            main       -> FETCH_HEAD
 * [new branch]      main       -> origin/main
Merge made by the 'ort' strategy.
 README.md | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

C:\Users\Samkelo Gift\PLPBasicGitAssignment>git push -u origin main
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (5/5), 570 bytes | 570.00 KiB/s, done.
Total 5 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Samkelo0423/PLPBasicGitAssignment.git
   d0286b2..ecdd77e  main -> main
branch 'main' set up to track 'origin/main'.

C:\Users\Samkelo Gift\PLPBasicGitAssignment>
