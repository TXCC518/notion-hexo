---
categories: Elog-Notion
tags:
  - notion
  - 教程
status: 已发布
permalink: notion-example/
title: Notion示例文章
cover: https://www.notion.so/images/page-cover/met_camille_pissarro_1896.jpg
id: 1240f7bb-9a0b-81d3-8b6f-fdbc7d7b6e75
---

# Notion-Markdown

[Notion 示例文章源地址](https://1874.notion.site/Notion-0658ee89cadf4d0e9b6adfbb1d953c70)

## 行内样式

- **加粗**

_斜体_

<u>下划线</u>

删除线

行内代码 `const a = 123`

行内公式，在 Vitepress 会报错，不做演示

红色的文字

蓝色的文字背景

绿色的块背景

## Basic block（基本块）

## Notion 示例文章的子页面

Notion 示例文章的子页面

| 表格标题 | 备注            |
| -------- | --------------- |
| 测试 1   | 啊大大          |
| 测试 2   | `const a = 123` |

- 无序列表

1. 有序列表：事物按规律变化，也有一种不可避免的性质．这种性质就叫做**必然性** 1. 事物的必然性，是事物本身的性质（我们反对宿命论的是其认为这一切是受神明的支配，而不是反对事物发展中存在的不可避免的性质的事实） 1. 第三级别列表 2. 第三级别列表 2. 其决定于它自己本身发展的情况和周围的条件 1. 第三级别列表 1. 第三级别列表
<details>
<summary>折叠块：点击展开【一级】</summary>
<details>
<summary>点击展开【二级】</summary>
<details>
<summary>点击展开【三级】</summary>

内容文本

</details>

</details>

</details>

123

> 引用块  
> 引用换行  
> 引用换行

> 引用 2  
> 引用 2 换行

---

<aside>
<img class="emoji" draggable="false" alt="👏" src="https://twemoji.maxcdn.com/v/13.1.0/72x72/1f44f.png"/>标注文本：Elog 0.4.0-beta.7 发布了！
开放式跨平台博客解决方案，随意组合写作平台和部署平台

帮助导航 👇
❓ Elog 能干什么
🚀 快速开始

</aside>

## Media（媒体）

![](https://image.1874.cool/moon/cover.JPG)

<div style="width: 100%; margin-top: 4px; margin-bottom: 4px;"><div style="display: flex; background:white;border-radius:5px"><a href="https://elog.1874.cool"target="_blank"rel="noopener noreferrer"style="display: flex; color: inherit; text-decoration: none; user-select: none; transition: background 20ms ease-in 0s; cursor: pointer; flex-grow: 1; min-width: 0px; flex-wrap: wrap-reverse; align-items: stretch; text-align: left; overflow: hidden; border: 1px solid rgba(55, 53, 47, 0.16); border-radius: 5px; position: relative; fill: inherit;"><div style="flex: 4 1 180px; padding: 12px 14px 14px; overflow: hidden; text-align: left;"><div style="font-size: 14px; line-height: 20px; color: rgb(55, 53, 47); white-space: nowrap; overflow: hidden; text-overflow: ellipsis; min-height: 24px; margin-bottom: 2px;">Elog 介绍 | Elog 文档GitHubGitHub</div><div style="font-size: 12px; line-height: 16px; color: rgba(55, 53, 47, 0.65); height: 32px; overflow: hidden;">doc for elog</div><div style="display: flex; margin-top: 6px; height: 16px;"><img src="https://elog.1874.cool/favicon.ico"style="width: 16px; height: 16px; min-width: 16px; margin-right: 6px;"><div style="font-size: 12px; line-height: 16px; color: rgb(55, 53, 47); white-space: nowrap; overflow: hidden; text-overflow: ellipsis;">https://elog.1874.cool</div></div></div></a></div></div>

<div style="width: 100%; margin-top: 4px; margin-bottom: 4px;"><iframe src="https://prod-files-secure.s3.us-west-2.amazonaws.com/ddd4b5f0-a409-4ae2-8ca3-61c898273cfe/5999649b-7796-46a0-abd4-2e17b7b607ab/46_1677164223.mp4?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20241019%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20241019T153128Z&X-Amz-Expires=3600&X-Amz-Signature=93f69b573cde935ba0143bcaaac5d98256ed0387413fd0409e69971ea74defa5&X-Amz-SignedHeaders=host&x-id=GetObject" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true" style="width: 100%; margin:0; aspect-ratio: 16/9;"> </iframe></div>

<div style="width: 100%; margin: 0 0 2px;"><audio controls style="width: 100%; height: 54px;margin:0;"><source src="https://prod-files-secure.s3.us-west-2.amazonaws.com/ddd4b5f0-a409-4ae2-8ca3-61c898273cfe/62bd39fa-f48e-4259-a738-e5ea79b7a250/y1561.wav?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20241019%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20241019T153128Z&X-Amz-Expires=3600&X-Amz-Signature=b7b4166ff682d3adefb0f0a90ba8441a7458b595f86738d46113d7866fd98a0c&X-Amz-SignedHeaders=host&x-id=GetObject" type="audio/mpeg"></audio></div>

```python
pwd='123456'
print(f"password={pwd!r}")

## output:
#password='123456'
```

[example.txt](https://prod-files-secure.s3.us-west-2.amazonaws.com/ddd4b5f0-a409-4ae2-8ca3-61c898273cfe/753c8245-2aea-45de-8a5a-509c105f6236/example.txt?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20241019%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20241019T153128Z&X-Amz-Expires=3600&X-Amz-Signature=3e8bb89653a523e922def2fd2a1dfb8f30133e9d0d9256e575f98950d44d3224&X-Amz-SignedHeaders=host&x-id=GetObject)

## DataBase（数据库）

数据库

## AI block

API 不支持，会报错`Block type ai_block is not supported via the API.`

## Advanced block（高级块）

$$
f\left(\left[\frac{1+\{x, y\}}{\left(\frac{x}{y}+\frac{y}{x}\right)(u+1)}+a\right]^{3 / 2}\right)\tag{行标}
$$

Notion 示例文章的同步块

# 折叠一级标题

    ## 折叠二级标题


    	折叠内容

两列分栏（左）

- [ ] 左侧书写

两列分栏（右）

- [ ] 右侧书写

```mermaid
graph LR;
Mermaid思维导图-->思维导图
Mermaid思维导图-->研发
```

@Anonymous

[Untitled](https://www.notion.so/f478ef37c82a41f1b7a59c195b043831)

2023-04-26

🚀🔥🐸

## Embeds（嵌入）

嵌入网页

<div style="width: 100%; margin: 0 0 2px;"><iframe src="https://elog.1874.cool" style="width: 100%; margin:0; aspect-ratio: 16/9;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe></div>
