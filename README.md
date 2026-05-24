# JP
日語教學

## 日語學習網站（GitHub Pages 可用）

本專案已提供純前端靜態頁面 `index.html`，可直接貼上每日內容並轉換成學習卡片，包含：

- 句型拆解（假名、羅馬拼音、中文、使用情境、跟讀重點、常見錯誤）
- 小練習題目與答案整理
- 今日跟讀順序整理
- 日文語音播放（使用瀏覽器內建 Web Speech API / SpeechSynthesis）

## 本機使用

直接用瀏覽器開啟 `index.html`，或使用簡單靜態伺服器：

```bash
python -m http.server 8000
```

然後開啟 `http://localhost:8000/`。

## GitHub Pages 部署

這個專案只有靜態檔案，可直接部署到 `github.io`：

1. 到 GitHub 專案 `Settings` → `Pages`
2. `Source` 選 `Deploy from a branch`
3. Branch 選目前分支（例如 `main`），資料夾選 `/ (root)`
4. 儲存後等待部署完成

完成後即可用 `https://<你的帳號>.github.io/JP/` 直接使用。
