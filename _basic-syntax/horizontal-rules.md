---
title: 水平分隔线
syntax-id: horizontal-rules
---

To create a horizontal rule, use three or more asterisks (`***`), dashes (`---`), or underscores (`___`) on a line by themselves.

```
***

---

_________________
```

The 渲染输出 of all three looks identical:

---

### Horizontal Rule Best Practices

For compatibility, put blank lines before and after horizontal rules.

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>✅&nbsp; Do this</th>
      <th>❌&nbsp; Don't do this</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code class="highlighter-rouge">
        Try to put a blank line before...<br><br>

        ---<br><br>

        ...and after a horizontal rule.
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
        Without blank lines, this would be a heading.<br>
        ---<br>
        Don't do this!
        </code>
      </td>
    </tr>
  </tbody>
</table>
