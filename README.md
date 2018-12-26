# ARFA 教堂
## 官方博客。

这里是 ARFA 教堂的官方博客。

使用 Netlify 自动部署，请在 GitHub 仓库上修改代码。

以下是对于没有接触过 Hexo 的成员的不完全教程。

---

写文章，请在开头加上这样一段：

```plain
---
title: "xxxxx"
date: xxxx-xx-xx xx:xx
id: hello-world
tag:
  - xxx1
  - xxx2
  - xxx3
category: xxx
---
```

看英文应该能懂。  
特别地，`id` 是文章的 URL 标识符。

其中，加入这样一行：

```plain
<!--more-->
```

会使该行以上的内容成为显示在首页的摘要内容。

此外，如果要使用 LaTeX，注意一些可能与 markdown 冲突的语法使用 `\` 转义。

例如：`$\sum\limits_{i=1}^n{a_i}$` 请改为 `$\\sum\\limits\_{i=1}^n{a\_i}$`。

还有一些奇怪的东西可以在[这里](https://hexo.io/docs/tag-plugins.html)和[这里](http://theme-next.iissnan.com/tag-plugins.html)找到。