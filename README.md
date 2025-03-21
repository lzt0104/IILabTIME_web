# 資訊整合實驗室時間追蹤系統

## 系統簡介

這是一個專為資訊整合實驗室設計的時間追蹤系統，主要用於追蹤大一學生在實驗室實習的時間。系統提供打卡計時功能，並支援排行榜和競爭機制，幫助學生更有動力投入實習工作。

![系統預覽](https://via.placeholder.com/800x400?text=資訊整合實驗室時間追蹤系統)

## 功能特色

### 1. 時間追蹤
- 自動使用系統時間計算，防止手動竄改
- 提供即時計時器顯示當前在線時間
- 記錄每週累計實習時間
- 詳細的打卡歷史記錄

### 2. 多用戶支援
- 支援同時追蹤五位大一學生的時間
- 顯示所有在線用戶及其上線時間
- 個人化的使用體驗

### 3. 競爭機制
- 每週實習時間排行榜
- 排行榜自動標記前三名（金、銀、銅）
- 圖表化顯示每位學生的工作時數對比

### 4. 資料視覺化
- 條形圖顯示各學生的每週實習時間
- 歷史記錄時間線
- 直觀的在線/離線狀態指示

## 技術實現

- **前端框架**：Bootstrap 5
- **圖表庫**：Chart.js
- **圖示**：Font Awesome
- **資料儲存**：目前使用前端本地儲存

## 安裝與使用

1. 將所有檔案下載到同一個目錄：
   - `index.html`
   - `style.css`
   - `script.js`

2. 在瀏覽器中開啟 `index.html` 檔案

3. 使用步驟：
   - 從下拉選單選擇您的用戶
   - 點擊「打卡上線」按鈕開始計時
   - 離開實驗室時點擊「打卡下線」按鈕結束計時
   - 查看排行榜了解您的排名

## 系統結構

```
├── index.html      # 主頁面結構
├── style.css       # 樣式表
└── script.js       # JavaScript邏輯
```

## 未來擴展計劃

- 加入後端資料庫支援，確保資料持久化
- 實現用戶認證系統，提高安全性
- 增加管理員功能，方便教師監督和管理
- 提供週報和月報功能
- 加入行動裝置對應的響應式設計優化

## 注意事項

- 本系統目前為純前端實現，資料僅暫存於瀏覽器
- 頁面重新整理後，當前會話的打卡資訊可能會丟失
- 建議在正式使用前，先實現資料持久化功能

## 作者

資訊整合實驗室

