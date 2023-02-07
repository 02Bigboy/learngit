# 下面是使用git的教程
## 首先确定电脑能否用git，不能的话需要安装
## 需要首先设置用户名和对应的邮件
## 然后将目录变成git管理，即变成仓库，需要用git初始化（直接git clone的就不需要这一步了）
```
git init
```
# 然后就可以对仓库进行改了
# 改完之后需要将改动的添加到缓存区
```
git add file_name
# 也可以用下面命令添加所有修改的文件
git add . 
```
## 然后将缓存区的提交到分支里面
```
git commit -m "自己对提交的描述"
```
# 上面就实现了改动，到提交的过程
## 查看当前分支的状态
```
git status
```
## 查看提交的历史信息
```
git log
```
## 当我们修改了一个文件后，但还没提交，我们可以比较工作区和版本库里最新版本的区别（就相当于插件compare的作用）
```
git diff HEAD --- file_name
```
## 回退到前面提交的版本
```
git reset --hard HEAD^ //HEAD表示当前版本，一个^表示log里上一个版本
git reset --hard id //这里id是log时 commit id的id，用这种情况可以处理想要的版本在之前回退的时候已经不见了（删除了），所以知道想要版本的id很重要
```
# 将本地创建的仓库与github联系，同步交互
## 首先要生成自己电脑的ssh key
## 然后再github自己的账号设置里添加电脑的ssh key
## 然后在github里创建同名空仓库
## 然后运行下面命令使得本地与github进行连接
```
git remote add origin git@github.com:mygithub_name/仓库_name.git
```
## 然后将本地仓库的所有内容推送到github上
```
git push -u origin master  //第一次推送要加上-u参数， git push就是把当前分支推送到远程
```
## 推送成功后就可以看见远程仓库内容和本地一模一样
## 后面，只要本地做了提交，就可以通过下面命令，将本地分支的最新修改推送到github上
···
git push origin master
···

