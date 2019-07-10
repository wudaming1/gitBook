# GitBook使用手册
gitbook是node的一个模块。

1. gitbook -V：查看版本。
2. gitbook init：初始化gitbook项目。
3. gitbook build：命令可以将内容 （Markdown）编译成网页（HTML），生成的网页将存放在目录下的 _book 文件夹中。GitBook 将根据 SUMMARY.md 中的内容来决定被编译的内容，并将它们链接起来。gitbook build [书籍路径] [输出路径]指定路径。
4. gitbook serve：gitbook会启动一个4000端口用于预览，可以在浏览器打开网址。gitbook serve --port 2333，指定端口。
5. npm install gitbook-cli -g:安装。


*注：通常只需单独调用 gitbook serve命令，该命令会事先调用 gitbook build 命令*

## 本地配置介绍
运行publish.py文件即可编译并发布到网站。