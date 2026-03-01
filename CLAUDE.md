# CLAUDE.md

## Project Overview
- **Repo**: sjhuangphi.github.io (GitHub Pages 靜態網站)
- **用途**: 測試用頁面集合，包含各種第三方服務整合測試
- **部署**: GitHub Pages，main 分支自動部署

## Project Structure
- 純靜態 HTML 頁面，無建置工具或框架
- 每個 HTML 檔案為獨立測試頁面

### 主要頁面
- `index.html` — 極驗 (Geetest) 設備指紋測試
- `apple*.html` — Sign in with Apple 登入測試
- `line_index.html` — LINE 相關測試
- `network.html` — 網路相關測試
- `image.html` — 圖片相關測試

## Git Conventions
- **主分支**: main
- **Commit 語言**: 中文
- **Commit 格式**: `feat: 描述` / `fix: 描述`
- **分支命名**: `dev/<功能名稱>`

## Development Notes
- 無需安裝依賴，直接編輯 HTML 即可
- 第三方 SDK 透過 CDN 引入（Tailwind CSS、Prism.js、Apple JS SDK、Geetest SDK 等）
- 測試頁面可能包含 ngrok 等臨時網址，使用前需確認是否仍有效
