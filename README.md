# ✨ 10 週年星空光暈產生器 · Anniversary Starfield "10"

用純黑深空 + 四色發光散景光點勾出數字「**10**」，做出類似 Apple「Far Out」風格的星塵主視覺。全程在瀏覽器裡拉桿即時預覽，一鍵下載 PNG（最高 4800×4800）。

> An in-browser generator that traces the number **10** with glowing bokeh particles on a deep-space starfield. Live sliders, one-click PNG export.

## 🚀 使用方式

- **線上版**：把本 repo 開啟 GitHub Pages 後，直接開網址即可（見下方）。
- **本機**：下載 `index.html` 用瀏覽器（Chrome / Safari）打開即可。需連網（字體由 Google Fonts 載入）。

## 🎛️ 可調參數

- **字體**：Nunito / Quicksand / Fredoka / Baloo 2 / Comfortaa / Poppins / Montserrat / Playfair，或自訂輸入任一 Google Fonts 字體名；字重可調
- **「10」與光暈**：光暈強度、10 明顯度（微星塵）、顆粒大小、輪廓密度、柔焦散景比例、外圍飄散量
- **星空背景**：星點數、星芒數、星雲層次、暗角、背景色
- **四色校準**：四個品牌色可自由改色碼
- **SEED**：換一組光點排列
- **下載尺寸**：1600 / 3200 / 4800 px

## 🌐 開啟 GitHub Pages

1. repo → **Settings → Pages**
2. **Source** 選 `main` 分支、資料夾 `/ (root)` → **Save**
3. 等一兩分鐘，網址為 `https://ringsbebe.github.io/tenstar/`

## 🛠️ 技術

純前端，單一 `index.html`（HTML + Canvas 2D），無框架、無建置。光暈為多層高斯模糊 + 加法混色（bloom），星點與散景皆即時繪製。字體採 Google Fonts CDN。

## 📄 授權

MIT License．字體版權屬各自作者（皆為 Google Fonts 上的開源字體，SIL Open Font License）。
