---
title: Escaping Characters
syntax-id: escaping-characters
---

要在 Markdown 文档中显示本应用于格式化文本的字符，可以在字符前添加反斜杠 (`\`)。

```
\* 如果没有反斜杠，这将成为无序列表中的一个项目符号。
```

渲染输出看起来是这样的：

\* 如果没有反斜杠，这将成为无序列表中的一个项目符号。

### 可以转义的字符包括

你可以使用反斜杠来转义以下字符：

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>字符</th>
      <th>名称</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>\</td>
      <td>反斜杠</td>
    </tr>
    <tr>
      <td>`</td>
      <td>反引号 (另见 <a href="#escaping-backticks">转义代码中的反引号</a>)</td>
    </tr>
    <tr>
      <td>*</td>
      <td>星号</td>
    </tr>
    <tr>
      <td>_</td>
      <td>下划线</td>
    </tr>
    <tr>
      <td>{ }</td>
      <td>花括号</td>
    </tr>
    <tr>
      <td>[ ]</td>
      <td>中括号</td>
    </tr>
    <tr>
      <td>< ></td>
      <td>角括号</td>
    </tr>
    <tr>
      <td>( )</td>
      <td>小括号</td>
    </tr>
    <tr>
      <td>#</td>
      <td>井号</td>
    </tr>
    <tr>
      <td>+</td>
      <td>加号</td>
    </tr>
    <tr>
      <td>-</td>
      <td>减号（连字符）</td>
    </tr>
    <tr>
      <td>.</td>
      <td>句点</td>
    </tr>
    <tr>
      <td>!</td>
      <td>感叹号</td>
    </tr>
    <tr>
      <td>|</td>
      <td>管道符 (另见 <a href="/extended-syntax/#escaping-pipe-characters-in-tables">表格中的管道符转义</a>)</td>
    </tr>
  </tbody>
</table>
