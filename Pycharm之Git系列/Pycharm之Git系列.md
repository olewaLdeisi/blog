## 一、 准备工作
&emsp;首先你需要有一个github账户，同时电脑里安装git，
这些工作准备好了之后，可以开始我们的Pycharm体验了。  
> 说明: 博主的Pycharm是2018.1版本。

## 二、 配置Pycharm的Git环境
&emsp;1.打开Pycharm，选择菜单栏的`File -> Settings ->
Version Control -> Github` :  
！[1_File_Settings](./imgs/1_File_Settings.png)  
&emsp;2.输入自己的github账号:  
！[2_配置Github](./imgs/2_配置Github.png)  
&emsp;3.在同个目录下选择Git，填上自己安装的Git路径:  
！[3_配置Git](./imgs/3_配置Git.png)  

## 三、 从Github导入项目到本地
&emsp;1.选择菜单栏的`VCS -> Checkout from Version Control`，
选择 `Git`  
！[4_从Git检出项目](./imgs/4_从Git检出项目.png)  
&emsp;2.在弹出的窗口的URL填上你要导入的Github上的项目地址，Directory
填上保存到本地的路径，然后点击Clone，克隆好了就选择打开  
！[5_克隆远程仓库](./imgs/5_克隆远程仓库.png)  

## 四、 如何提交本地修改，更新到Github
&emsp;1. 在Pycharm中修改过的文件会显示蓝色，新建的文件会显示红色  
！[6_文件颜色显示](./imgs/6_文件颜色显示.png)  
&emsp;2. 鼠标右键项目目录，先选择 `Git -> Add`，再选择 `Git -> Commit Directory...`  
> 说明: 如果读者是参与别人的项目，在Commit之前要先Pull，作用是先更新本地的代码，防止你克隆项目
后到提交项目前的这段时间，原项目已经更新，导致合并冲突，Pull操作下面会说明  

！[7_Comit](./imgs/7_Comit.png)
！[8_提交更改](./imgs/8_提交更改.png)  
&emsp;3. 仅仅是进行Commit操作是不会更新到Github的，还需要Push操作  
鼠标右键项目目录，选择 `Git -> Repository -> Push`  
！[9_Push操作](./imgs/9_Push操作.png)
> 说明: Pull操作也在这里  
如果遇到`OpenSSL SSL_connect: SSL_ERROR_SYSCALL in connection to github.com:443`的错误，  
一般是你开启了代理，关掉了就好

本文完，敬请期待下一篇 [Pycharm之Git分支管理]()




