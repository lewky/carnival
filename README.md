## carnival

forked from https://github.com/nd002723/carnival

一个能让你的网站high起来的js！

这是原作者原项目的GitHub Pages：https://nd002723.github.io/carnival

本项目修改了bgm，压缩了音乐文件大小，修改了代码里引入的文件路径，改用cdn来提高国内访问速度。

这是一个使用了该js的样例页面：https://lewky.cn/high

## 使用方法

在网站头部引用`carnival.js`：
```javascript
<script src="https://cdn.jsdelivr.net/gh/lewky/carnival@master/js/carnival.js"></script>
```

或者你可以直接新建一个浏览器书签，地址填下面这个：
```javascript
//拖动到书签栏 或者手动输入(PS：点击预览)
javascript:void(function(){var d = document,a = 'setAttribute',s = d.createElement('script');s[a]('tyle','text/javascript');s[a]('src','https://cdn.jsdelivr.net/gh/lewky/carnival@master/js/carnival.js');d.head.appendChild(s);})();
```
