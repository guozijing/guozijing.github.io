---
title: git-随笔
date: 2019-04-28 21:52:49
tags: git
categories: git
---
#### git-随笔
> fork 创建私有库
> git clone 建立本地库并将私有库的工程拷贝到本地
> git commit 提交到本地库
> git push 提交到版本库
> git pull 把最新的代码下载到本地库


<!-- more -->
#### git文件提交管理
> 工作区 -> git add -> 提交到暂存区 -> commit -> 提交到版本库

#### 步骤
> 1.创建fork私有库
> 2.clone创建本地库
> 3.fork库中创建topic分支
> 4.本地切换到topic分支
> 5.编辑 add commit push
> 6.fork中的topic分支 -> 集中库的master分支

#### 常用命令
> git init 本地库初始化
> git add 提交到暂存区
> git config
> git status 查看状态
> git commit -m '注释'
> git reflog
> git reset --hard +索引值 移动head
> git reset --hard head^ 回退一步
> git reset --hard head~n 回退n步
> git diff 文件名 查看修改
> git branch -v 查看所有分支情况
> git branch 名 创建分支
> git checkout 名 更改当前分支
> 合并分支  切换到接受修改的分支上 git merge 分支名
> 冲突解决 git remote add 别名 地址 
> git push
