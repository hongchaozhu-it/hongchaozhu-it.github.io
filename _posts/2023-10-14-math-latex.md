---
title: 数学公式与 LaTeX
author: 朱洪超
date: 2023-10-14
category: Jekyll
layout: post
mermaid: true
---

这个主题支持 [MathJax](https://www.mathjax.org/)，可以在 Markdown 中渲染 $\LaTeX$ 数学公式。

> ##### 提示
>
> 当前 Kramdown 使用双美元符号作为数学公式定界方式，写展示公式时尤其方便。
{: .block-tip }

例如：

```markdown
勾股定理可以写成 $x^2 + y^2 = z^2$。
而下面这个方程在整数范围内没有非零解：

$$ x^n + y^n = z^n $$
```

勾股定理可以写成 $x^2 + y^2 = z^2$。
而下面这个方程在整数范围内没有非零解：

$$ x^n + y^n = z^n $$

再看一个更常见的二次方程求根公式：

```markdown
当 $a \ne 0$ 时，方程 $ax^2 + bx + c = 0$ 的解为：

$$x = {-b \pm \sqrt{b^2-4ac} \over 2a}.$$
```

当 $a \ne 0$ 时，方程 $ax^2 + bx + c = 0$ 的解为：

$$x = {-b \pm \sqrt{b^2-4ac} \over 2a}.$$

如果你的站点会写算法、统计、经济学或课堂笔记，这个能力会非常方便。
