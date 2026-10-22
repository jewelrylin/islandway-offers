# 島途 ISLANDWAY — 優惠資料端點

`offers-latest.js` 是「島途」App 開啟時自動抓取的優惠資料。內容：

```js
window.OFFERS_UPDATED = "2026-10-22T...";
window.OFFERS_LATEST = [ { ... }, ... ];
```

更新這個檔案並 push 到 `main`，GitHub Pages 會重新部署；App 下次開啟時會以 cache-busting query 載入。

資料來源：各縣市政府觀光旅遊網、交通部觀光署台灣好湯。折扣、名額與期限以官方公告為準。
