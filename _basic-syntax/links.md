---
title: 链接
syntax-id: links
---

要创建一个链接，请将链接文本放在方括号中（例如，`[Duck Duck Go]`) ，然后紧接着用圆括号包含 URL（例如，`(https://duckduckgo.com)`）。

```
我最喜欢的搜索引擎是 [Duck Duck Go](https://duckduckgo.com).
```

渲染输出看起来是这样的：

我最喜欢的搜索引擎是 [Duck Duck Go](https://duckduckgo.com).

<div class="alert alert-info">
  <i class="fas fa-info-circle"></i> <strong>注意：</strong> 要链接到页面上的某个元素，请参见<a href="/extended-syntax/#linking-to-heading-ids">链接到标题 ID</a>. 要创建一个在新标签页或窗口中打开的链接，请参见<a href="/hacks/#link-targets">链接目标</a>。
</div>

### 添加标题

你可以选择为链接添加标题。这样，当用户将鼠标悬停在链接上时，会显示为工具提示。要添加标题，请在 URL 后用双引号括起来。

```
我最喜欢的搜索引擎是 [Duck Duck Go](https://duckduckgo.com "保护隐私的搜索引擎").
```

渲染输出看起来是这样的：

我最喜欢的搜索引擎是 [Duck Duck Go](https://duckduckgo.com "保护隐私的搜索引擎").

### URL 和电子邮件地址

要快速将 URL 或电子邮件地址转换为链接，请用尖括号括起来。

```
<https://www.markdownguide.org>
<fake@example.com>
```

渲染输出看起来是这样的：

<https://www.markdownguide.org><br/>
<fake@example.com>

### 格式化链接

要对链接进行 [强调](#emphasis)，在方括号和圆括号前后添加星号。要将链接标记为 [代码](#code)，在方括号中添加反引号。

```
我喜欢支持 **[EFF](https://eff.org)**.
这是 *[Markdown 101](https://markdown101.github.io)*.<br/>
查看有关 [`代码`](#code).
```

渲染输出看起来是这样的：

我喜欢支持 **[EFF](https://eff.org)**.<br/>
这是 *[Markdown 101](https://markdown101.github.io)*.<br/>
查看有关 [`代码`](#code).

### 引用风格链接

引用风格链接是一种特殊类型的链接，使 URL 在 Markdown 中更易于显示和阅读。引用风格链接分为两部分：一部分嵌入到文本中，另一部分存储在文件的其他地方，以保持文本的可读性。

#### 格式化链接的第一部分

引用风格链接的第一部分由两组方括号组成。第一组方括号包含要显示为链接的文本。第二组方括号显示一个标签，用于指向你在文档其他地方存储的链接。

虽然不是必需的，但你可以在第一组和第二组方括号之间添加空格。第二组方括号中的标签不区分大小写，可以包含字母、数字、空格或标点符号。

这意味着以下示例格式在链接的第一部分是大致等效的：

- `[霍比特人洞穴][1]`
- `[霍比特人洞穴] [1]`

#### 格式化链接的第二部分

引用风格链接的第二部分格式化具有以下属性：

1. 标签，使用方括号括起来，紧接着是冒号和至少一个空格（例如 `[label]: `）。
2. 链接的 URL，你可以选择用尖括号括起来。
3. 链接的可选标题，你可以用双引号、单引号或圆括号括起来。

这意味着以下示例格式在链接的第二部分大致等效：

- `[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle`
- `[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle "霍比特人的生活方式"`
- `[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle '霍比特人的生活方式'`
- `[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle (霍比特人的生活方式)`
- `[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "霍比特人的生活方式"`
- `[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> '霍比特人的生活方式'`
- `[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> (霍比特人的生活方式)`

你可以将链接的第二部分放在 Markdown 文档中的任何位置。有些人将它们放在出现的段落之后，而其他人则将其放在文档的末尾（类似于尾注或脚注）。

#### 将两部分组合在一起

假设你将一个 URL 作为 [标准 URL 链接](#links) 添加到一个段落中，在 Markdown 中，它看起来像这样：

```
在地面下的一个洞里住着一个霍比特人。
不是一个肮脏、潮湿的洞，充满了虫子的末端和恶心的气味，也不是一个干燥、光秃秃的沙土洞，里面没有可以坐下或吃东西的东西：这是一个 [霍比特人洞穴](https://en.wikipedia.org/wiki/Hobbit#Lifestyle "霍比特人的生活方式")，这意味着舒适。
```

虽然它可能指向有趣的附加信息，但显示的 URL 实际上并没有为现有的原始文本增加太多内容，反而使其更难阅读。为了解决这个问题，你可以将 URL 格式化成这样：
```
在地面下的一个洞里住着一个霍比特人。不是一个肮脏、潮湿的洞，充满了虫子的末端和恶心的气味，也不是一个干燥、光秃秃的沙土洞，里面没有可以坐下或吃东西的东西：这是一个 [霍比特人洞穴][1]，这意味着舒适。
[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "霍比特人的生活方式"
```

在上述两种情况中，渲染输出将是相同的：

> 在地面下的一个洞里住着一个霍比特人。不是一个肮脏、潮湿的洞，充满了虫子的末端和恶心的气味，也不是一个干燥、光秃秃的沙土洞，里面没有可以坐下或吃东西的东西：这是一个 <a href="https://en.wikipedia.org/wiki/Hobbit#Lifestyle" title="霍比特人的生活方式">霍比特人洞穴</a>，这意味着舒适。

链接的 HTML 将是：

```
<a href="https://en.wikipedia.org/wiki/Hobbit#Lifestyle" title="霍比特人的生活方式">霍比特人洞穴</a>
```

### 链接最佳实践

Markdown 应用程序在处理 URL 中间的空格时并不一致。为了兼容性，尽量使用 `%20` 对空格进行 URL 编码。或者，如果你的 Markdown 应用程序 [支持 HTML](#html)，你可以使用 `a`  HTML 标签。

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>✅&nbsp; 正确做法</th>
      <th>❌&nbsp; 错误做法</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code class="highlighter-rouge">
        [link](https://www.example.com/my%20great%20page)<br><br>
        &lt;a href="https://www.example.com/my great page"&gt;link&lt;/a&gt;
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
        [link](https://www.example.com/my great page)
        </code>
      </td>
    </tr>
  </tbody>
</table>