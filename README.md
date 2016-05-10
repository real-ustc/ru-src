# real-ustc.github.io源码

## 准备工作
**安装nodejs与npm**

nodejs官网: https://nodejs.org/en/
安装nodejs后npm会自动安装

**安装hexo**
> npm install -g hexo-cli

**下载源码**
> git clone https://github.com/real-ustc/ru-src.git

**安装hexo-deployer-git**

在blog-src目录下运行
> npm install hexo-deployer-git --save

**安装依赖**

在blog-src目录下运行
> npm install

## 使用
**创建博客**

新建一篇新博客页面
> hexo new TITLE

**生成博客站**

生成静态网站
> hexo g

**部署博客站**

把博客部署到github
> hexo d

**生成并部署博客站**
> hexo d -g

**本地测试**

本地查看效果
浏览器输入localhost:4000 （如果本地有代理可能无法打开，请自行设置）
> hexo s
