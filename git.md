# git常用命令

+ git init  初始化   
+ git status 查看状态   
  - 红色为工作区内容
  - 绿色为暂存区内容
+ git  add  xx/.  添加到暂存区  
+ git  checkout xxx 从暂存区检出某个文件   
  - 谨慎使用,一旦被检出将会覆盖工作区内容无法还原 
+ git commit -m'xxx'   添加到存储区(二进制)
+ git log  查看历史记录
    - HEAD指向当前版本
    - 日志太多显示不全,enter追加显示,q结束
+ git reset --hard  'axasdfsadf'  回到某个版本

# 分支

+ git branch  xx 创建xx分支
+ git branch -v  查看所有分支
+ git checkout xx 切换分支
+ git merge  xxx(分支名)   把xxx合并到当前分支
+ git branch -d xxx(分支名)  删除xxx分支


# github
+ git remote add origin https://github.com/nevermo2013/1907-git-demo.git 
  - 添加远程关联 https/ssh 两种模式
+ git remote -v  查看远程源
+ git remote remove origin  删除远程关联
+ git push -u origin master   推送到远程
    - 只有第一次需要写 -u
+ git push

+ git clone  https://github.com/nevermo2013/1907-git-demo.git  git-demo
  - clone远程仓库到本地
+ git pull
  - 获取远程内容/ 合并远程内容到本地
  - 如果远程出现了更新,必须先pull再commit再push


# ssh 
+ ssh-keygen -t rsa -C "youremail@example.com"  生成秘钥
