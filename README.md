# 楓根室內裝修設計有限公司｜數位名片

這個專案提供：

- GitHub Pages 公開名片頁
- 後續可直接作為 LINE LIFF Endpoint URL
- 黑金風格單畫面數位名片

## 檔案結構

- `index.html`：主名片頁
- `assets/portrait.jpg`：形象照
- `assets/logo-transparent.png`：透明版 Logo
- `line-flex-message.json`：LINE Flex Message 範本

## 後續接 LIFF

1. 到 LINE Developers 建立 LIFF App
2. 將 GitHub Pages 網址填到 LIFF 的 Endpoint URL
3. 把 `index.html` 內 `window.CARD_CONFIG.liffId` 改成正式 LIFF ID
4. 將 `window.CARD_CONFIG.lineUrl` 換成正式 LINE 連結
5. 將 `line-flex-message.json` 內 `https://example.com/digital-card` 換成正式網址

## 備註

目前頁面已可單獨部署使用；若尚未填入 LIFF ID，頁面會以一般網站模式開啟。