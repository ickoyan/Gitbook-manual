#Gitbook插件
插件可以让你的文章显得更加生动，比如：添加一段视频、添加评论功能、分享功能、给文字添加颜色等，总之，学习插件是Gitbook的高级使用方式。

Gitbook插件地址：https://plugins.gitbook.com/

Gitbook插件的使用步骤：
* npm命令安装插件
* 在book.json中启用插件

##Ace 
代码编辑插件，支持插入代码片段并高亮显示，支持110中编程语言。

本地安装：   
`npm install gitbook-plugin-ace`

启用：   
`"pluglins":["ace"]`


##Emphasize
为文字添加底色

本地安装：   
`npm install gitbook-plugin-emphasize`

启用：   
`"pluglins":["emphasize"]`

示例：   

This text is {% em %}highlighted !{% endem %}

This text is {% em %}highlighted with **markdown**!{% endem %}

This text is {% em type="green" %}highlighted in green!{% endem %}

This text is {% em type="red" %}highlighted in red!{% endem %}

This text is {% em color="#ff0000" %}highlighted with a custom color!{% endem %}
