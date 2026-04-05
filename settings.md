---
layout: default
title: Settings
---

<div class="page-card">
  <h2>Settings</h2>
  
  <md-list>
    <md-list-item>
      <div slot="headline">ダークテーマ</div>
      <md-switch slot="end" id="theme-toggle"></md-switch>
    </md-list-item>
    <md-divider></md-divider>
    <md-list-item>
      <div slot="headline">通知許可</div>
      <md-checkbox slot="end"></md-checkbox>
    </md-list-item>
  </md-list>

  <div style="margin-top: 32px;">
    <md-outlined-button onclick="loadPage('index.html')">
      ホームへ戻る
    </md-outlined-button>
  </div>
</div>

<script>
  // SPA遷移後も動作するように、ここにロジックを書く
  document.getElementById('theme-toggle')?.addEventListener('change', (e) => {
    console.log('Theme toggled:', e.target.selected);
  });
</script>

