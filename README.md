<<<<<<< HEAD

=======
# Google 評論爬蟲工具

這是一個用於抓取 Google 地圖商家評論的爬蟲工具。此工具可以自動擷取商家評論內容、評分和相關圖片。

## 功能特點

- 自動抓取 Google 評論內容
- 擷取評分資訊 
- 下載評論相關圖片
- 避免重複評論
- 資料可輸出為 DataFrame 格式
- 支援自動滾動載入更多評論

## 環境需求

- Python 3.9+
- 必要套件：
  - pandas
  - selenium
  - beautifulsoup4
  - pyautogui
  - undetected_chromedriver
  - webdriver_manager
  - requests
  - Pillow
  - matplotlib

## 安裝方式

1. 複製專案：
```bash
git clone https://github.com/YourUsername/Get-Google-Reviews.git
cd Get-Google-Reviews
```

2. 安裝相依套件：
```bash
pip install -r requirements.txt
```

## 使用說明

1. 開啟 Jupyter Notebook：
```bash
jupyter notebook
```

2. 執行 `get-google-commet.ipynb`

3. 修改目標商家網址：
```python
target_url = 'YOUR_TARGET_URL'
```

## 輸出格式

資料將以 DataFrame 格式儲存，包含以下欄位：
- 評等：評論星級
- 評論：評論內容
- 圖片url：評論附帶的圖片連結

## 注意事項

- 需要穩定的網路連接
- 遵守 Google 服務條款
- 建議適當設置爬蟲間隔時間
- 商業使用前請確認相關法律規範
- 確保 Chrome 版本與 ChromeDriver 版本相符（建議使用最新版本的 Chrome 瀏覽器）
>>>>>>> Google-Review-Crawler
