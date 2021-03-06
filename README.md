<h2>新的Wordpress主题——“晓风”</h2>
<img src="https://raw.githubusercontent.com/liyaodong/hybrid-dongdong/master/images/banner.jpg">

很久之前就想着要给自己写一个主题了，但屡屡没有坚持写下去，最近暑假闲了下来，静下心来总算写了一个还算满意的主题，开源出来大家共同改进！
<h3>功能概览</h3>
>1. 支持响应式，兼容PC及移动端平台
2. 支持添加社交网站，QQ空间、微信、微博等
3. 有众多CSS3特效，LOGO旋转、链接浮动、图片模糊等
4. 优化过的文字排版，对各类标签、代码高亮支持较好
5. 一定程度上支持Markdown（其实主要是插件）
6. 图片自适应大小，同时自动检测404错误
7. SVG、Fonts图标，加快响应速度
8. 自行开发的分享栏，无需插件响应更快
9. 针对性的SEO支持，对每个页面、文章和分享都做了SEO优化

<h3>开发工具</h3>
>1. Macbook Pro 
2. Sublime text 2
3. Grunt（用来压缩、合并文件、编译Less、优化图片）
4. Svn、Git
5. Hybird主题框架（多亏有这玩意）
6. Less（通过Grunt来编译）
7. Node（主要是npm，用来安装Grunt）

<h3>安装过程</h3>
>1. 首先安装框架：[Hybird框架](http://wordpress.org/themes/hybrid) 上传到theme即可
2. 到Github下载本主题最新版，不会用Github的同学请自行百度
3. 上传至你的theme目录
4. 修改需要修改的文件，比如LOGO什么的，具体在function.php里有说明
5. 调试、兼容

<h3>To do list</h3>
IE的兼容完全没有看，主要是在Webkit内核的浏览器上，因为我博客访问大多是webkit内核的浏览器，所以也没有管兼容问题。准备再增加个提示功能，当IE进来的时候提示用户切换到极速内核或者下载现代浏览器。毕竟是个人爱好的博客，也懒得管兼容这种事情了。

>1. [github下载](https://github.com/liyaodong/hybird-dongdong)
2. [风格预览](http://liyaodong.com)

<h3>开发心得</h3>
整个开发过程从最开始的茫然、到处找框架，到最后狠下心来使用[Hybird](http://wordpress.org/themes/hybrid)，纠结了两三天。看到别人使用`Node`做的博客反应奇快我就在想我要不要也搞一个`Node`的博客，后来一想什么Node不Node的，先搞一个Wordpress来再折腾Node吧。为什么下决心了？原因是因为我的主机（SAE,新浪云计算）它不支持Node...

这款主题是Hybird的子主题，子主题就是说先把父主题上传到主题目录，然后新建一个文件夹关联到父主题后可以随意改动。子主题中出现的文件会覆盖父主题的文件，这样就保证了不会因为父主题的更新而丢失所修改的东西。看起来很复杂，但是实际上很方便。因为这款框架基本把你能用到的功能都包含了，你只需要在原来很淳朴的样式上修改自己的CSS。如果需要加什么功能，顺藤摸瓜找到原来主题的文件，另存到自己的主题里修改修改就OK了！不罗嗦了，看的再多不如实践，看得上这款主体的就拿去折腾吧！开源万岁！

[原文链接](http://liyaodong.sinaapp.com/1457.html)
