---
title: Image gallery
description: Create beautiful interactive image gallery using Markdown
date: 2023-08-26 00:00:00+0000
image: 2.jpg
---

Hugo theme Stack supports the creation of interactive image galleries using Markdown. It's powered by [PhotoSwipe](https://photoswipe.com/) and its syntax was inspired by [Typlog](https://typlog.com/).

To use this feature, the image must be in the same directory as the Markdown file, as it uses Hugo's page bundle feature to read the dimensions of the image. **External images are not supported.**

## Syntax

```markdown
![Image 1](1.jpg) ![Image 2](2.jpg)
```

## Result

Inside links:

![Image 1](1.jpg) ![Image 2](2.jpg)

External links:

![Image 1](https://user-images.githubusercontent.com/5889006/190859441-141b5f81-8483-40d2-bd96-ebf85616a46d.png) ![Image 2](https://cn.bing.com/th?id=OHR.CheetahDay_EN-CN5641048727_1920x1080.webp&qlt=50) ![Image 3](https://cn.bing.com/th?id=OHR.ManateeMama_EN-US7376333243_UHD.jpg&pid=hp&w=1920&h=1080&rs=1&c=4)

> Photo by [mymind](https://unsplash.com/@mymind) and [Luke Chesser](https://unsplash.com/@lukechesser) on [Unsplash](https://unsplash.com/)
