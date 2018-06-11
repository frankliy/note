### GitHub创建

##### 创建git仓库

> git init

##### 把文件提交到仓库

> git add . 
>
> git commit -m "备注"

##### 关联远程仓库

> git remote add origin git@github.com:frankliy/vuedemo.git
>
> git push origin master     (第一次需要公钥)

##### 公钥

本地磁盘C>用户>user目录下会有一个.ssh文件，文件中有一个known_hosts文件

> ssh-keygen -t rsa -C "邮箱"

这是.ssh文件中多了两个id_rsa文件，打开id_rsa.pub文件，复制，回到github中>Settings>SSH and GPG keys ,新建SSH key，粘贴到key中。

##### 推送到远程仓库

https://blog.csdn.net/Freelifewe/article/details/79666995

> git push origin master

网页效果

> Setting>GitHub Pages>change theme>Select theme

在GitHub Pages下方就会出现一个可以查看网页效果的网址。

### Git克隆

##### 初始化

> git init

##### 克隆

> git clone git@github.com:frankliy/vuedemo.git

### 创建分支

##### 拉

> git push origin master

##### 创建分支

> git branch name

##### 切换到分支

> git checkout name

##### 添加分支

> git add .
>
> git commit -m "备注"

##### 检查在哪个分支

> git branch

##### 合并分支

> 1. git checkout master
> 2. git merge name

##### 删除分支

> git branch -d name

### 修改丢失的文件

> git log

选择commit前几位数字，如123456

##### 找回以前的文件

> git reset --hard 123456

