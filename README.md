# 在大服务器上安装SOWFA需要的部分安装包

因为编译安装OpenFOAM、SOWFA需要git clone源码库，大服务器不联网不能下载，而在Windows上git clone下来的换行符格式和Linux的不一样，不能直接在Linux上使用

所以打包了一份Linux上能直接用的压缩包，可以直接sftp上传到服务器

> 具体按照手册参考[我的个人博客](http://www.xf-blog.top/2023/10/31/SOWFA-on-cluster/)   
