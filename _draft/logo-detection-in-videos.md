---
layout: post
title: 机器视觉：视频logo检测
categories: [机器视觉]
tags: 计算机视觉
---

> 古之所谓豪杰之士者，必有过人之节，人情有所不能忍者。匹夫见辱，拔剑而起，挺身而斗，此不足为勇也。天下有大勇者，卒然临之而不惊，无故加之而不怒。此其所挟持者甚大，而其志甚远也。

在视频、图片社交、电商等领域，常常会面临logo检测方面的需求，作为物体检测的细分领域，logo检测有其自身的一些特性，具体表现为：

- logo样式多变
- 小尺寸
- 易受背景

当然除了上面它独有的一些比较难的特性外，也有一些比较好的先验特性供利用，比如同一logo样式是刚性的，并且在视频、图片社交应用上，大部分logo都分布在图片的四个角落和中间位置。这篇博文，是小白菜关于短视频行业logo检测一些浅薄的思考和总结。


