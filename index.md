---
layout: default
title: Home
---

<div class="page-card">
  <md-list>
    <md-list-item>
      <div slot="headline">奏音のPWA</div>
      <div slot="supporting-text">Jekyll × MWC で作る SPA 風サイト</div>
      <md-icon slot="start">auto_awesome</md-icon>
    </md-list-item>
  </md-list>

  <p>
    下のリロードなし遷移を試してみてね。
  </p>

  <md-filled-button onclick="loadPage('settings.html')">
    設定ページへ移動
  </md-filled-button>
</div>

<style>
  .page-card {
    background: white;
    padding: 24px;
    border-radius: 16px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.05);
  }
</style>

