# 项目说明

### git远程仓库操作

```bash
# 克隆远程仓库(从无到有)
$ git clone https://github.com/jxsrzj0325/myapp.git

# 设置远程服务器地址
$ git remote add origin https://github.com/jxsrzj0325/myapp.git

# 将本地仓库推送的远程服务器
$ git push -u origin main

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

# 切换分支
$ git checkout 分支名

# 合并分支
$ git merge 分支名
```