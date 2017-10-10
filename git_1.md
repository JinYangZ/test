# GIT初始化及仓库创建和操作 #
## 设置用户名 ##
    git config --global user.name 'XXX'
## 设置用户名邮箱 ##
    git config --global user.email 'XX@XX.com'
## 创建文件 ##
    mkdir xx
## 显示当前位置 ##
    pwd
## 文件内初始化git（创建git仓库） ##
    git init
## 添加文件 ##
    touch
## 显示当前状态 ##
    git status
## 添加到暂存处 ##
    git add
## 添加到仓库 ##
    git commit -m '添加描述'
## GIT克隆操作 ##
### 目的 ###
将远程仓库（github对应的项目）复制到本地
### 代码 ###
    git clone 仓库地址
### 创建文件 ###
    vi a1.php
### 添加ssh key ###
    ssh-keygen -t rsa -C 'username'
### 测试ssh ###
    ssh -T git@github.com