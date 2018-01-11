
#使用说明

## 系统要求
1. **安卓手机一部看直播**
2. **电脑一台查看搜索结果**

## 原理
每当题目出来的时候按下回车键即可瞬间打开百度 
 主要原理使用Android adb进行截图,截取题目,使用汉王OCR识别图片中的文字,在使用selenium
 打开百度.汉王云ocrAPI，参考了 [wuditken/MillionHeroes](https://github.com/wuditken/MillionHeroes) 项目


## 使用步骤
### 安装python
1.获取项目后把项目解压 解压后是这样的

1. 把项目放在D盘路径下
2. 在software路径下 双击python-3.6.4.exe 一路点击next 已经安装的跳过
3. 在software路径下 双击ChromeStandalone_63.0.3239.132_Setup.exe 一路点击next 已经安装的跳过
4. 打开Android手机,用usb连接电脑,百度 自己手机型号 打开开发者模式
5. 执行adb.bat 如果 没有出现 device not find则手机连接正常
6. 执行pip.bat
7. 打开 http://console.bce.baidu.com/ai/#/ai/ocr/app/detail~appId=217403 注册账号 开通文字识别 可能需要充值一块钱
   在config.py 文件中 修改app_id app_key app_secret 可以跳过,但不保证图像文字识别稳定
8. 执行main.bat 每当题目出来的时候在黑窗口中 按回车键发起搜索




