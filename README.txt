按照我的博客 https://blog.xbreeding.com 说明设置应用ID授权，获得 {授权appID}，其中到Redirect URIs ，除了http://localhost:3000/，还要增加自己的部署所用的https://网址到Redirect URIs，不然可能子账号登录会报Redirect URIs不相符的错（需要ssl安全认证的https://域名）

此库基于2020年4月10日原项目github最新版(为了防查，具体来源看博客)，编译打包形成的静态网址文件，此库只作为 github page 和 下载部署到自己空间域名使用，（本库中已进行了{授权appID}的替换，需要替换文件，请到https://github.com/setdiaoyong/teamAPI）。


一、以下是github PAGE 部署说明：

1、在setdiaoyong/teamAPI.git 库中，拉取到自己的github，在settings中将库名，改成自己的github用户名.github.io，分别打开static\js\main.b09a1c35.chunk.js和build\static\js\main.b09a1c35.chunk.js.map 分别搜索 {授权appID} ，将 {授权appID}  连 { }挂号一起替换成至自己设置好的app ID
 
3、参考https://blog.csdn.net/yuexianchang/article/details/53431703  设置githubpage，好像也就改个库名，其他自动识别，在下拉页面，看到github page 选项打钩，就说明部署成功，访问后，登录自己子账号，创建一下team的meeting，就可以了。

4、他人子账户登录需要对应管理员授权，还在测试哪种授权可以允许登录。

5、已验证，该静态文件可部署，欢迎注册https://setdiaoyong.github.io  （此api开的比较早，是所有类型微软账号都可以登录的）


二、如果部署到自己的空间和域名

请打包下载https://github.com/setdiaoyong/teamAPI ，点击绿色图标code，下载zip压缩包。一样按照博客，进行之前的操作。



