# studyMiniProgram
学习小程序开发

# git 将本地项目关联到远程仓库

1.首先在项目目录下初始化本地仓库

git init

2.添加所有文件( . 表示所有)

git add .

3.提交所有文件到本地仓库

git commit -m "备注信息"

4.连接到远程仓库

git remote add origin 你的远程仓库地址

5.将项目推送到远程仓库

git push -u origin master

6.报错输入

git pull --rebase origin master