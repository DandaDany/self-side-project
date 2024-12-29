# 緯度經度網路爬蟲

這個專案是一個網路爬蟲，設計用來使用 Bing 地圖獲取一系列地址的緯度和經度坐標。

## 功能特點

- 將地址中的全形字元轉換為半形
- 使用 Selenium WebDriver 來自動化網頁瀏覽
- 處理錯誤並進行重試，以確保穩定運作
- 定期將進度保存到 Excel 檔案中

## 系統需求

- Python 3.x
- Pandas
- Selenium
- BeautifulSoup
- undetected_chromedriver
- PyAutoGUI
- webdriver_manager

## 安裝方法

1. 複製此專案庫
2. 安裝所需套件：
   ```
   pip install pandas selenium beautifulsoup4 undetected_chromedriver pyautogui webdriver_manager
   ```

## 使用方法

1. 準備一個包含地址的 Excel 檔案，地址欄位名稱為「工廠地址」
2. 更新腳本中的檔案路徑，指向您的 Excel 檔案
3. 執行腳本：
   ```
   python latitude_longitude_web_crawler.py
   ```

## 輸出結果

腳本會創建一個名為「工廠地址經緯度.xlsx」的 Excel 檔案，其中包含原始地址及其對應的緯度和經度坐標。

## 注意事項

- 本腳本使用 Bing 地圖進行地理編碼。請確保您遵守 Bing 地圖的服務條款。
- 腳本包含避免被偵測為機器人的措施，但請注意地圖服務的使用限制和服務條款。
- 對於無法找到或不明確的地址，腳本會分別標記為「查無地址」或「無明確地址」。
