# yolo_tlite
＃研究目標

希望能將yolo.tlite移植至android系統當中

＃研究方法

＃＃我們開發方法有三

1.使用原始
2.使用其他有成功之程式碼
3.使用unity去包yolo.tlite再丟進android

＃研究問題

＃＃以下將針對以上三種方法所遇到之問題進行說明

1. 使用原始
所遇到的問題：考慮使用官網之模型先進行執行，這部份是可以行，但換成yolo.tlite會有閃退現象

2.使用其他github之程式碼
所遇到的問題：基於第一點之問題，我們改使用其他線上github並且發現在youtube上作者也有發布他成功之作法
但實際使用後發現android上的會因為openGL而失敗，其原因還不了解

3.使用unity 使用unity去包yolo.tlite再丟進android
所遇到的問題：基於openGL會有問題所以我們改用unity去包yolo.tlite
