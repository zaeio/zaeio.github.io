---
sort: 1
---

# 仓库管理

## 从本地新建仓库

    git init
    git add .
    git commit -m "message"
    git branch -M main

使用token将本地仓库关联到远程仓库  

    git remote add origin https://[username]:[token]@github.com/[username]/[repository].git

> 问题：fatal: remote origin already exists.  
> 解决：git remote rm origin 删除关联的origin的远程库  

将本地分支的更新，推送到远程主机。现在github的主分支名称从master改成了main。

    git push -u origin main
