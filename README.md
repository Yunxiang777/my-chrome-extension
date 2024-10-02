# My Chrome Extension

這是一個簡單的 Google Chrome 擴充功能範例，當用戶點擊擴充功能按鈕時，會彈出一個彈窗並顯示按鈕，點擊按鈕會顯示提示訊息。

## 目錄結構
<pre>
my-chrome-extension/<br>
│ 
├── images/                    # 擴充功能圖標
│   ├── icon16.png             # 16x16 圖標
│
├── popup.html                 # 彈出介面的 HTML 文件
├── popup.js                   # 彈出介面的 JavaScript 文件
└── manifest.json              # 擴充功能的配置文件
</pre>

## 載入擴充功能

1. 打開 Chrome 瀏覽器，並輸入 `chrome://extensions/`。
2. 打開右上角的「開發人員模式」。
3. 點擊「載入未封裝項目」，然後選擇你創建的擴充功能目錄。
