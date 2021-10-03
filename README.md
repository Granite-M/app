# 项目说明

### git远程仓库操作

```bash
# 克隆远程仓库(从无到有)
$ git clone https://github.com/jxsrzj0325/myapp.git

# 设置远程服务器地址
$ git remote add origin(origin 是自己起的名字) https://github.com/jxsrzj0325/myapp.git

# 将本地仓库推送的远程服务器
$ git push -u origin main

# 查看分支
$ git branch
# 修改分支名
$ git branch -M 分支名 

# 拉取远程分支(更新)
$ git pull origin 分支名

```

### 分支操作
```bash
# 查看分支
$ git branch     

# 创建分支
$ git branch 分支名 
#创建属于自己的分支，在自己的分支上进行开发，
#千万不能在主分支上进行修改，
#千万不能在主分支上进行修改，
#千万不能在主分支上进行修改，

# 切换分支  切换到自己的分支进行开发
$ git checkout 分支名
# 开发完成后，
# git add .
# git commit -m 'v1.0.0'

# 将本地仓库推送的远程服务器
$ git push -u origin main

# 不需要自己合并分支的话  操作到此结束




# 合并分支 
$ git merge 分支名
$ git merge ZYD
```