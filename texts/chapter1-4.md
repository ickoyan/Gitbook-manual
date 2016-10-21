#创建书籍Github-Gitbook-本地
本章节的主要内容是教会大家创建一个与Github相关联的书籍。

Github上通常以一个repository为单位又称项目，在上面写书籍也不是不可以，不过会对那些没有安装Chrome插件的人浏览起来不会方便，因为他们看不到一个类似左边的一个目录。

Gitbook的HTML就解决了这个问题，而Gitbook支持 Github/Git 方式创建数据，这就非常方便我们更新书籍的内容。

##准备工作
首先，确保你的电脑上安装好以下工具：
* [Node.js ](https://nodejs.org/en/)
* [Git](https://git-scm.com/download/win)
* [Atom](https://atom.io/)
* [Gitbook.Editor](https://www.gitbook.com/editor)

Node.js是Gitbook的环境需求，Git是我们同步数据的工具，Atom是写Markdown的工具。Gitbook.Editor是本地Gitbook客户端。     
安装好以上工具并参照之前章节内容安装Gitbook。        
其次你还需要有自己的 [Github](https://github.com/) 账户，没有就赶快注册去吧。

##新建Gitbook书籍
**步骤1：创建Github仓库**    
打开Github网站，登录，并创建新的仓库。    
![](/img/1-4-1.png)

**步骤2：使用Github账户登录Gitbook**
打开Gitbook，点击登录按钮上方的黑粗Github子使用Github方式登录。   
![](/img/1-4-2.png)

**步骤3：以Github/Git方式创建书籍**
登录好后你就拥有了一个自己的Gitbook，现在就可以创建书籍了。点击右上方的NEW，默认显示前3个选项点击下方的箭头会翻页。
* BOOK & MANUAL
* API DOCUMENTATION
* KNOWLEDGE BASE 
* IMPORT A DOCUMENT
* GITHUB
* GIT

![](/img/1-4-3.gif)

我们可以选择Github或者Git,    
选择Github我们可以直接选择Github上我们创建的Reoisutory,   
![](/img/1-4-4.png)   
选择Git我们只有复制Github上Reoisutory的URL粘贴上去就OK了，最后记得Create Book.   
![](/img/1-4-5.png)   

**步骤4：使用Gitbook.Editor导入Gitbook书籍**

**步骤5：使用Atom编辑书籍**
