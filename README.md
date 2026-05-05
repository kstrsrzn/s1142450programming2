# s1142450programming2

## 垃圾分類手機 Web App

本專案使用純前端技術實作垃圾分類手機響應式網頁。 它會啟用手機相機，拍攝照片後使用 `models` 資料夾內的 Teachable Machine 影像分類模型進行辨識。

### 使用步驟

1. 開啟 `index.html`
2. 允許網頁存取相機
3. 按「拍照辨識」
4. 看到辨識結果與信心度

> 建議使用本機伺服器開啟，例如 `python3 -m http.server`，以確保相機功能正常。瀏覽器直接開啟 `file://` 可能會被限制。
### GitHub Pages

此專案也可部署到 GitHub Pages，網址為：

`https://kstrsrzn.github.io/s1142450programming2/`

部署後請直接由此網址開啟，模型檔案會自動從 `models/` 資料夾載入。
### 專案結構

- `index.html`：主要頁面
- `styles.css`：響應式手機樣式
- `script.js`：相機拍照與模型辨識邏輯
- `models/`：已訓練好的 Teachable Machine 模型
