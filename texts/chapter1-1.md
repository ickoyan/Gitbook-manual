#Gitbook简介
> Gitbook是最具潜力的开源书籍编辑平台，每个人都可以制作并发布个人的电子书籍，并能最大程度上利用“群智”提高阅读品质和享受创作过程。

##Gitbook百度百科
Gitbook是一个基于Node.js的命令行工具，可使用Github/Git和Markdown来制作精美的电子书，Gitbook并关于Git的教程。   

Gitbook支持输出多种文档格式：
* 静态站点：Gitbook默认输出该种合适，生成的静态站点可直接托管搭载Github Pages服务上
* PDF：需要安装gitbook-pdf依赖
* eBook：需要安装ebook-convert
* 单HTML网页：支持将内容输出为单页的HTML，不过一般用在将电子书格式转换为PDF或eBook的中间过程
* JSON：一般用于电子书的调试或元数据提取

使用Gitbook制作电子书，必备两个文件：`README.md` 和 `SUMMARY.md`
