# yolo_tlite
基於yolo.tlite檔案太大因此放在雲端(yolo_tlite資料夾)-yolov3-416-fp16.tflite,yolov3.tflite,yolov4.tflite(https://drive.google.com/drive/my-drive)


# 研究目標

希望能將yolo.tlite移植至android系統當中，其中要做成yolo.tlite之github為(https://github.com/hunglc007/tensorflow-yolov4-tflite)

# 研究方法

## 我們開發方法有三

1.使用原始

github:(https://github.com/tensorflow/examples/tree/master/lite/examples/object_detection/android)

2.使用其他有成功之程式碼

github:(https://github.com/haroonshakeel/tensorflow-yolov4-tflite?fbclid=IwAR1xCZbbCTYf4-Wsq5Gpr-iv6TXhlkNNIGGJZYfj3Di0Dngq27MjlJNOCgI#setting-up-environment)

youtube:(https://www.youtube.com/watch?v=YzAjAS6Os8c&list=PLUE9cBml08yhizwPqHSRZZgNs9_jaQG1q)

3.使用unity去包yolo.tlite再丟進android


github:(https://github.com/derenlei/Unity_Detection2AR?fbclid=IwAR3ciGKNHzS0-EhJWFWyUq7DHv9rZS8BHYLlznT8T8b4tSCwAUfLyCQpcNY)

# 研究問題

## 以下將針對以上三種方法所遇到之問題進行說明


1. 使用原始

所遇到的問題：考慮使用官網之模型先進行執行，這部份是可以行，但換成yolo.tlite會有閃退現象

2.使用其他github之程式碼

所遇到的問題：基於第一點之問題，我們改使用其他線上github並且發現在youtube上作者也有發布他成功之作法

但實際使用後發現android上的會因為openGL而失敗，其原因還不了解

3.使用unity 使用unity去包yolo.tlite再丟進android

所遇到的問題：基於openGL會有問題所以我們改用unity去包yolo.tlite，其中在github提到若要使用自己的模型去跑需先轉檔成ONNX格式，這部份轉換不順利（也許是我對unity）




