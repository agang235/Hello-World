1.安装git

2. 设置姓名和邮箱
$ git config --global user.name "a**********"  
$ git config --global user.email "4*********@qq.com"

3. 设置颜色(可选)
$ git config --global color.ui auto

4. 设置秘钥 (秘钥可以设置密码)0***********
$ ssh-keygen -t rsa -C "4**********@qq.com"


5. 用秘钥链接git
$ ssh -T git@github.com

6. 切换目录
$ cd e:gitcode

7. 克隆项目
注:用ssh的话必须要有秘钥
$ git clone git@github.com:agang235/Hello-World.git

8. 加入暂缓区(在本地还没上传)
$ git add world.md

9. 提交本地到本地仓库(只提交add的文件)
只是提交到本地仓库,并没有提交到远程仓库,还需要push才能提交当远程仓库
$ git commit -m "第一个提交的文件"

10. 提交到远程仓库
$ git push

11. 通过git创建仓库
$ mkdir git-tutorial   //创建目录
$ git init //执行这一条以后就会生成一个.git目录

12. git status 查看仓库状态

13. git diff 查看工作树和暂缓区的差别

14. git checkout master 切换分支

15. git chaeckout - 切换到上一分支

16. git reset --merge  退回到合并以前,一般在合并出现冲突时退回

17. 切换分支时,文件夹中的文件就会跟着发生变化,notpad++编辑器这时就会提醒你是否要重新加载

18. git log --graph 以图表形式查看分支
