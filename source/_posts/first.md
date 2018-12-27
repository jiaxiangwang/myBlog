---
title: first
date: 2018-12-27 18:00:34
tags:
---
## create a new repository on the command line
`
echo "# myBlog" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/jiaxiangwang/myBlog.git
git push -u origin master
`
## push an existing repository from the command line
`
git remote add origin https://github.com/jiaxiangwang/myBlog.git
git push -u origin master

`