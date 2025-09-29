# Android APK - WebView 包裝你的雲端網站

這是可直接用 Android Studio 打開的專案。它會把你的雲端網站包成 APK。
- 預設網址在 `app/src/main/res/values/strings.xml` 的 `<string name="base_url">...</string>`
- 建議使用 HTTPS（例如 Render：`https://your-site.onrender.com`）

## 匯入步驟
1. 用 Android Studio 開啟此資料夾（含 `settings.gradle` 的根目錄）。
2. 修改 `strings.xml` 的 `base_url` 為你的雲端網址。
3. 連接手機或用模擬器，點擊 ▶️ 執行；或 Build > Build APK(s) 產生 APK。

## 常見問題
- 若載入空白頁：確認你的網站網址可公開存取、且使用 HTTPS。
- 若網站需要相機/麥克風/檔案權限：請在 `AndroidManifest.xml` 加上對應權限並於程式中請求。
