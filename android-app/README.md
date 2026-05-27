# Android app

這個資料夾是把 `C:\Users\user\Desktop\codex1\index.html` 包成 Android APP 的專案。

重點：

- 採用 `WebView` 載入目前的單字卡介面
- 建置前會自動把根目錄的 `index.html` 與 `高中英文參考詞彙表.csv` 複製到 app assets
- 支援網頁中的檔案選擇器，可在 Android 裝置匯入 `.csv`、`.tsv`、`.txt`、`.json`
- 已補上 `gradlew` / `gradlew.bat` 與 Gradle wrapper 設定檔；若缺少 `gradle-wrapper.jar`，可直接用 Android Studio 開啟專案後讓 IDE 協助補齊，或手動加入 wrapper JAR

使用方式：

1. 用 Android Studio 開啟 `C:\Users\user\Desktop\codex1\android-app`
2. 等 Gradle Sync 完成
3. 執行模擬器或實機
4. 需要 APK 時可使用 `Build > Build APK(s)`
