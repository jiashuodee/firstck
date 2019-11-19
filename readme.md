# 第一个仓库
1 git init 初始化仓库
2 新建一个readme.md  文件
3 git add 文件名 添加文件到本地仓库
 4添加用户和邮箱
git config --global user.email  邮箱名
git config --global user.name 用户名
4- 提交
 git commit -m 注释    本次提交的说明
 5. 添加远程仓库地址
git remote add origin git@github.com:jiashuodee.com/仓库名.git
 5 将本地提交的内容推送到远程仓库
git push 远程仓库的别名 master
git push

6没有权限  先生成ssh key
ssh-keygen -t rsa -c 邮箱
执行完上一条命令后，会在~/.ssh/ 文件夹下生成公钥文件 id_rsa.pub
将公钥文件中的内容放到Github中；
 右上角头像 -> settings -> SSH and GPG keys -> New SSH key
	title： 仓库名
	Key： id_rsa.pub 的内容
```s