Title: 測試
Date: 2015-09-30 16:12
Modified: 2015-09-30 16:12
Category: Python
Tags: pelican, publishing
Slug: 2015cp_test
Authors: b850617
Summary: 測試 一 test
以下為作業一內容

利用 iframe 嵌入投影片:

<iframe src="simplest.html" width="400" height="200"></iframe>

[作業一投影片](simplest2.html){:target="_blank"}

使用 H1 標題
============

<div style="position:relative;width:267px;height:25px;overflow:hidden;">
  <div style="position:absolute;top:-276px;left:-5px">
    <iframe width="300" height="300" 
      src="https://www.youtube.com/embed/z0kGDLzZ05E?rel=0">
    </iframe>
  </div>
</div>

<br>

<div style="position:relative;width:267px;height:25px;overflow:hidden;">
  <div style="position:absolute;top:-276px;left:-5px">
    <iframe width="300" height="300" 
      src="https://www.youtube.com/embed/Jp2TFRqOOOs?rel=0">
    </iframe>
  </div>
</div>



文字段落間若要跳行, 必須插入空白行, 否則將會被 Markdown 視連續的資料

使用. *斜體文字*, **黑體文字**, 以及 `單線文字`. 表列資料可以寫為:
~~~
 * 456
  * 123
  * 789
~~~


使用註腳 [^1].


123

[^1]: 註腳會連結到這裡.


<iframe src="https://player.vimeo.com/video/137724068" width="500" height="281" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe> <p><a href="https://vimeo.com/137724068">Welcome Speech</a> from <a href="https://vimeo.com/user24079973">虎尾科大機械設計工程系 KMOL</a> on <a href="https://vimeo.com">Vimeo</a>.</p>
