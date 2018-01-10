# 如果觉得过程太麻烦的伙伴,直接看效果图然后加入QQ群 今天下午会在群里发布安装更方便,功能更强大的版本

# 百万英雄/冲顶大会/芝士超人 答题助手 瞬间打开百度
 每当题目出来的时候按下回车键即可瞬间打开百度,主要支持Android系统
 主要原理使用Android adb进行截图,截取题目,使用汉王OCR识别图片中的文字,在使用selenium
 打开百度.汉王云ocrAPI，参考了 [wuditken/MillionHeroes](https://github.com/wuditken/MillionHeroes) 项目

# 系统要求
1. **谷歌浏览器**
2. **安卓手机一部 电脑一台**
3. **python3.6**

### 使用步骤
1. 安装python3.6 [python下载地址](https://www.python.org/downloads/)
2. 在本项目根路径下执行 pip install -r requirements.txt
3. 修改默认的配置文件config.py 中Chrome Driver的路径
 Chrome Driver 在lib有一份,需要设置存放的路径 [driver下载地址](https://sites.google.com/a/chromium.org/chromedriver/downloads)
4. 修改配置文件config.py 中图片存放路径
5. 如果汉王OCR无法使用,需要自己使用自己的code [汉王API](https://market.aliyun.com/products/57124001/cmapi011523.html?spm=5176.730005.0.0.B1mZNd#sku=yuncode552300000)
6. 把手机设为开发者模式,在电脑环境变量中添加adb路径,lib中有下载好的adb,调试好adb
7. 每个手机像素不一样,在config文件中调整
8. 启动项目 python helper.py 每当题目出来时按下回车键即可   


### 效果图
![](https://github.com/idealspark/ZhiShiWenDa-Helper/blob/master/image/xiaoguo1.png)
![](https://github.com/idealspark/ZhiShiWenDa-Helper/blob/master/image/xiaoguo2.png)

### qq群:612045335
![](https://github.com/idealspark/ZhiShiWenDa-Helper/blob/master/image/qun.png)

