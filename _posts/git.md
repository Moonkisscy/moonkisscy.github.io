---
title: 学习git
date: 2020-01-11
categories: Linux
tags:
- linux
- git
- github
---




```
$git init
//在文件夹新建readme.txt
$ git add readme.txt

Administrator@XB-20151111COQP MINGW64 /e/git (master)
$ git commit -m "add a readme file"
master (root-commit) afd5aa3] add a readme file
 1 file changed, 1 insertion(+)
 create mode 100644 readme.txt

```



 将工作目录的文件放到Git仓库只需要两步：

```
git add 文件名
git commit -m "你干了啥"
```
20200111
$ git push origin maste
error: src refspec maste does not match any.
error: failed to push some refs to 'https://github.com/Moonkisscy/moonkisscy.github.io.git'


删除了里面的文件导致上传失败：
$ git pull origin master
From https://github.com/Moonkisscy/moonkisscy.github.io
 * branch            master     -> FETCH_HEAD
Already up to date.

解决：
cy@cy-PC MINGW64 /d/GitHub/moonkisscy.github.io/_posts (master)
$ git push -u origin master
Everything up-to-date
Branch 'master' set up to track remote branch 'master' from 'origin'.
