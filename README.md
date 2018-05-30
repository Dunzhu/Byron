## Github
全球最大的社交编程网站


## Github有什么作用

1.代码托管

2.多人协作_项目开发

3.个人博客_URL访问

4.个人简历

## 使用Github 

 1.stars “收藏“

 2.fork  “复制”_编辑

 3.repository “仓库”
  
 4.watch  “观看“ _
 事实获取更新的内容

5.gist “代码片段” _分享gist的内容

6.clone “克隆”

  cmd：\g:

    git clone +URl

  cd Byron(远程项目名称)


   再次 cd dir

最后README.md打开远程仓库项目

7.git config 配置信息

    user：G:\Byron>git config --global(全局)  user.name "Dunzhu"
    
     email：G:\Byron>git config --global(全局)  user.email "1486374440@qq.com"


8.已远程的本地库上插入New内容及上转至github

A.将本地更新的内容插入至README.md_git   //每次更新本地文件重复运行一下代码

   git status     git add README.md   git commit  -m "add feature"

                 example：

                 G:\Byron>git status 
           
                 G:\Byron>git add README.md 

                 G:\Byron>git commit  -m "add feature"
B.本地仓库上转至github

       SSH 授权之后

git push  origin master  

    各种错误解决方案：https://blog.csdn.net/qq_28055429/article/details/51007453
            https://blog.csdn.net/qq_31387043/article/details/72844178
     Everything up-to-date：https://blog.csdn.net/lxcboke/article/details/52230717

git remote add origin git@github.com:Dunzhu/Byron.git
  ssh授权 

    生成秘钥：ssh-keygen-t rsa

    验证是否授权成功 : ssh -T git@github.com

   用这个工具git bash 

  私钥pash： c/Users/Administrator/.ssh/id_rsa.
  公钥pash： c/Users/Administrator/.ssh/id_rsa.pub.

C.从github推送到本地

 git pull  origin master

Your local changes to the following files would be overwritten by merge:

解决方案：https://blog.csdn.net/misakaqunianxiatian/article/details/51103734

9.git 	branch -git分支	
  
新建一个A分支： git branch A 

切换到A 分支： git checkout A -A分支的内容与master的内容完全一样

 git add README.md ，git commit  -m "feature A"

A分支的内容上传到github git push origin A 

10.git merge   合并

  git merge A _把A新加的功能合并到master


11.删除分支 git branch -d A 


 

















