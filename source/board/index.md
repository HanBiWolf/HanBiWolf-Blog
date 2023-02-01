---
title: 留言板
date: 2022-07-28 00:00:00
---

留下点足迹罢 :)


<!-- CSS -->
<link href="https://unpkg.com/artalk@2.4.4/dist/Artalk.css" rel="stylesheet">

<!-- JS -->
<script src="https://unpkg.com/artalk@2.4.4/dist/Artalk.js"></script>

<!-- Artalk -->
<div id="Comments"></div>
<script>
  new Artalk({
    el:        '#Comments',              // 绑定元素的 Selector
    pageKey:   '',                // 固定链接 (留空自动获取)
    pageTitle: '', // 页面标题 (留空自动获取)
    server:    'https://artalk.hanbiwolf.cc',  // 后端地址
    site:      'HanBiWolf Blog',           // 你的站点名
  })
</script>
