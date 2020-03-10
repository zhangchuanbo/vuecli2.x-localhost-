将config文件夹目录下的index.js中的host改为0.0.0.0
![image](https://github.com/zhangchuanbo/vuecli2.x-localhost-/blob/master/QQ%E6%88%AA%E5%9B%BE20200310102857.png)
或者将package.json中的dev 后面加上 --host 0.0.0.0。

最后避免本地启动还应该将webpack.dev.conf.js中的devServer中添加useLocalIp:true//避免自动打开网页时是0.0.0.0
