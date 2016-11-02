#Gitbook插件
插件可以让你的文章显得更加生动，比如：添加一段视频、添加评论功能、分享功能、给文字添加颜色等，总之，学习插件是Gitbook的高级使用方式。

Gitbook插件地址：https://plugins.gitbook.com/

Gitbook插件的使用步骤：
* npm命令安装插件
* 在book.json中启用插件   

注：在使用npm安装插件的时候，确保在你的书籍目录下出现 `node_modules` 文件夹，要使你的书籍在Gitbook上正确显示安装插件的效果，确保上传插件文件的内容哦。

##ace 
代码编辑插件，支持插入代码片段并高亮显示，支持110中编程语言。

本地安装：   
```
npm install gitbook-plugin-ace
```

启用：   
```json
"pluglins":["ace"]
```


##emphasize
为文字添加底色

本地安装：   
```
npm install gitbook-plugin-emphasize
```

启用：  
```json 
"pluglins":["emphasize"]
```

示例：   
```
This text is {% em %}highlighted !{% endem %}

This text is {% em %}highlighted with **markdown**!{% endem %}

This text is {% em type="green" %}highlighted in green!{% endem %}

This text is {% em type="red" %}highlighted in red!{% endem %}

This text is {% em color="#ff0000" %}highlighted with a custom color!{% endem %}
```

##local-video
在页面上键入视频

本地安装：
```   
npm install gitbook-plugin-local-video
```

启用： 
```json  
"plugins": [ "local-video" ]
```

使用示例：为了使视频可以自适应，我们指定视频的width为100%，并设置宽高比为16:9，如下面所示

网页播放mp4视频，出现有声音无图像问题，先使用格式工厂转换mp4->mp4格式,输出编码选择AVC(H264),然后在网页中代码调用，看是否解决问题。
<!-- poster="http://zhangjikai.com/resource/poster.jpg" -->
```
{% raw %}
<video id="my-video" class="video-js" controls preload="auto" width="100%" 
 data-setup='{"aspectRatio":"16:9"}'>
  <source src="http://120.25.195.103/mine/mv/sss.mp4" type='video/mp4' >
  <p class="vjs-no-js">
    To view this video please enable JavaScript, and consider upgrading to a web browser that
    <a href="http://videojs.com/html5-video-support/" target="_blank">supports HTML5 video</a>
  </p>
</video>
{% endraw %}
```

{% raw %}
<video id="my-video" class="video-js" controls preload="auto" width="100%" 
 data-setup='{"aspectRatio":"16:9"}'>
  <source src="http://120.25.195.103/mine/mv/sss.mp4" type='video/mp4' >
  <p class="vjs-no-js">
    To view this video please enable JavaScript, and consider upgrading to a web browser that
    <a href="http://videojs.com/html5-video-support/" target="_blank">supports HTML5 video</a>
  </p>
</video>
{% endraw %}

另外我们还要再配置下css，即在website.css中加入

    .video-js {
        width:100%;
        height: 100%;
    }
