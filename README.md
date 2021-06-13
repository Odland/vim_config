## 个人vim插件的管理与配置
*好久以前做的vim插件配置，没怎么管过，最近更新记录一下，以备以后更新使用*
- 可以在命令模式下使用plug对插件进行手动更新、安装、删除等操作
- 使用Vim插件管理程序vim-plug，管理Vim使用的插件
- 使用时将vim_conf内容导入到home目录下.vimrc文件即可
- 程序会检测是否有plug，如果没有会自动下载plug
- 下载所需插件时，在call  plug#begin 与 call plug#end() 之间填写插件地址，plug会自动下载，这里写的是github地址的缩写也可以用完整的地址
- 可以根据自己的需要对插件进程设置
- 直连会很慢，有条件搭代理的，可以为github设置代理地址： `git config --global https.https://github.com.proxy socks5://127.0.0.1:1080`
- repl插件不错，还是国人写的，在打开py文件时，会自动加载一个对应的shell
