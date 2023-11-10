## ZenMind Hexo Theme
ZenMind 是一款 [Hexo](https://hexo.io/) 简洁单栏主题。其名来源于中文「静思」，寓意深入思考与宁静的心境。
这款主题旨在为读者和作者提供一个简洁、宁静的阅读与写作环境。

由 [@lenchou95](https://twitter.com/lenchou95) 修改自 [one-paper](https://github.com/zheli-design/hexo-theme-one-paper)

## Live Demo

预览：[https://imzl.com/zenmind](https://imzl.com/zenmind)

![ZenMind 预览图](/source/img/screenshot.png)

## 功能

-   响应式设计，兼容手机端、Pad 端以及 PC 端；
-   支持所有现代浏览器；
-   Markdown 常用格式支持；
-   代码高亮、行数显示支持；
-   目前版本支持的模版页：首页、文章详情页、归档页、单页；
-   中英文兼容，显示良好；
-   不支持评论。


## 安装
1. 克隆仓库到 Hexo themes 目录：
`git clone https://github.com/yourusername/ZenMind.git themes/ZenMind`
2. 修改 Hexo 配置文件 `_config.yml`，将 `theme` 字段值改为 `ZenMind`；
3. 运行 `hexo serve` 预览主题效果。

## 已开启高亮代码

主题内置了 [highlightjs](https://highlightjs.org/) 以及 [highlightjs-line-numbers.js](https://github.com/wcoder/highlightjs-line-numbers.js) 两个插件，默认启用，无需手动开启。如无效果，请将 hexo/_config.yml 中的以下两处 `true` 改为 `false`：

```yml
highlight:
  enable: false
prismjs:
  enable: false
```

## 更换 favicon

请同命名覆盖替换 `source/img/favicon.ico` 文件；

如你需要使用 `.png` 格式，可在 `layout/_partial/head.ejs` Favicon 处修改。

## 更换 apple-touch-icon
请同命名覆盖替换 `source/img/apple-touch-icon.png` 图片。

## 其他

-   如果你觉得主题不错，欢迎分享出去；使用中遇到问题，可以在 [GitHub Issues](https://github.com/LenChou95/hexo-theme-ZenMind/issues) 提交反馈；
-   可以在 [twitter](https://twitter.com/lenchou95) 与我取得联系。


## 作者

[Len Chou](https://twitter.com/lenchou95/) <[imzl.com](https://imzl.com)>


## 版权声明

遵守 [MIT License](https://zh.wikipedia.org/wiki/MIT許可證) 协议
