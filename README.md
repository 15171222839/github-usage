# github-usage
github创建与上传本地文件

一.创建很简单

  直接在登录首页，点击new repository————（选中公开public）————然后点击create repository创建仓库
  
二.上传本地文件

  1.在桌面创建一个文件，把要上传的东西放在文件里
  
  2.启动git Bash代码编辑框
  
  3.cd到创建的文件夹中//（cd desktop / cd 文件名）
  
  4.git init //（把这个目录变成Git可以管理的仓库）
  
  5.git add -A //（上传文件夹中所有文件）
  
  6.git commit -m "first commit" //把文件提交到仓库，其中first commit随意定义
  
  7.git remote add origin https://github.com/15171222839/github-usage.git //关联远程仓库
  
  8.git push origin master//把本地库的所有内容推送到远程库上

完成传送，刷新页面可见！！！

三.下载那就更简单了

  有2种方法，可能更多：
  
  方法一：直接download
  
  方法二：和上传本地文件前三个步骤一样，cd到创建文件夹中，接着git clone https://github.com/15171222839/github-usage.git（需要下载的链接）
  
 任务完成！
