# hugo-theme-jsimple
## 基于HEXO主题jsimple移植的Hugo主题
预览: [demo](https://jsimple.hojun.cn)

![](https://cdn.jsdelivr.net/gh/honjun/ImageHosting/picgo/20190814201913.jpg)

主题配置参考B站视频教程：[bilibili](https://www.bilibili.com/video/av63723072/)

欢迎提交文字教程PR
## 2019.6.站内搜索
感谢[lunr.js](https://github.com/olivernn/lunr.js)和[hugo-lunr](https://github.com/dgrigg/hugo-lunr)。
本插件基于hugo-lunr修改，仅适配hugo-theme-diaspora主题，其他主题需自行修改。
先安装插件（需要安装npm工具）
```cmd
npm i hugo-lunr-diaspora
```
然后在博客根目录下新建package.json，增加如下内容
```json
{
  "scripts": {
    "index": "hugo-lunr"
  }
}
```
最后cd到博客根目录下运行`npm run index`生成lunr.json文件即可以使用站内搜索。
注意更新文章后需要更新lunr.json文件。
To Be Continued...