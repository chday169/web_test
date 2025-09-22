# 📚 AI老師的文章展示平台

![GitHub repo size](https://img.shields.io/github/repo-size/chday169/web_test)
![GitHub last commit](https://img.shields.io/github/last-commit/chday169/web_test)
![GitHub Pages](https://img.shields.io/badge/Live-Demo-blue?logo=github)

> 一個支援 PDF 與圖片閱讀的教學展示平台，適合教師、講者、內容創作者分享教材與筆記。

---

## 🖼️ 專案封面

> 📌 預設封面可使用 `assets/images/book1/page1.jpg`  
> 或自行替換為你想展示的圖片。

---

## ✨ 功能特色

- ✅ 支援 PDF 與圖片雙模式切換
- 📄 自動偵測圖片頁數，無需手動設定
- 🔘 上一篇 / 下一篇文章切換
- 📷 圖片模式下顯示「第 X 頁 / 共 Y 頁」
- 🌐 可部署至 GitHub Pages 作為個人教材網站

---

## 📁 資料夾結構

---

## 🚀 使用方式

1. 將你的 PDF 放入 `assets/docs/`
2. 將圖片依照 `page1.jpg` 命名放入 `assets/images/bookX/`
3. 開啟 `index.html` 即可使用
4. 建議使用本地伺服器（如 VS Code Live Server）開啟

---

## 🧠 技術說明

- HTML：頁面結構與選單
- CSS：簡潔排版與樣式
- JavaScript：
  - 模式切換（PDF / 圖片）
  - 自動偵測圖片頁數
  - 動態更新頁面與標題

---

## ☁️ GitHub Pages 部署教學

### ✅ 推送到 GitHub

```bash
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/chday169/web_test.git
git push -u origin master


---

這份 README 已完全對應你的專案名稱、功能與資料夾結構。如果你之後新增更多書籍、功能（例如搜尋、放大圖片、留言板），我也可以幫你更新 README 成進階版本！