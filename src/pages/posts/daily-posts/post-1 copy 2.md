---
layout: ../../../layouts/MarkdownPostLayout.astro
title: 'My First Blog Post'
pubDate: 2022-07-01
description: 'This is the first post of my new Astro blog.'
author: 'Astro Learner'
tags: ["astro", "blogging", "learning in public"]
source: '翻译,https://github.com/withastro/astro/blob/main/examples/basic/src/pages/index.astro'
---

## What I've accomplished

1. **Installing Astro**: First, I created a new Astro project and set up my online accounts.

2. **Making Pages**: I then learned how to make pages by creating new `.astro` files and placing them in the `src/pages/` folder.

3. **Making Blog Posts**: This is my first blog post! I now have Astro pages and Markdown posts!

## What's next

I will finish the Astro tutorial, and then keep adding more posts. Watch this space for more to come.

## 图片展示效果

下面是一张示例图片，用来测试博客中图片的显示效果：

![Astro Logo](https://astro.build/assets/press/astro-logo-dark.png)

这张图片展示了 Astro 的官方 Logo。让我们看看它在博客中的渲染效果如何。

### 本地图片示例

如果你想使用本地图片，可以将图片放在 `public/assets/images/` 目录下，然后这样引用：

```markdown
![本地图片示例](/assets/images/example.jpg)
```

### 图片样式说明

- 图片会自动适应容器宽度
- 支持 alt 文本用于无障碍访问
- 可以添加标题属性用于悬浮提示