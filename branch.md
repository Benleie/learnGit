

## learnBranch
[教程](https://learngitbranching.js.org/)



+ git init
+ git add .
+ git commit
+ HEAD 默认指向当前分支上最近一次提交记录


## 分支
+ git branch [branch]    新建
+ git checkout -b [branch] 新建并切换
+ git checkout [branch]    切换分支

+ git checkout [commit]  分离HEAD,指定提交记录
+ git checkout [branch]^ 
+ git checkout HEAD^
+ `git branch -f master HEAD~3` 强制移动分支


+ git merge [branch]  创建新的提交，并把别的分支合并过来
+ git rebase [branch]  HEAD向前创建新的提交，把branch添加过去


## 撤销变更
+ git reset
+ git revert HEAD

## 深入了解
+ git cherry-pick [commit]
+ git rebase -i 位置

## 远程分支
push.default
+ git checkout origin/master  分离HEAD
+ 远程库更新后rebase和merge存在区别
+ git pull --rebase


+ git branch --set-upstream-to=origin/learn master

## 解决冲突
+ mergetool
+ 手动解决





