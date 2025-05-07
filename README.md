PS C:\Users\26029\Desktop\git_demo> git init
Initialized empty Git repository in C:/Users/26029/Desktop/git_demo/.git/
PS C:\Users\26029\Desktop\git_demo> git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.html

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\26029\Desktop\git_demo> $ git config --global user.name "younger234"
$ : 无法将“$”项识别为 cmdlet、函数、脚本文件或可运行程序的名称。请检查名称的拼写，如果包括路径，请确保路径正确，然后再试一次。     
所在位置 行:1 字符: 1
+ $ git config --global user.name "younger234"
+ ~
    + CategoryInfo          : ObjectNotFound: ($:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\26029\Desktop\git_demo> ^C
PS C:\Users\26029\Desktop\git_demo> git config --global user.name "younger234"
PS C:\Users\26029\Desktop\git_demo> git config --global user.email 2962601810@qq.com
PS C:\Users\26029\Desktop\git_demo> git config --global http.proxy http://127.0.0.1:7897
PS C:\Users\26029\Desktop\git_demo> ^C
PS C:\Users\26029\Desktop\git_demo> git config --global https.proxy https://127.0.0.1:7897
PS C:\Users\26029\Desktop\git_demo> git log
commit bf77ef66593b9413a7eb9c5cad0923215b9a7bae (HEAD -> master, origin/master, origin/HEAD)
Author: younger234 <2962601810@qq.com>
Date:   Wed May 7 19:31:01 2025 +0800

    add main.js

commit e135c8ba982e2e8d6a252480093e8c9e738e9da5
Author: younger234 <2962601810@qq.com>
Date:   Wed May 7 19:13:33 2025 +0800

    second save

commit 489d6ae336436f03b9932cfd38bfbd714e852f0b
Author: younger <2602961810@qq.com>
Date:   Wed May 7 19:09:11 2025 +0800

    first save
PS C:\Users\26029\Desktop\git_demo> 