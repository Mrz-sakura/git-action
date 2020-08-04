### 初始化 Git 仓库

```git
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/Mrz-sakura/git-action.git
git push -u origin master
```

### 如果有 git 仓库

```git
# 移除原有git仓库
git remote remove origin
git remote add origin https://github.com/Mrz-sakura/git-action.git
git push -u origin master
```
