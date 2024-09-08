---
title: 无序列表
syntax-id: unordered-lists
---

To create an unordered list, add dashes (`-`), asterisks (`*`), or plus signs (`+`) in front of line items. Indent one or more items to create a nested list.

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>Markdown</th>
      <th>HTML</th>
      <th>渲染输出</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code class="highlighter-rouge">
          - First item<br/>
          - Second item<br/>
          - Third item<br/>
          - Fourth item
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
          &lt;ul&gt;<br>
            &nbsp;&nbsp;&lt;li&gt;First item&lt;/li&gt;<br/>
            &nbsp;&nbsp;&lt;li&gt;Second item&lt;/li&gt;<br/>
            &nbsp;&nbsp;&lt;li&gt;Third item&lt;/li&gt;<br/>
            &nbsp;&nbsp;&lt;li&gt;Fourth item&lt;/li&gt;<br/>
          &lt;/ul&gt;
        </code>
      </td>
      <td>
        <ul>
          <li>First item</li>
          <li>Second item</li>
          <li>Third item</li>
          <li>Fourth item</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>
        <code class="highlighter-rouge">
          * First item<br/>
          * Second item<br>
          * Third item<br/>
          * Fourth item
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
          &lt;ul&gt;<br>
            &nbsp;&nbsp;&lt;li&gt;First item&lt;/li&gt;<br/>
            &nbsp;&nbsp;&lt;li&gt;Second item&lt;/li&gt;<br/>
            &nbsp;&nbsp;&lt;li&gt;Third item&lt;/li&gt;<br/>
            &nbsp;&nbsp;&lt;li&gt;Fourth item&lt;/li&gt;<br/>
          &lt;/ul&gt;
        </code>
      </td>
      <td>
        <ul>
          <li>First item</li>
          <li>Second item</li>
          <li>Third item</li>
          <li>Fourth item</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>
        <code class="highlighter-rouge">
          + First item<br/>
          + Second item<br/>
          + Third item<br/>
          + Fourth item
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
          &lt;ul&gt;<br>
            &nbsp;&nbsp;&lt;li&gt;First item&lt;/li&gt;<br/>
            &nbsp;&nbsp;&lt;li&gt;Second item&lt;/li&gt;<br/>
            &nbsp;&nbsp;&lt;li&gt;Third item&lt;/li&gt;<br/>
            &nbsp;&nbsp;&lt;li&gt;Fourth item&lt;/li&gt;<br/>
          &lt;/ul&gt;
        </code>
      </td>
      <td>
        <ul>
          <li>First item</li>
          <li>Second item</li>
          <li>Third item</li>
          <li>Fourth item</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>
        <code class="highlighter-rouge">
          - First item<br/>
          - Second item<br/>
          - Third item<br/>
          &nbsp;&nbsp;&nbsp;&nbsp;- Indented item<br/>
          &nbsp;&nbsp;&nbsp;&nbsp;- Indented item<br/>
          - Fourth item
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
          &lt;ul&gt;<br/>
            &nbsp;&nbsp;&lt;li&gt;First item&lt;/li&gt;<br/>
            &nbsp;&nbsp;&lt;li&gt;Second item&lt;/li&gt;<br/>
            &nbsp;&nbsp;&lt;li&gt;Third item<br/>
              &nbsp;&nbsp;&nbsp;&nbsp;&lt;ul&gt;<br/>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;li&gt;Indented item&lt;/li&gt;<br/>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;li&gt;Indented item&lt;/li&gt;<br/>
              &nbsp;&nbsp;&nbsp;&nbsp;&lt;/ul&gt;<br/>
            &nbsp;&nbsp;&lt;/li&gt;<br/>
            &nbsp;&nbsp;&lt;li&gt;Fourth item&lt;/li&gt;<br/>
          &lt;/ul&gt;
        </code>
      </td>
      <td>
        <ul>
          <li>First item</li>
          <li>Second item</li>
          <li>Third item
            <ul>
              <li>Indented item</li>
              <li>Indented item</li>
            </ul>
          </li>
          <li>Fourth item</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

#### Starting Unordered List Items With Numbers

If you need to start an unordered list item with a number followed by a period, you can use a backslash (`\`) to [escape](#escaping-characters) the period.

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>Markdown</th>
      <th>HTML</th>
      <th>渲染输出</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code class="highlighter-rouge">
          - 1968\. A great year!<br/>
          - I think 1969 was second best.
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
          &lt;ul&gt;<br>
            &nbsp;&nbsp;&lt;li&gt;1968. A great year!&lt;/li&gt;<br/>
            &nbsp;&nbsp;&lt;li&gt;I think 1969 was second best.&lt;/li&gt;<br/>
          &lt;/ul&gt;
        </code>
      </td>
      <td>
        <ul>
          <li>1968. A great year!</li>
          <li>I think 1969 was second best.</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

#### Unordered List Best Practices

Markdown applications don’t agree on how to handle different delimiters in the same list. For compatibility, don't mix and match delimiters in the same list — pick one and stick with it.

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
          - First item<br>
          - Second item<br>
          - Third item<br>
          - Fourth item
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
          + First item<br>
          * Second item<br>
          - Third item<br>
          + Fourth item
        </code>
      </td>
    </tr>
  </tbody>
</table>
