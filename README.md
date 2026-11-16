# TRY ESPORT｜PUBG 電競知識庫

一個以 PUBG 團隊戰術與訓練賽知識為主題的靜態教學網站。使用 `AGENTS.md` 規範 AI 協助開發的方式，確保後續新增內容維持一致。

## 網站頁面
- `index.html`：首頁與分類入口
- `pages/basics.html`：PUBG 基礎觀念
- `pages/tactics.html`：團隊戰術教學
- `pages/scoring.html`：訓練賽積分教學（示範規則）

## 本機使用
下載後直接開啟 `index.html` 即可瀏覽。

## GitHub Pages 部署
1. 在 GitHub 建立公開 repository，例如 `try-esport-wiki`。
2. 將此資料夾**內的所有檔案**上傳到 repository 根目錄（必須讓 `index.html` 位於根目錄）。
3. 到 Settings → Pages → Build and deployment → Deploy from a branch。
4. 選擇 `main` 分支與 `/(root)`，按 Save。
5. 等候部署完成，網站網址通常為 `https://你的帳號.github.io/try-esport-wiki/`。

## AI 擴充流程
請 AI 先閱讀 `AGENTS.md`，再依照規範新增 `pages/*.html`，同步更新首頁卡片與本文件。

## 技術
HTML5 / CSS3 / Vanilla JavaScript。無需 API 金鑰、後端或額外安裝。

> 非官方粉絲教育專案，與 PUBG 或 KRAFTON 無隸屬或合作關係。
