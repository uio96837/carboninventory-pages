# carboninventory-pages

碳溯 Carbon Explorer(原專案代號 CarbonInventory)的兩個公開靜態頁面,透過 GitHub Pages 託管:

- [`index.html`](index.html) — 產品介紹 landing page(係数查證方法論、Scope 涵蓋範圍、實機截圖、架構圖)
- [`privacy.html`](privacy.html) — 隱私權政策(Play 商店上架要求的公開網址)

啟用 GitHub Pages 後,對應網址為:

```
https://<你的帳號>.github.io/carboninventory-pages/
https://<你的帳號>.github.io/carboninventory-pages/privacy.html
```

## 說明

這個 repo **只放這兩頁靜態 HTML**,不包含 app 原始碼——app 本身是獨立的私有 repo。
兩頁皆為單檔 HTML,自帶 CSS,不依賴任何外部資源或建置流程,直接透過 GitHub Pages
託管即可,無需額外設定。

內容若有更新(例如係数資料庫增減、隱私權政策條款變動),直接編輯對應的 HTML 檔案、
commit、push 即可,GitHub Pages 會自動重新部署。
