---
title: Images
syntax-id: images
---

要添加图片，请在 Markdown 文本中使用感叹号 (`!`)，后跟方括号中的替代文本，再加上圆括号中的图片路径或 URL。你可以选择性地在路径或 URL 后加上双引号中的标题。

```
![圣胡安山脉非常美丽！](/assets/images/san-juan-mountains.jpg "圣胡安山脉")
```

渲染输出看起来是这样的：

{% include image.html file="/assets/images/san-juan-mountains.jpg" alt="圣胡安山脉非常美丽！" title="圣胡安山脉" lazy="yes" %}

<div class="alert alert-info">
  <i class="fas fa-info-circle"></i> <strong>注意：</strong> 要调整图片大小，请参见关于 <a href="/hacks/#image-size">图片大小</a>. 要添加标题，请参见关于 <a href="/hacks/#image-captions">图片标题</a>.
</div>

### 链接图片

要给图片添加链接，请将图片的 Markdown 语法放在方括号中，然后在圆括号中添加链接。

```
[![沙漠中的一块古老岩石](/assets/images/shiprock.jpg "新墨西哥州的船岩，摄影：Beau Rogers")](https://www.flickr.com/photos/beaurogers/31833779864/in/photolist-Qv3rFw-34mt9F-a9Cmfy-5Ha3Zi-9msKdv-o3hgjr-hWpUte-4WMsJ1-KUQ8N-deshUb-vssBD-6CQci6-8AFCiD-zsJWT-nNfsgB-dPDwZJ-bn9JGn-5HtSXY-6CUhAL-a4UTXB-ugPum-KUPSo-fBLNm-6CUmpy-4WMsc9-8a7D3T-83KJev-6CQ2bK-nNusHJ-a78rQH-nw3NvT-7aq2qf-8wwBso-3nNceh-ugSKP-4mh4kh-bbeeqH-a7biME-q3PtTf-brFpgb-cg38zw-bXMZc-nJPELD-f58Lmo-bXMYG-bz8AAi-bxNtNT-bXMYi-bXMY6-bXMYv)
```

渲染输出看起来是这样的：

<div>
  <a href="https://www.flickr.com/photos/beaurogers/31833779864/in/photolist-Qv3rFw-34mt9F-a9Cmfy-5Ha3Zi-9msKdv-o3hgjr-hWpUte-4WMsJ1-KUQ8N-deshUb-vssBD-6CQci6-8AFCiD-zsJWT-nNfsgB-dPDwZJ-bn9JGn-5HtSXY-6CUhAL-a4UTXB-ugPum-KUPSo-fBLNm-6CUmpy-4WMsc9-8a7D3T-83KJev-6CQ2bK-nNusHJ-a78rQH-nw3NvT-7aq2qf-8wwBso-3nNceh-ugSKP-4mh4kh-bbeeqH-a7biME-q3PtTf-brFpgb-cg38zw-bXMZc-nJPELD-f58Lmo-bXMYG-bz8AAi-bxNtNT-bXMYi-bXMY6-bXMYv" class="no-underline">
  {% include image.html file="/assets/images/shiprock.jpg" alt="沙漠中的一块古老岩石" title="新墨西哥州的船岩，摄影：Beau Rogers" lazy="yes" %}
  </a>
</div>

