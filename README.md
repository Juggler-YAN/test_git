# test_git

1. 拉取远程仓库最新代码

```
git clone <仓库地址>
cd <项目目录>
git fetch origin
```

2. 根据你要开发的功能切换分支 or 创建新分支

```
git checkout main      # 切换到主分支
git checkout develop   # 切换到开发分支
git checkout feature/login   # 切换到已有功能分支
git checkout -b feature/my-new-feature # 创建并切换到新分支
```

3. 开发

4. 推送到远程分支上（根据实际情况）

```
git add ...
git commit -m "完成某某功能"
git push origin feature/my-feature
```

6. 推送到main分支上（根据实际情况）

···
git checkout main
git pull origin main
git merge develop
git add ...
git commit -m "完成某某功能"
git push origin main
```

7. 删除自己的分支

```
git branch -d develop
git push origin --delete develop
```

