# FHIR SMART App

這是一個基於 SMART on FHIR 的 JavaScript 應用程式。

## 如何使用

此應用程式需要通過 SMART Launcher 啟動，不能直接訪問。

### 方法 1: 使用 SMART Launcher（推薦）

1. 訪問 [SMART Launcher](http://launch.smarthealthit.org/)
2. 在 "App Launch URL" 欄位輸入：`https://onesebun.github.io/fhir-Exercise1/launch.html`
3. 選擇病患和其他選項
4. 點擊 "Launch" 按鈕

### 方法 2: 直接連結（本地測試）

如果在本地運行（http://127.0.0.1:8080），可以點擊：
```
http://127.0.0.1:8080/launch.html?launch=eyJhIjoiMSJ9&iss=https%3A%2F%2Flaunch.smarthealthit.org%2Fv%2Fr4%2Ffhir
```

## 本地開發

```bash
npx http-server
```

然後訪問 http://127.0.0.1:8080
