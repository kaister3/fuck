开始用 stagehand 新建了一个项目，完全好用

然后拿 webstorm 创建了一个模板文件，反而不好用了

打开浏览器是404 not found

找了半天错误发现是 webdev 这个服务器程序没启动

那么，如何启动呢

我在 webstorm 的终端里试了，不行

改了 webstorm 端口，不行

后来发现右键点击 pubspec有一个 web build

试了试，果然可以

然后运行，但是端口被占用

我就把 preference->dart->webdev port改成之前默认的53322

运行，成功了

舒服

虽然耽误了20分钟时间
