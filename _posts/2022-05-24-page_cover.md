---
title: 带封面图的文章示例
author: 朱洪超
date: 2022-05-24
category: Jekyll
layout: post
cover: /assets/dinosaur.gif
---

这篇文章演示封面图效果。你只需要在文章头信息里增加一个 `cover` 字段，就可以让页面顶部显示大图。

```diff
  ---
  title: 带封面图的文章示例
  author: 朱洪超
  date: 2022-05-24
  category: Jekyll
  layout: post
+ cover: /assets/dinosaur.gif
  ---
```

封面图适合用在以下几类页面：

- 专题文章
- 首页推荐内容
- 项目介绍页
- 长篇教程开篇

如果你的站点部署在带 `baseurl` 的路径下，封面图路径也要一并考虑进去。这个仓库里已经顺手补了相对路径兼容，直接使用站点内资源即可。
