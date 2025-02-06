# Instagram Post Web Crawler

## 功能特點
- 自動登入 Instagram 帳號
- 自動收集指定帳號的貼文連結
- 根據關鍵字（泰國、越南、印尼）篩選貼文
- 支援無頭模式（headless）瀏覽器操作
- 自動滾動頁面以加載更多內容

## 環境需求
- Python 3.x
- undetected-chromedriver
- BeautifulSoup4
- Selenium WebDriver
- Chrome瀏覽器

## 安裝步驟
1. 複製此專案：
```bash
git clone [你的專案URL]
cd [專案資料夾名稱]
```

2. 安裝所需套件：
```bash
pip install undetected-chromedriver
pip install beautifulsoup4
pip install selenium
```

## 使用方法
1. 在程式碼中設定您的 Instagram 帳號資訊：
```python
username.send_keys("你的使用者名稱")
password.send_keys("你的密碼")
```

2. 執行程式：
```bash
python main.py
```

## 主要功能說明

### setup_browser()
- 設置 Chrome 瀏覽器選項
- 配置無頭模式和其他必要參數
- 返回配置好的瀏覽器實例

### collect_links()
- 自動收集目標帳號的貼文連結
- 支援自動滾動頁面
- 可設定目標收集數量
- 自動過濾重複連結

### analyze_posts()
- 分析收集到的貼文內容
- 根據預設關鍵字進行篩選
- 返回所有貼文和符合條件的貼文

## 注意事項
- 使用前請確保您有正確的 Instagram 帳號權限
- 建議適當設置等待時間，避免被 Instagram 限制訪問
- 運行程式時需要穩定的網路連接
- 請遵守 Instagram 的使用條款和政策
- 登入彈出視窗不一定每次出現，需視情況調整程式碼

## 錯誤處理
程式包含完整的錯誤處理機制：
- 連結收集過程的錯誤處理
- 貼文分析過程的錯誤處理
- 瀏覽器操作的錯誤處理
