---
title: 块引用
syntax-id: blockquotes
syntax-summary: "> blockquote"
description: "要创建块引用，请在段落前添加一个 `>` 符号。"
examples:
  - markdown: "> Dorothy followed her through many of the beautiful rooms in  her castle."
    html: "<blockquote><p>Dorothy followed her through many of the beautiful rooms in her castle.</p></blockquote>"
additional-examples:
  - name: "Blockquotes with Multiple Paragraphs"
    description: "Blockquotes can contain multiple paragraphs. Add a `>` on the blank lines between the paragraphs."
    markdown: |
      > Dorothy followed her through many of the beautiful rooms in her castle.
      >
      > The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.
    html: "<blockquote><p>Dorothy followed her through many of the beautiful rooms in her castle.</p><p>The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.</p></blockquote>"
  - name: "Nested Blockquotes"
    description: "Blockquotes can be nested. Add a `>>` in front of the paragraph you want to nest."
    markdown: |
      > Dorothy followed her through many of the beautiful rooms in her castle.
      >
      >> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.
    html: "<blockquote><p>Dorothy followed her through many of the beautiful rooms in her castle.</p><blockquote><p>The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.</p></blockquote></blockquote>"
  - name: "Blockquotes with Other Elements"
    description: "Blockquotes can contain other Markdown formatted elements. Not all elements can be used — you'll need to experiment to see which ones work."
    markdown: |
      > ### The quarterly results look great!
      >
      > - Revenue was off the chart.
      > - Profits were higher than ever.
      >
      >  *Everything* is going according to **plan**.
    html: "<blockquote><h3>The quarterly results look great!</h3><ul><li>Revenue was off the chart.</li><li>Profits were higher than ever.</li></ul><p><em>Everything</em> is going according to <strong>plan</strong>.</p></blockquote>"
---

要创建块引用，请在段落前添加一个 `>` 符号。

```
> Dorothy followed her through many of the beautiful rooms in her castle.
```

渲染输出如下所示：

> Dorothy followed her through many of the beautiful rooms in her castle.

### 带有多个段落的块引用

块引用可以包含多个段落。在段落之间的空白行上添加一个 `>` 符号。

```
> Dorothy followed her through many of the beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.
```

渲染输出如下所示：

> Dorothy followed her through many of the beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

### 嵌套块引用

块引用可以嵌套。在要嵌套的段落前面添加一个 `>>` 符号。

```
> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.
```

渲染输出如下所示：

> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

### 带有其他元素的块引用

块引用可以包含其他 Markdown 格式的元素。并非所有元素都可以使用——你需要尝试看看哪些元素有效。

```
> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
>  *Everything* is going according to **plan**.
```

渲染输出如下所示：

> <h4 class="no-anchor">The quarterly results look great!</h4>
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
> *Everything* is going according to **plan**.

### 块引用的最佳实践

For compatibility, put blank lines before and after blockquotes.

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
        尝试在前面放一个空行...<br><br>

        > 这是一个块引用<br><br>

        ...在一个块引用之后。
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
        如果没有空行，这可能看起来不正确。<br>
        > 这是一个块引用<br>
        不要这样做！
        </code>
      </td>
    </tr>
  </tbody>
</table>