# fb_crawl_comment

爬取 *mbasic.facebook.com* 內影片留言。

## 建至過程、心得
使用requests抓取facebook影片留言：[連結](https://aleetsaiya.github.io/2021/06/10/%E4%BD%BF%E7%94%A8requests%E6%8A%93%E5%8F%96facebook%E5%BD%B1%E7%89%87%E7%95%99%E8%A8%80/)

## 下載 chrome driver
檔案內預付 `chromedriver.exe` 版本：96.0.4664.45  
  
ChromeDriver - WebDriver for Chrome：[https://chromedriver.chromium.org/](https://chromedriver.chromium.org/)  


## 操作方式  
需先下載 chromedriver 至電腦內。  
### 輸入 (於程式碼內改寫):
+ 個人帳號密碼
+ chrome_driver 位置
+ 欲爬取影片目標網址
+ 欲爬取目標留言數

### 輸出:
+ 建立 `data` 資料夾，並建立 `留言內容.csv` 檔
