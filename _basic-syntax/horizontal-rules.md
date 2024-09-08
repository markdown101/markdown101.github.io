---
title: 水平分隔线
syntax-id: horizontal-rules
---

要创建水平线，可以在单独一行上使用三个或更多的星号 (`***`), 破折号 (`---`) 或下划线 (`___`) 。

```
***

---

_________________
```

所有三种方式的渲染输出效果相同：

---

### 水平线最佳实践

为了兼容性，请在水平线的前后留出空行。

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
            尽量在水平线之前留出一个空行...<br><br>
            ---<br><br>
            ...以及在水平线之后留出一个空行。
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
            如果没有空行，这将会是一个标题。<br>
            ---<br>
            不要这样做！
        </code>
      </td>
    </tr>
  </tbody>
</table>
