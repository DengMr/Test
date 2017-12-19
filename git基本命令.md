# 第一次配置
>配置用户名
* git config --global user.name "用户名"
***
>配置邮箱
* git config --global user.email "注册的邮箱"
***
>查看用户配置信息
* git config --global  --list
***
# 仓库管理
>创建仓库
* mkdir Myapp
***
>进入仓库所在目录
* cd Myapp
***
>仓库初始化
* git init
***
>是VS code创建index.html文件
* code index.html
***
>添加到仓库暂存区
* git add index.html
***
>提交到仓库分支
* git commit -m "提交说明"
***
>查看提交日志
* git log
* --pretty=oneline(美化)
***
>回退版本
* git reset --hard HEAD^(回退到上一个版本)
* git reset --hard commit id(指定回退版本号)
***
>用来记录每次命令
* git reflog
***
>查看工作区状态
* git status
***
>查看最近版本的区别
* git diff HEAD -- 文件名
***
>撤销修改
* git checkout -- 文件名
***
>删除文件
* rm 文件名(可撤销)
* git rm 文件名(不可撤销)
***
20171019