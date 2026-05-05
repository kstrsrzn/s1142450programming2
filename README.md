# s1142450programming2

## 垃圾分類手機 Web App

本專案使用純前端技術實作垃圾分類手機響應式網頁。 它會啟用手機相機，拍攝照片後使用 `models` 資料夾內的 Teachable Machine 影像分類模型進行辨識。

### 使用步驟

1. 確保 `index.html` 和 `models/` 資料夾在同一個資料夾內
2. 直接開啟 `index.html`
3. 允許網頁存取相機
4. 按「拍照辨識」
5. 看到辨識結果與信心度

> 此專案為純前端靜態網頁，不需要後端伺服器。若使用 GitHub Pages，也可直接開啟以下網址：

`https://kstrsrzn.github.io/s1142450programming2/`

### GitHub Pages

此專案可部署到 GitHub Pages，部署後請直接由上述網址開啟，模型檔案會自動從 `models/` 資料夾載入。
### 專案結構

- `index.html`：純前端單頁應用
- `models/`：已訓練好的 Teachable Machine 模型
