---
layout: default
title: API
description: 以编程方式访问 Markdown 文档。
last_modified_at: 2018-10-18
---

## 介绍

Markdown 101 API 提供了JSON 格式的 Markdown 101 文档子集。我们希望软件开发人员和组织使用此 API 以编程方式使用我们的文档并将其显示在应用程序和网站上。

### 为什么？

为什么要为 Markdown 文档创建 API？因为网络上有太多重复的 Markdown 文档！似乎每个人都有自己的应用程序或网站版本的 Markdown 文档。这是一个耻辱，因为它大部分是完全相同的。

然后是顿悟。💡 我们意识到我们可以使用 *Markdown 101* 中的文档创建 JSON API 。这样，软件开发人员可以开始使用 API 将我们的文档包含在他们的应用程序中，而大学和图书馆等组织可以使用 API 将我们的文档包含在他们的网站上。

我们很乐意看到 *Markdown 101* 成为散布在互联网上的数千条 Markdown 指令的中央文档存储库。它会起作用吗？谁知道！有一件事是肯定的：我们迫不及待地想看看你用它做了什么。🤘

### 限制

Markdown 101 API 旨在仅提供基本的 Markdown 文档。因此，API 不包括 *Markdown 101*  网站上提供的所有文档。例如[在列表中添加元素](/basic-syntax/#adding-elements-in-lists)部分不能通过基本语法端点使用。

## 基本语法端点

基本语法端点包含有关在 John Gruber 的设计文档中概述并在[基础语法页面](/basic-syntax/)上描述的 Markdown 元素的文档。

<div class="card">
  <h6 class="card-header no-anchor" data-toc-skip>API 端点</h6>
  <div class="card-body"><a href="/api/v1/basic-syntax.json">/api/v1/basic-syntax.json</a></div>
</div>

### Request

`curl https://www.markdownguide.org/api/v1/basic-syntax.json`

### Response

<script src="https://gist.github.com/mattcone/a0103c47bdac8bf81a54b29f650e5cb2.js"></script>

## 速查表端点

速查表端点概述了最流行的基本和扩展 Markdown 语法元素，如[速查表](/cheat-sheet/)页面所述。

<div class="card">
  <h6 class="card-header no-anchor" data-toc-skip>API 端点</h6>
  <div class="card-body"><a href="/api/v1/cheat-sheet.json">/api/v1/cheat-sheet.json</a></div>
</div>

### Request

`curl https://www.markdownguide.org/api/v1/cheat-sheet.json`

### Response

<script src="https://gist.github.com/mattcone/ec8057127a0ff2e0b45d2cde14355b2a.js"></script>

## 变更日志

这是我们对 Markdown Guide API 所做的所有更改的列表。

```
2018-10-18
- Updated cheat sheet endpoint to include information about definition lists

2018-07-12
- Updated links description to include information about adding titles

2017-11-10
- Added cheat sheet endpoint

2017-11-04
- Added section about escaping backticks in code

2017-10-24
- Released API v1
- Published docs
```
