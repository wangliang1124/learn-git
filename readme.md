# hello world

## git branch dev

## git checkout dev

## git checkout -b dev

## 添加新功能

## 试验一下强制禁用 fast forword, --no-ff

## 试验一下强制禁用 fast forword, --no-ff

## 再次试验一下强制禁用 fast forword, --no-ff

## 再来一次 修复 bug

## issue-1: 修复 bug

## 添加远程分支

## 添加远程分支 2

## 111

## 222

## 333

## 444

## 555

git status
```
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   readme.md

no changes added to commit (use "git add" and/or "git commit -a")
```

git add .

git status
```
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	modified:   readme.md
```

git commit
```
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
```

有新的提交

```
On branch master
Your branch is behind 'origin/master' by 1 commit, and can be fast-forwarded.
  (use "git pull" to update your local branch)

nothing to commit, working tree clean
```

git pull

git status
```
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean
```
