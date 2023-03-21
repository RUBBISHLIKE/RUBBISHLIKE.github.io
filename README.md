# RUBBISHLIKE.github.io
学号：202000161069     姓名： 欧阳坤   班级： 智能20  
实验题目：利用云平台搭建个人博客  
实验学时：2  实验日期：2023/3/21      
实验目的：熟悉个人博客系统的搭建。  
具体包括：参考方案：注册Github账号，搭建Hexo环境并实现个人博客搭建，撰写实验报告。  

硬件环境：   
联网的计算机一台  

软件环境：  
Windows   

实验步骤与内容：  
1.	注册 GitHub 账号 如果没有 GitHub 账号，可以前往 https://github.com/join 注册一个新账号。 我之前已经注册过了，所以无需再注册一遍了。  
2.	创建新的 GitHub 仓库 登录 GitHub 账号之后，点击右上角的加号 "+"，选择 "New repository"。输入仓库名称并选择公共或私有，然后点击 "Create repository" 创建新的仓库。  
3.	安装 Node.js 和 Git 需要先安装 Node.js 和 Git。可以使用以下命令来安装：  
sudo apt-get update  
sudo apt-get install -y nodejs git  
 ![Aaron Swartz][https://github.com/RUBBISHLIKE/PHOTOS/raw/main/p1.png]
4.安装 Hexo 在安装 Node.js 和 Git 之后，可以使用 npm（Node.js 包管理器）来安装 Hexo。使用以下命令来安装 Hexo：
sudo npm install -g hexo-cli  
5.创建 Hexo 博客 安装完成 Hexo 之后，使用以下命令来创建一个新的博客：  
hexo init Hexo-blog  
这将创建一个名为 " Hexo-blog" 的新目录，其中包含 Hexo 的所有必需文件和目录。  
6.配置 Hexo 在创建了新的博客之后，需要对 Hexo 进行一些基本配置。打开 " Hexo-blog" 目录下的 _config.yml 文件，根据自己的需要修改配置选项，比如网站标题、描述、作者等等。  
7.安装主题 Hexo 支持多种主题，可以选择一个自己喜欢的主题进行安装和使用。可以前往 https://hexo.io/themes/ 查找和下载喜欢的主题。下载完成之后，将主题文件夹复制到 " Hexo-blog/themes/" 目录下。  
8. 发布博客 在完成了 Hexo 的配置之后，可以开始撰写博客并发布到网站上。完成之后，可以使用以下命令来生成网站hexo generate，然后可以使用以下命令来启动本地服务器hexo server  
hexo server -p 5000  
博客页面如下(后期可以发布一些有意义的内容完善)  
 ![Aaron Swartz][https://github.com/RUBBISHLIKE/PHOTOS/raw/main/p2.png]
9.发布新的博客  
  ![Aaron Swartz][https://github.com/RUBBISHLIKE/PHOTOS/raw/main/p3.png]
 
10.将实验报告上传到网站上  
