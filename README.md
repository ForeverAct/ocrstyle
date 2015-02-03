#<img src="ocrstyle.ico" alt="pageres">OCR Style

##Optical Character Recognition

##背景
本程序最初是想用于发票识别的，目前可以通过ocrengine和imageprocess动态库进行二次开发。

##功能
* 图片识别文字的软件。
* 支持截图。
* 支持选择识别的区域。
* 支持选择识别的语言。
* 支持倾斜纠正。
* 支持保存识别的文字。
* 支持多种语言的识别，内置了中文和英文，可以根据需要下载其它语言。

##编译环境
* ocrstyle 使用的Qt4.8开发的。
* ocrengine 使用Visual C++ Express 2008开发的。这个工程依赖third-party目录下的tesseract OCR开发库，目前是google维护的，项目地址：http://code.google.com/p/tesseract-ocr/。当时开发的时候官方只有VC2008的开发库，于是就用的VC2008开发了。
* imageprocess 使用的Visual C++ Express 2010开发的。这个工程依赖于OpenCV。项目地址：http://opencv.org/

##截图
###主界面
![](./snapshots/ocrstyle_main.png)

###英文图片倾斜纠正并识别
![](./snapshots/ocrstyle-english-deskew-recognition.png)

###中文发票进行区域选择并识别
![](./snapshots/ocrstyle-chinese-select-region-recognition.png)

