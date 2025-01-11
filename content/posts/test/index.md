---
title: "测试"
description: "了解如何将文章分组到系列中。"
externalUrl:
editURL:
editAppendPath:
groupByYear:
menu:
robots:
sharingLinks:
showAuthor:
showAuthorBottom:
authors: ["sarom"]
showAuthorsBadges:
featureimage:
featureimagecaption:
showHero:
heroStyle:
showBreadcrumbs:
showDate:
showDateUpdated:
showEdit:
showHeadingAnchors:
showPagination:
invertPagination:
showReadingTime:
showTaxonomies:
showTableOfContents:
showWordCount:
showComments:
showSummary:
showViews:
showLikes:
seriesOpened: true
series: ["测试"]
series_order: 1
summary: sfasdfasdfasdfasdfafd
draft: false
slug: "series"
tags: ["1", "2"]
date: "2024-12-21"
author: "sarom"
---

这篇文章提供了一些基础的 Markdown 语法样例，这些可以在 Hugo 的内容文件中使用。

<!--more-->

{{< alert >}}
**警告！**此操作具有破坏性！
{{< /alert >}}

---

{{< alert "twitter" >}}
Don't forget to [follow me](https://twitter.com/nunocoracao) on Twitter.
{{< /alert >}}

---

{{< alert icon="fire" cardColor="#e63946" iconColor="#1d3557" textColor="#f1faee" >}}
This is an error!
{{< /alert >}}

---

{{< article link="/docs/series/" >}}

---

{{< badge >}}
New article!
{{< /badge >}}

---

{{< button href="#button" target="_self" >}}
Call to action
{{< /button >}}

---

{{< carousel images="{https://cdn.pixabay.com/photo/2016/12/11/12/02/mountains-1899264_960_720.jpg, gallery/03.jpg, gallery/01.jpg, gallery/02.jpg, gallery/04.jpg}" >}}

---

{{< carousel images="gallery/*" aspectRatio="21-9" interval="2500" >}}

---

{{< chart >}}
type: 'bar',
data: {
  labels: ['Tomato', 'Blueberry', 'Banana', 'Lime', 'Orange'],
  datasets: [{
    label: '# of votes',
    data: [12, 19, 3, 5, 3],
  }]
}
{{< /chart >}}

---

{{< katex >}}
\\(f(a,b,c) = (a^2+b^2+c^2)^3\\)

