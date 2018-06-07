## Github

全球最大的社交编程网站-代码版本控制系统


## Github有什么作用

1.代码托管

2.多人协作_项目开发

3.个人博客_URL访问

4.个人简历

5.团队合作利器（使用分支）

6.代码丢失

7.代码还原

8.记录代码版本

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

12.pull request 请求合并

13.git常用的操作命令

    git init 初始化git仓库

     mkdir zixin
    
   git status 查看状态

   git  add  将文件添加到git仓库的暂存区  git add add.txt 把add.txt文件添加到git仓库的暂存区里 newfile表示文件可以提交commit

   git commit 将暂存区的文件提交到git仓库里去 git commit -m “add add.txt"

   git log  查看日志
    
   git branch 查看当前仓库的分支

   git branch xz 创建xz分支

   git checkout xz 当前分支切换到xz

   git  branch -d xz 删除xz分支

## Android 开发阶段

  1.安装JDK，SDK、Android Studio能够快速开发Android应用程序

  2.Java 7 语言适用于Android开发

  3.使用Android Studio创建项目
   
    A.What is IntelliJ IDEA
    
      IntelliJ IDEA是Java集成开发环境，它支持多种操作系统windows、MacOSX、Linux
    
   B.安装Android模拟器的步骤
    
      a）安装Intel x86 Emulator Accelerator(HAXM installer)
      
      b)安装Android模拟器提示以下错误

      b-1:question：unfortunately,the process com.android.phone has stopped

          Answer：卸载之前的AVD，重新安装AND即可
    
      b-2:Suggestion: use a compatible library with a minSdk of at most 14

          Answer: checkout  run APP is Mobile

     C）Android虚拟机上如何运行自己开发的APP
       
        windows上按Alt-Tab 、 MAC上CMD+Tab

    D）创建新的Virtual Devices
   
     d-1:释放现有的虚拟设备的内存
     
    d-2：Memory RAM set 1024

  4.更新Android studio 版本 
 
      set-Updates-Stable Channel button Check Now

  5.研究Android项目与结构
   
       java、building脚本控制语句

  6.configuring Android Studio
    
     控制Android Studio 外观和行为

      a) Editor 设置调试代码、代码颜色、是否显示行号


 7. 如何处理一个项目的Jar文件

   Project—>tv->build.gradle 
 
   7-a:compileSdkVersion 22(22表示当前使用的API版本)，targetSdkVersion 22 (22表示当前使用的API版本);

   7-b:implementation 'com.android.support:leanback-v17:22.0.1'   22表示当前使用的API版本;

   build.gradle文件使用libs里面Jar文件

020

8.1G-4G的介绍

  1G 大哥大， 语音通话

  2G  小灵通 gsm 发短信 wap.baidu.com，语音+低速数据业务

  3G  沃 网页浏览、音乐等基本数据业务

  4G lte  传输速度比3G快，100M/s 能流畅承载视频、电话会议等业务
 
  5G 华为 6亿美金  10G/s 小公司卖产品大公司卖版权（标准） 

9.Android 操作系统

   创始人：安迪鲁宾，相机系统演变成安卓系统；
 
   logo由来：不带任何的种族及性别的歧视。
 
   Android 系统的体系结构：https://blog.csdn.net/itluochen/article/details/52583442

   Example：实现闹钟：先从应用层通知到（c语言或者C++）编写的写的中

   层，最后中层栏在再次通知Linux层音频驱动能够控制硬件设；


    Android系统的构成：

    [1]linux;

    [2]:函数层 由C或者C++写的；

    [3]：Application frameWork 应用框架层；

    [4] 最上层：应用层
 









  





    
    

  
















