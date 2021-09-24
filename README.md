# 2018-計算機概論-Final Project

### 1.Target
利用爬蟲技術將電腦中的Youtube首頁的影片抓下來，顯示你想看到前_名觀看人數的影片，再利用長條圖做觀看次數的比較

### 2.Motivation
現代人每天有大部分時間都拿來看影片，於是我選了一個最大的影片平台來分析首頁中，也就是你比較有興趣的影片中其中觀看人數更高的影片及連結，既可以方便找到有趣的影片也可以利用這個分析了解最新Youtube的趨勢，簡單的增加與他人的話題也不失看自己喜歡影片的原意。

### 3.Implement
    1.	將爬到的內容刪去不必要的資訊 ( Youtube自己的版面配置、重複的影片、頻道連結 …等等 )
    2.	觀看數將數字重新拼接，並判斷是否大於6位數使其分割次數不同，例如：123,456 => 123456 和 123,456,789 => 123456789
    3.	抓取所有影片的並分析出需要數量的超連結
    4.	擷取需要的影片後和流量輸出成長條圖
    5.	依照觀看量決定圖表大小

### 4.Result
![image](https://drive.google.com/uc?export=view&id=1XlJkwWyEkhZH3fFhMbkyLMDs6cKqFGXq)  

### 5.Reference
[Python中使用多个分隔符分隔字符串re.split](https://blog.csdn.net/programmer_at/article/details/77409507 "link")  
[Python：爬蟲處理流程及網頁解析](https://kknews.cc/tech/3jjpj8g.html "link")  
[Day23Beautiful Soup網頁解析！](https://ithelp.ithome.com.tw/articles/10196817 "link")  
