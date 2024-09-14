## 1.创建仓库命令：
### 初始化一个本地仓库
git init
### 添加所有文件到暂存区
git add .
### 提交暂存区的文件到本地仓库，并添加一条提交信息
git commit -m "first commit"
### 添加一个远程仓库的地址，命名为origin
git remote add origin https://github.com/user/repo.git
### 将本地仓库的内容推送到远程仓库的master分支(这里主分支是main)
git push -u origin mian


## 2.其他git常用命令：
### 查看远程仓库地址
git remote -v
### 查看远程仓库的分支
git branch -r
### 查看本地仓库的分支
git branch
### 切换分支
git checkout branch_name
### 创建并切换分支
git checkout -b branch_name
### 删除分支
git branch -d branch_name
### 强制删除分支
git branch -D branch_name
### 合并分支
git merge branch_name
### 拉取远程仓库的更新
git pull
### 推送本地仓库的更新到远程仓库
git push
### 查看提交历史
git log
### 查看提交历史，并显示每次提交的diff
git log -p
### 查看提交历史，并显示每次提交的diff，并限制显示的行数
git log -p -n 5