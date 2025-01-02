# Self-Project 介紹

這是一個包含多個獨立專案的程式集合，主要專注於網路爬蟲和數據分析。每個專案都針對特定需求開發，包含完整的程式碼和文檔。

## 專案列表

### 1. YouTube Web Crawler
- 抓取 YouTube 直播聊天室的對話內容
- 支援自動滾動載入更多訊息
- 輸出結構化的聊天記錄

### 2. Google Review Crawler
- 擷取 Google Maps 商家評論
- 包含評分和評論內容
- 支援圖片下載功能

### 3. Yield Rate Web Crawler
- 股票殖利率計算工具
- 自動抓取公開資料
- 提供預估價格區間

### 4. Address to Latitude/Longitude
- 地址轉換為經緯度座標
- 批量處理功能
- 支援多種地址格式

## 技術棧

- Python 3.9+
- 主要使用套件：
  - pandas
  - selenium
  - beautifulsoup4
  - requests
  - numpy

## 安裝方式

1. 複製專案：
```bash
git clone https://github.com/YourUsername/self-side-project.git
```

2. 安裝相依套件：
```bash
pip install -r requirements.txt
```

## 使用說明

每個子專案都有其獨立的 README 文件，包含詳細的使用說明和注意事項。請參考各專案資料夾中的文檔。

## 專案結構
```
self-side-project/
├── Youtube-web-crawler/
├── Google-Review-Crawler/
├── Yield-rate-web-crawler/
├── address_to_Latitude_Longitude/
└── requirements.txt
```

## 注意事項

- 請遵守網站的使用規範和爬蟲政策
- 建議在使用前先閱讀各專案的文檔
