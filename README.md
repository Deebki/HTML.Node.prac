HTML.Node.prac
==============

HTML with Node practice @RailsBridge Frontend Wkshp

===================================
HOW TO STAGE, COMMIT & PUSH TO GIT PUB-FACING

C:\Users\RosanneMS>cd learningless

C:\Users\RosanneMS\learningless>git status
fatal: Not a git repository (or any of the parent directories): .git

C:\Users\RosanneMS\learningless>git init
Initialized empty Git repository in C:/Users/RosanneMS/learningless/.git/

C:\Users\RosanneMS\learningless>git add .

C:\Users\RosanneMS\learningless>git status
On branch master

Initial commit

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   HTML practice file
        new file:   Less/Style.less
        new file:   index.html


C:\Users\RosanneMS\learningless>git commit -m "first commit"
[master (root-commit) 5ce0f9f] first commit
 3 files changed, 40 insertions(+)
 create mode 100644 HTML practice file
 create mode 100644 Less/Style.less
 create mode 100644 index.html

C:\Users\RosanneMS\learningless>git remote add origin https://github.com/Deebki/
HTML.Node.prac.git

C:\Users\RosanneMS\learningless>
C:\Users\RosanneMS\learningless>git push origin master
Username for 'https://github.com': Deebki
Password for 'https://Deebki@github.com':
Counting objects: 6, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 878 bytes | 0 bytes/s, done.
Total 6 (delta 0), reused 0 (delta 0)
To https://github.com/Deebki/HTML.Node.prac.git
 * [new branch]      master -> master

C:\Users\RosanneMS\learningless>
===============================
