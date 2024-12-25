# YouTube Live Chat Crawler

這是一個用於擷取 YouTube 直播聊天室訊息的爬蟲工具。此工具可以自動抓取指定 YouTube 直播聊天室的對話內容，並將其儲存為結構化數據。

## 功能特點

- 即時擷取 YouTube 直播聊天室訊息
- 自動記錄訊息發送時間、使用者和內容
- 支援特定時間範圍的訊息收集（例如晚上11點到凌晨3點）
- 可過濾特定用戶的訊息
- 防止重複訊息的收集
- 資料可輸出為 Pandas DataFrame 格式

## 環境需求

- Python 3.9+
- 必要套件：
  - pandas
  - selenium
  - beautifulsoup4
  - pyautogui
  - undetected_chromedriver
  - webdriver_manager

## 安裝方式

1. 克隆專案：
```bash
git clone https://github.com/YourUsername/youtube-chat-crawler.git
cd youtube-chat-crawler
