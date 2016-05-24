---
layout: default
---

<body>
  <div class="index-wrapper">
    <div class="aside">
      <div class="info-card">
        <h1>Eidosper</h1>
        <a href="http://weibo.com/eidosper/" target="_blank"><img src="http://www.weibo.com/favicon.ico" alt="" width="25"/></a>
        <a href="http://site.douban.com/eidosper/" target="_blank"><img src="http://www.douban.com/favicon.ico" alt="" width="22"/></a>
      </div>
      <div id="particles-js"></div>
    </div>

    <div class="index-content">
      <ul class="artical-list">
        {% for post in site.categories.blog %}
        <li>
          <a href="http://eidosper.github.io" class="title">main page test</a>
          <div class="title-desc">Test</div>
        </li>
<a href="http://weibo.com/eidosper/" target="_blank"><img src="http://www.weibo.com/favicon.ico" alt="" width="25"/></a>
        {% endfor %}
      </ul>
    </div>
  </div>
</body>
