# khlin712.github.io

林鍇弦的個人連結／廣告頁，使用原生 HTML、CSS 與少量 JavaScript 製作，可直接部署到 GitHub Pages。

## 頁面特色

- 大圖主視覺，延續附圖的校園夜景與暖金色視覺語言。
- 所有入口都能用錨點或頁面連結直接跳轉。
- 課程、關於我、工作方式與合作聯絡分區呈現。
- 手機版自適應、鍵盤焦點、跳至主要內容與深／淺色主題切換。
- 不依賴框架或建置工具，適合 GitHub Pages 的純靜態部署。

## 主要檔案

- `index.html`：首頁文案與所有連結。若要換社群網址，直接搜尋 `social-links` 區塊中的 `href`。
- `style.css`：色彩、排版、卡片與響應式版面。
- `me/index.html`：完整自我介紹頁。
- `images/ntulib-night.jpg`：瀏覽器相容的夜景背景；原始 HEIC 仍保留在 `images/`。

## 部署到 GitHub Pages

1. 將這個 `site` 資料夾內容推送到 `main` 分支。
2. 到 GitHub repository 的 **Settings → Pages**。
3. 在 **Build and deployment** 選擇 **Deploy from a branch**。
4. Branch 選 `main`、資料夾選 `/ (root)`，按 **Save**。
5. 等待 GitHub Actions 完成後，網站會位於 `https://khlin712.github.io/`。

這個版本先使用 `hello@example.com` 與各平台首頁作為可替換示範連結；上線前請把它們換成你的實際 Email、LINE、Instagram 與 Threads 網址。

## 參考方向

版面採用高星數開源專案常見的輕量做法：LittleLink（MIT、約 3.1k stars）強調原生 HTML/CSS 與 GitHub Pages 友善部署；Linkhub（MIT、約 87 stars）提供分類連結、社群入口與主題切換的資訊架構。這裡保留其可維護性概念，但重新設計了本頁的視覺與內容。
