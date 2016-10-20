#Gitbook命令
安装Gitbook的时候我们接触了Gitbook的安装命令，本章会介绍一些Gitbook中常用的命令。


`npm install gitbook-cli -g`    
gitbook安装   

`gitbook -V`    
(大写的V) 查看gitbook的版本    

`gitbook init`    
初始化目录（建立对应的目录和文件 `README.md`和 `SUMMARY.md`就是这么来的）   

`gitbook build`   
构建书籍源文件，静态HTML文件    
默认会在书籍目录下生成一个 _book 文件夹。书籍的源文件就在里面。
如果你有自己的服务器，你就将 _book 下的所有文件拷贝到自己的服务器上。

`gitbook serve`
构建书籍源文件并启动本地web服务，可以使用浏览器打开 localhost:4000 在本地查看效果
