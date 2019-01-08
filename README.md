## 笔记222

## git操作
    1). 创建本地仓库
           创建.gitignore配置文件
           git init
           git add *
           git commit -m "xxx"
    2). 创建远程仓库
          New Repository
           指定名称
           创建
    3). 将本地仓库推送到远程仓库
           git remote add origin https://github.com/zxfjd3g/xxx.git 关联远程仓库
           git push origin master
    4). 如果本地有更新, 推送到远程
       git add *
           git commit -m "xxx"
           git push origin master
    5). 如果远程有更新, 拉取到本地
       git pull origin master
       git fetch origin master:tmp
    6). 克隆远程仓库到本地
       git clone https://github.com/zxfjd3g/xxx.git
       git checkout -b dev origin/dev