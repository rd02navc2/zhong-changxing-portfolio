# 鍾昌興｜個人作品集網站

這是一個純 HTML / CSS / JavaScript 的繁體中文靜態網站，可直接部署到 GitHub Pages，不需要 Node.js、建置工具或後端伺服器。

## 本機預覽
直接以瀏覽器開啟 `index.html` 即可預覽。

## 部署到 GitHub Pages
1. 在 GitHub 建立新的 repository，例如 `zhong-changxing-portfolio`。
2. 將 ZIP 解壓後的所有檔案上傳至 repository 根目錄。
3. 進入 repository 的 **Settings → Pages**。
4. 在 **Build and deployment** 選擇 `Deploy from a branch`。
5. Branch 選 `main`，資料夾選 `/ (root)`，按 Save。
6. 等待 GitHub Pages 完成部署，網站網址通常會是 `https://你的帳號.github.io/zhong-changxing-portfolio/`。

也可使用內附的 `.github/workflows/pages.yml` 以 GitHub Actions 部署。

## 上線前請先修改
- `index.html` 的聯絡資訊：公開 Email、LinkedIn、GitHub URL。
- 確認個人簡介、專案內容與實際工作成果一致。
- `resume/` 內的履歷檔可持續更新；網站會提供 Word 與 Markdown 下載。
- 若要放正式履歷 PDF，可自行加入 PDF 檔並在 `index.html` 增加下載連結。

## 內容與安全提醒
架構圖是邏輯示意，不代表所有模組均已部署正式環境。尚待外部環境驗證的功能請保留相應說明。公開前請檢查是否含公司機密、內網位址、憑證、客戶資料或敏感商業資訊。
