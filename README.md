# 好運色彩研究室 🌈 Lucky Color Lab

輸入你的出生年月日，依據「日柱天干」推算你的五行屬性（甲木～癸水），
再根據你想提升的運勢類別（財運／事業運／考試讀書運／整體補運），
透過五行生剋對應的十神關係，推薦適合的幸運色與幸運小物。

純前端靜態網頁，不需安裝任何套件，開啟 `index.html` 即可使用。

## 線上版本

- 中文版：`index.html`
- English version: `index-en.html`

兩個版本互有語言切換連結。

## 功能特色

- 輸入西元生日，自動換算日柱天干與五行屬性
- 四種補運類別：財運、事業運、考試／讀書運、整體補運
- 每個五行對應一套 20 色的色票（含中文色名、英文色名、HEX 色碼）
- 隨機抽選 3 色作為「今日幸運色」，可重新抽選
- 可展開查看完整色票
- 提供對應的幸運小物建議
- 結果頁附「延伸推薦」卡片，連結至東方原型天賦分析網站

## 在本機開啟

直接用瀏覽器開啟 `index.html`（或 `index-en.html`）即可，不需要伺服器。

## 部署到 GitHub Pages

1. 建立一個新的 GitHub repository。
2. 將 `index.html`、`index-en.html` 上傳到 repo 根目錄。
3. 到 repo 的 **Settings → Pages**，Source 選擇放檔案的分支（如 `main`）與根目錄 `/`，儲存。
4. 等待約 1～2 分鐘，即可於 `https://你的帳號.github.io/repo名稱/` 瀏覽中文版，
   英文版則在網址後加 `/index-en.html`。

## 技術說明

- 純 HTML + CSS + JavaScript，無框架、無建置流程
- 字體使用 Google Fonts（Zen Maru Gothic）
- 日柱天干計算採用儒略日數（Julian Day Number）公式推算

## 免責聲明

本測驗結果僅供參考娛樂，幸運色與幸運小物可作為穿搭、配件或居家佈置的小靈感 🌈
